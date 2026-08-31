FROM alpine:latest

ARG PB_VERSION=0.39.8

RUN apk add --no-cache \
    unzip \
    ca-certificates \
    wget

# Download PocketBase binary
RUN wget https://github.com/pocketbase/pocketbase/releases/download/v${PB_VERSION}/pocketbase_${PB_VERSION}_linux_amd64.zip \
    && unzip pocketbase_${PB_VERSION}_linux_amd64.zip -d /pb/ \
    && rm pocketbase_${PB_VERSION}_linux_amd64.zip

COPY pb_hooks /pb/pb_hooks
COPY pb_migrations /pb/pb_migrations

EXPOSE 8090

# Matches the "start" script in package.json (data dir mounted at /pb/pb_data)
CMD ["/pb/pocketbase", "serve", "--http=0.0.0.0:8090", "--dir=/pb/pb_data", "--migrationsDir=/pb/pb_migrations", "--hooksDir=/pb/pb_hooks", "--hooksWatch=false", "--encryptionEnv=PB_ENCRYPTION_KEY"]
