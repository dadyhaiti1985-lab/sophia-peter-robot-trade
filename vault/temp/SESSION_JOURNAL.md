## 2026-08-27 16:36:25.940Z load
- url: http://localhost:3000/

## 2026-08-27 16:36:27.741Z navigate
- url: http://localhost:3000/
- via: replaceState

## 2026-08-27 16:36:28.826Z console.warn
- text: [Perf] Low FPS detected: 5

## 2026-08-27 16:36:29.861Z console.warn
- text: [Perf] Low FPS detected: 28

## 2026-08-27 16:36:30.884Z console.warn
- text: [Perf] Low FPS detected: 18

## 2026-08-27 16:36:31.894Z console.warn
- text: [Perf] Low FPS detected: 25

## 2026-08-27 16:36:32.538Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":" KONT PA OU"}

## 2026-08-27 16:36:32.540Z navigate
- url: http://localhost:3000/dashboard/oracle-trader-pro
- via: pushState

## 2026-08-27 16:36:32.568Z navigate
- url: http://localhost:3000/login
- via: replaceState

## 2026-08-27 16:36:32.899Z console.warn
- text: [Perf] Low FPS detected: 44

## 2026-08-27 16:36:33.899Z console.warn
- text: [Perf] Low FPS detected: 50

## 2026-08-27 16:36:35.282Z focus
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"login-email","placeholder":"jan@ekzanp.com","label":"email","value":"","valueLength":0,"text":""}

## 2026-08-27 16:36:35.407Z click
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"login-email","placeholder":"jan@ekzanp.com","label":"email","value":"","valueLength":0,"text":""}

## 2026-08-27 16:36:36.285Z click
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"login-email","placeholder":"jan@ekzanp.com","label":"email","value":"","valueLength":0,"text":""}

## 2026-08-27 16:36:39.933Z console.warn
- text: [Perf] Low FPS detected: 45

## 2026-08-27 16:36:40.949Z console.warn
- text: [Perf] Low FPS detected: 52

## 2026-08-27 16:36:58.882Z focus
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"login-email","placeholder":"jan@ekzanp.com","label":"email","value":"","valueLength":0,"text":""}

## 2026-08-27 16:36:58.999Z click
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"login-email","placeholder":"jan@ekzanp.com","label":"email","value":"","valueLength":0,"text":""}

## 2026-08-27 16:37:02.000Z change
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"login-email","placeholder":"jan@ekzanp.com","label":"email","value":"dadyhaiti1985@gmail.com","valueLength":23,"text":""}

## 2026-08-27 16:37:02.000Z blur
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"login-email","placeholder":"jan@ekzanp.com","label":"email","value":"dadyhaiti1985@gmail.com","valueLength":23,"text":""}

## 2026-08-27 16:37:02.001Z focus
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=0]","valueLength":0,"text":""}

## 2026-08-27 16:37:02.121Z click
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=0]","valueLength":0,"text":""}

## 2026-08-27 16:37:13.164Z focus
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=0]","valueLength":0,"text":""}

## 2026-08-27 16:37:13.259Z click
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=0]","valueLength":0,"text":""}

## 2026-08-27 16:37:19.005Z change
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=14]","valueLength":14,"text":""}

## 2026-08-27 16:37:19.005Z click
- element: {"tag":"button","role":null,"ariaLabel":null,"name":null,"type":"submit","id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Konekte (Login)"}

## 2026-08-27 16:37:19.009Z submit
- action: http://localhost:3000/login
- fields: [{"label":"email","type":"email","value":"dadyhaiti1985@gmail.com","length":23,"redacted":false},{"label":"password","type":"password","value":"[redacted:length=14]","length":14,"redacted":true},{"label":"[submit]","type":"submit","value":"","length":0,"redacted":false}]

## 2026-08-27 16:37:19.018Z blur
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=14]","valueLength":14,"text":""}

## 2026-08-27 16:37:19.025Z network.error
- method: POST
- url: http://localhost:3000/hcgi/platform/api/collections/users/auth-with-password
- status: 404
- statusText: Not Found
- requestBody: {"identity":"dadyhaiti1985@gmail.com","password":"[redacted:length=14]"}
- durationMs: 11

## 2026-08-27 16:37:19.026Z console.error
- text: Fetch error from http://localhost:3000/hcgi/platform/api/collections/users/auth-with-password: 

## 2026-08-27 16:37:19.029Z console.error
- text: [AuthContext] Login failed: {"status":404,"message":"Something went wrong while processing your request.","response":{},"isAbort":false}

## 2026-08-27 16:37:22.199Z focus
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=14]","valueLength":14,"text":""}

## 2026-08-27 16:37:22.285Z click
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=14]","valueLength":14,"text":""}

## 2026-08-27 16:37:24.902Z click
- element: {"tag":"div","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"RoboKriptoRetounen KonekteAntre pou wè pèfòmans ouImèl (Email)Modpas (Password)Konekte (Login)Oswa kontinye avèkGoogleOu poko gen kont? Enskri isit la"}

## 2026-08-27 16:37:31.483Z change
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=14]","valueLength":14,"text":""}

## 2026-08-27 16:37:31.483Z click
- element: {"tag":"button","role":null,"ariaLabel":null,"name":null,"type":"submit","id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Konekte (Login)"}

## 2026-08-27 16:37:31.484Z submit
- action: http://localhost:3000/login
- fields: [{"label":"email","type":"email","value":"dadyhaiti1985@gmail.com","length":23,"redacted":false},{"label":"password","type":"password","value":"[redacted:length=14]","length":14,"redacted":true},{"label":"[submit]","type":"submit","value":"","length":0,"redacted":false}]

## 2026-08-27 16:37:31.486Z blur
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=14]","valueLength":14,"text":""}

## 2026-08-27 16:37:31.501Z network.error
- method: POST
- url: http://localhost:3000/hcgi/platform/api/collections/users/auth-with-password
- status: 404
- statusText: Not Found
- requestBody: {"identity":"dadyhaiti1985@gmail.com","password":"[redacted:length=14]"}
- durationMs: 17

## 2026-08-27 16:37:31.501Z console.error
- text: Fetch error from http://localhost:3000/hcgi/platform/api/collections/users/auth-with-password: 

## 2026-08-27 16:37:31.502Z console.error
- text: [AuthContext] Login failed: {"status":404,"message":"Something went wrong while processing your request.","response":{},"isAbort":false}

## 2026-08-27 16:37:44.899Z focus
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=14]","valueLength":14,"text":""}

## 2026-08-27 16:37:45.002Z click
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=14]","valueLength":14,"text":""}

## 2026-08-27 16:37:45.646Z blur
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=14]","valueLength":14,"text":""}

## 2026-08-27 16:37:45.790Z click
- element: {"tag":"button","role":null,"ariaLabel":null,"name":null,"type":"submit","id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Konekte (Login)"}

## 2026-08-27 16:37:45.790Z submit
- action: http://localhost:3000/login
- fields: [{"label":"email","type":"email","value":"dadyhaiti1985@gmail.com","length":23,"redacted":false},{"label":"password","type":"password","value":"[redacted:length=14]","length":14,"redacted":true},{"label":"[submit]","type":"submit","value":"","length":0,"redacted":false}]

## 2026-08-27 16:37:45.801Z network.error
- method: POST
- url: http://localhost:3000/hcgi/platform/api/collections/users/auth-with-password
- status: 404
- statusText: Not Found
- requestBody: {"identity":"dadyhaiti1985@gmail.com","password":"[redacted:length=14]"}
- durationMs: 10

## 2026-08-27 16:37:45.801Z console.error
- text: Fetch error from http://localhost:3000/hcgi/platform/api/collections/users/auth-with-password: 

## 2026-08-27 16:37:45.801Z console.error
- text: [AuthContext] Login failed: {"status":404,"message":"Something went wrong while processing your request.","response":{},"isAbort":false}

## 2026-08-27 16:37:47.864Z focus
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=14]","valueLength":14,"text":""}

## 2026-08-27 16:37:47.993Z click
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=14]","valueLength":14,"text":""}

## 2026-08-27 16:37:55.554Z click
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=0]","valueLength":0,"text":""}

## 2026-08-27 16:38:00.881Z change
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=14]","valueLength":14,"text":""}

## 2026-08-27 16:38:00.881Z click
- element: {"tag":"button","role":null,"ariaLabel":null,"name":null,"type":"submit","id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Konekte (Login)"}

## 2026-08-27 16:38:00.881Z submit
- action: http://localhost:3000/login
- fields: [{"label":"email","type":"email","value":"dadyhaiti1985@gmail.com","length":23,"redacted":false},{"label":"password","type":"password","value":"[redacted:length=14]","length":14,"redacted":true},{"label":"[submit]","type":"submit","value":"","length":0,"redacted":false}]

## 2026-08-27 16:38:00.883Z blur
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=14]","valueLength":14,"text":""}

## 2026-08-27 16:38:00.886Z network.error
- method: POST
- url: http://localhost:3000/hcgi/platform/api/collections/users/auth-with-password
- status: 404
- statusText: Not Found
- requestBody: {"identity":"dadyhaiti1985@gmail.com","password":"[redacted:length=14]"}
- durationMs: 4

## 2026-08-27 16:38:00.886Z console.error
- text: Fetch error from http://localhost:3000/hcgi/platform/api/collections/users/auth-with-password: 

## 2026-08-27 16:38:00.886Z console.error
- text: [AuthContext] Login failed: {"status":404,"message":"Something went wrong while processing your request.","response":{},"isAbort":false}

## 2026-08-27 16:38:22.691Z focus
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=14]","valueLength":14,"text":""}

## 2026-08-27 16:38:22.781Z click
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=14]","valueLength":14,"text":""}

## 2026-08-27 16:38:32.602Z click
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=14]","valueLength":14,"text":""}

## 2026-08-27 16:38:37.276Z click
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=14]","valueLength":14,"text":""}

## 2026-08-27 16:38:50.020Z click
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=0]","valueLength":0,"text":""}

## 2026-08-27 16:38:58.235Z click
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=0]","valueLength":0,"text":""}

## 2026-08-27 16:39:04.201Z click
- element: {"tag":"button","role":null,"ariaLabel":null,"name":null,"type":"submit","id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Konekte (Login)"}

## 2026-08-27 16:39:04.201Z submit
- action: http://localhost:3000/login
- fields: [{"label":"email","type":"email","value":"dadyhaiti1985@gmail.com","length":23,"redacted":false},{"label":"password","type":"password","value":"[redacted:length=14]","length":14,"redacted":true},{"label":"[submit]","type":"submit","value":"","length":0,"redacted":false}]

## 2026-08-27 16:39:04.203Z blur
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=14]","valueLength":14,"text":""}

## 2026-08-27 16:39:04.217Z network.error
- method: POST
- url: http://localhost:3000/hcgi/platform/api/collections/users/auth-with-password
- status: 404
- statusText: Not Found
- requestBody: {"identity":"dadyhaiti1985@gmail.com","password":"[redacted:length=14]"}
- durationMs: 16

## 2026-08-27 16:39:04.217Z console.error
- text: Fetch error from http://localhost:3000/hcgi/platform/api/collections/users/auth-with-password: 

## 2026-08-27 16:39:04.218Z console.error
- text: [AuthContext] Login failed: {"status":404,"message":"Something went wrong while processing your request.","response":{},"isAbort":false}

## 2026-08-27 16:39:10.851Z focus
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=14]","valueLength":14,"text":""}

## 2026-08-27 16:39:10.955Z click
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=14]","valueLength":14,"text":""}

## 2026-08-27 16:39:20.653Z change
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=14]","valueLength":14,"text":""}

## 2026-08-27 16:39:20.653Z click
- element: {"tag":"button","role":null,"ariaLabel":null,"name":null,"type":"submit","id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Konekte (Login)"}

## 2026-08-27 16:39:20.653Z submit
- action: http://localhost:3000/login
- fields: [{"label":"email","type":"email","value":"dadyhaiti1985@gmail.com","length":23,"redacted":false},{"label":"password","type":"password","value":"[redacted:length=14]","length":14,"redacted":true},{"label":"[submit]","type":"submit","value":"","length":0,"redacted":false}]

## 2026-08-27 16:39:20.655Z blur
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=14]","valueLength":14,"text":""}

## 2026-08-27 16:39:20.667Z network.error
- method: POST
- url: http://localhost:3000/hcgi/platform/api/collections/users/auth-with-password
- status: 404
- statusText: Not Found
- requestBody: {"identity":"dadyhaiti1985@gmail.com","password":"[redacted:length=14]"}
- durationMs: 14

## 2026-08-27 16:39:20.667Z console.error
- text: Fetch error from http://localhost:3000/hcgi/platform/api/collections/users/auth-with-password: 

## 2026-08-27 16:39:20.668Z console.error
- text: [AuthContext] Login failed: {"status":404,"message":"Something went wrong while processing your request.","response":{},"isAbort":false}

## 2026-08-27 16:39:31.703Z focus
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"login-email","placeholder":"jan@ekzanp.com","label":"email","value":"dadyhaiti1985@gmail.com","valueLength":23,"text":""}

## 2026-08-27 16:39:31.801Z click
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"login-email","placeholder":"jan@ekzanp.com","label":"email","value":"dadyhaiti1985@gmail.com","valueLength":23,"text":""}

## 2026-08-27 16:39:32.261Z click
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"login-email","placeholder":"jan@ekzanp.com","label":"email","value":"dadyhaiti1985@gmail.com","valueLength":23,"text":""}

## 2026-08-27 16:39:33.187Z click
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"login-email","placeholder":"jan@ekzanp.com","label":"email","value":"dadyhaiti1985@gmail.com","valueLength":23,"text":""}

## 2026-08-27 16:39:36.631Z click
- element: {"tag":"div","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"RoboKriptoRetounen KonekteAntre pou wè pèfòmans ouImèl (Email)Modpas (Password)Konekte (Login)Oswa kontinye avèkGoogleOu poko gen kont? Enskri isit la"}

## 2026-08-27 16:39:40.706Z change
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"login-email","placeholder":"jan@ekzanp.com","label":"email","value":"","valueLength":0,"text":""}

## 2026-08-27 16:39:46.544Z focus
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"login-email","placeholder":"jan@ekzanp.com","label":"email","value":"","valueLength":0,"text":""}

## 2026-08-27 16:39:46.642Z click
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"login-email","placeholder":"jan@ekzanp.com","label":"email","value":"","valueLength":0,"text":""}

## 2026-08-27 16:39:56.613Z load
- url: http://localhost:3000/

## 2026-08-27 16:39:55.959Z change
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"login-email","placeholder":"jan@ekzanp.com","label":"email","value":"dadyhaiti1985@gmail.com","valueLength":23,"text":""}

## 2026-08-27 16:39:55.959Z blur
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"login-email","placeholder":"jan@ekzanp.com","label":"email","value":"dadyhaiti1985@gmail.com","valueLength":23,"text":""}

## 2026-08-27 16:39:56.937Z navigate
- url: http://localhost:3000/
- via: replaceState

## 2026-08-27 16:39:57.929Z console.warn
- text: [Perf] Low FPS detected: 26

## 2026-08-27 16:39:58.930Z console.warn
- text: [Perf] Low FPS detected: 41

## 2026-08-27 16:39:59.943Z console.warn
- text: [Perf] Low FPS detected: 51

## 2026-08-27 16:40:00.933Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":" KONT PA OU"}

## 2026-08-27 16:40:00.935Z navigate
- url: http://localhost:3000/dashboard/oracle-trader-pro
- via: pushState

## 2026-08-27 16:40:00.949Z console.warn
- text: [Perf] Low FPS detected: 46

## 2026-08-27 16:40:00.969Z navigate
- url: http://localhost:3000/login
- via: replaceState

## 2026-08-27 16:40:02.899Z focus
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"login-email","placeholder":"jan@ekzanp.com","label":"email","value":"","valueLength":0,"text":""}

## 2026-08-27 16:40:03.032Z click
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"login-email","placeholder":"jan@ekzanp.com","label":"email","value":"","valueLength":0,"text":""}

## 2026-08-27 16:40:04.532Z click
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"login-email","placeholder":"jan@ekzanp.com","label":"email","value":"","valueLength":0,"text":""}

## 2026-08-27 16:40:09.454Z change
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"login-email","placeholder":"jan@ekzanp.com","label":"email","value":"dadyhaiti1985@gmail.com","valueLength":23,"text":""}

## 2026-08-27 16:40:10.395Z blur
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"login-email","placeholder":"jan@ekzanp.com","label":"email","value":"dadyhaiti1985@gmail.com","valueLength":23,"text":""}

## 2026-08-27 16:40:10.395Z focus
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=0]","valueLength":0,"text":""}

## 2026-08-27 16:40:10.512Z click
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=0]","valueLength":0,"text":""}

## 2026-08-27 16:40:15.814Z change
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=11]","valueLength":11,"text":""}

## 2026-08-27 16:40:15.815Z click
- element: {"tag":"button","role":null,"ariaLabel":null,"name":null,"type":"submit","id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Konekte (Login)"}

## 2026-08-27 16:40:15.815Z submit
- action: http://localhost:3000/login
- fields: [{"label":"email","type":"email","value":"dadyhaiti1985@gmail.com","length":23,"redacted":false},{"label":"password","type":"password","value":"[redacted:length=11]","length":11,"redacted":true},{"label":"[submit]","type":"submit","value":"","length":0,"redacted":false}]

## 2026-08-27 16:40:15.819Z blur
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=11]","valueLength":11,"text":""}

## 2026-08-27 16:40:15.829Z network.error
- method: POST
- url: http://localhost:3000/hcgi/platform/api/collections/users/auth-with-password
- status: 404
- statusText: Not Found
- requestBody: {"identity":"dadyhaiti1985@gmail.com","password":"[redacted:length=11]"}
- durationMs: 12

## 2026-08-27 16:40:15.829Z console.error
- text: Fetch error from http://localhost:3000/hcgi/platform/api/collections/users/auth-with-password: 

## 2026-08-27 16:40:15.830Z console.error
- text: [AuthContext] Login failed: {"status":404,"message":"Something went wrong while processing your request.","response":{},"isAbort":false}

## 2026-08-27 16:40:22.745Z navigate
- url: http://localhost:3000/
- via: popstate

## 2026-08-27 16:40:22.907Z console.warn
- text: [Perf] Low FPS detected: 53

## 2026-08-27 16:40:23.917Z console.warn
- text: [Perf] Low FPS detected: 51

## 2026-08-27 16:41:14.342Z console.warn
- text: [Perf] Low FPS detected: 49

## 2026-08-27 16:41:15.363Z console.warn
- text: [Perf] Low FPS detected: 44

## 2026-08-27 16:41:17.379Z console.warn
- text: [Perf] Low FPS detected: 52

## 2026-08-27 16:41:18.385Z console.warn
- text: [Perf] Low FPS detected: 45

## 2026-08-27 16:41:19.402Z console.warn
- text: [Perf] Low FPS detected: 50

## 2026-08-27 16:41:20.408Z console.warn
- text: [Perf] Low FPS detected: 49

## 2026-08-27 16:41:21.428Z console.warn
- text: [Perf] Low FPS detected: 50

## 2026-08-27 16:41:41.164Z focus
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=11]","valueLength":11,"text":""}

## 2026-08-27 16:41:42.257Z click
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=11]","valueLength":11,"text":""}

## 2026-08-27 16:41:45.816Z console.warn
- text: [Perf] Low FPS detected: 52

## 2026-08-27 16:41:45.996Z change
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=14]","valueLength":14,"text":""}

## 2026-08-27 16:41:45.996Z blur
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=14]","valueLength":14,"text":""}

## 2026-08-27 16:41:46.130Z click
- element: {"tag":"button","role":null,"ariaLabel":null,"name":null,"type":"submit","id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Konekte (Login)"}

## 2026-08-27 16:41:46.131Z submit
- action: http://localhost:3000/login
- fields: [{"label":"email","type":"email","value":"dadyhaiti1985@gmail.com","length":23,"redacted":false},{"label":"password","type":"password","value":"[redacted:length=14]","length":14,"redacted":true},{"label":"[submit]","type":"submit","value":"","length":0,"redacted":false}]

## 2026-08-27 16:41:46.137Z network.error
- method: POST
- url: http://localhost:3000/hcgi/platform/api/collections/users/auth-with-password
- status: 404
- statusText: Not Found
- requestBody: {"identity":"dadyhaiti1985@gmail.com","password":"[redacted:length=14]"}
- durationMs: 6

## 2026-08-27 16:41:46.137Z console.error
- text: Fetch error from http://localhost:3000/hcgi/platform/api/collections/users/auth-with-password: 

## 2026-08-27 16:41:46.137Z console.error
- text: [AuthContext] Login failed: {"status":404,"message":"Something went wrong while processing your request.","response":{},"isAbort":false}

## 2026-08-27 16:41:52.230Z click
- element: {"tag":"button","role":null,"ariaLabel":null,"name":null,"type":"submit","id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Konekte (Login)"}

## 2026-08-27 16:41:52.231Z submit
- action: http://localhost:3000/login
- fields: [{"label":"email","type":"email","value":"dadyhaiti1985@gmail.com","length":23,"redacted":false},{"label":"password","type":"password","value":"[redacted:length=14]","length":14,"redacted":true},{"label":"[submit]","type":"submit","value":"","length":0,"redacted":false}]

## 2026-08-27 16:41:52.236Z network.error
- method: POST
- url: http://localhost:3000/hcgi/platform/api/collections/users/auth-with-password
- status: 404
- statusText: Not Found
- requestBody: {"identity":"dadyhaiti1985@gmail.com","password":"[redacted:length=14]"}
- durationMs: 5

## 2026-08-27 16:41:52.236Z console.error
- text: Fetch error from http://localhost:3000/hcgi/platform/api/collections/users/auth-with-password: 

## 2026-08-27 16:41:52.237Z console.error
- text: [AuthContext] Login failed: {"status":404,"message":"Something went wrong while processing your request.","response":{},"isAbort":false}

## 2026-08-27 16:41:57.230Z click
- element: {"tag":"button","role":null,"ariaLabel":null,"name":null,"type":"submit","id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Konekte (Login)"}

## 2026-08-27 16:41:57.231Z submit
- action: http://localhost:3000/login
- fields: [{"label":"email","type":"email","value":"dadyhaiti1985@gmail.com","length":23,"redacted":false},{"label":"password","type":"password","value":"[redacted:length=14]","length":14,"redacted":true},{"label":"[submit]","type":"submit","value":"","length":0,"redacted":false}]

## 2026-08-27 16:41:57.237Z network.error
- method: POST
- url: http://localhost:3000/hcgi/platform/api/collections/users/auth-with-password
- status: 404
- statusText: Not Found
- requestBody: {"identity":"dadyhaiti1985@gmail.com","password":"[redacted:length=14]"}
- durationMs: 6

## 2026-08-27 16:41:57.237Z console.error
- text: Fetch error from http://localhost:3000/hcgi/platform/api/collections/users/auth-with-password: 

## 2026-08-27 16:41:57.238Z console.error
- text: [AuthContext] Login failed: {"status":404,"message":"Something went wrong while processing your request.","response":{},"isAbort":false}

## 2026-08-27 16:43:03.422Z console.warn
- text: [Perf] Low FPS detected: 53

## 2026-08-27 16:43:06.526Z console.warn
- text: [Perf] Low FPS detected: 47

## 2026-08-27 16:43:09.540Z console.warn
- text: [Perf] Low FPS detected: 49

## 2026-08-27 16:43:12.554Z console.warn
- text: [Perf] Low FPS detected: 47

## 2026-08-27 16:43:15.586Z console.warn
- text: [Perf] Low FPS detected: 43

## 2026-08-27 16:43:18.616Z console.warn
- text: [Perf] Low FPS detected: 44

## 2026-08-27 16:43:20.651Z console.warn
- text: [Perf] Low FPS detected: 54

## 2026-08-27 16:43:21.656Z console.warn
- text: [Perf] Low FPS detected: 45

## 2026-08-27 16:43:23.685Z console.warn
- text: [Perf] Low FPS detected: 54

## 2026-08-27 16:43:24.686Z console.warn
- text: [Perf] Low FPS detected: 45

## 2026-08-27 16:43:26.786Z console.warn
- text: [Perf] Low FPS detected: 52

## 2026-08-27 16:43:27.786Z console.warn
- text: [Perf] Low FPS detected: 44

## 2026-08-27 16:43:29.827Z console.warn
- text: [Perf] Low FPS detected: 53

## 2026-08-27 16:43:30.862Z console.warn
- text: [Perf] Low FPS detected: 44

## 2026-08-27 16:43:32.663Z console.warn
- text: [Perf] Low FPS detected: 1

## 2026-08-27 16:43:33.899Z console.warn
- text: [Perf] Low FPS detected: 52

## 2026-08-27 16:43:35.887Z click
- element: {"tag":"button","role":null,"ariaLabel":null,"name":null,"type":"submit","id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Konekte (Login)"}

## 2026-08-27 16:43:35.888Z submit
- action: http://localhost:3000/login
- fields: [{"label":"email","type":"email","value":"dadyhaiti1985@gmail.com","length":23,"redacted":false},{"label":"password","type":"password","value":"[redacted:length=14]","length":14,"redacted":true},{"label":"[submit]","type":"submit","value":"","length":0,"redacted":false}]

## 2026-08-27 16:43:36.551Z network.error
- method: POST
- url: http://localhost:3000/hcgi/platform/api/collections/users/auth-with-password
- status: 404
- statusText: Not Found
- requestBody: {"identity":"dadyhaiti1985@gmail.com","password":"[redacted:length=14]"}
- durationMs: 663

## 2026-08-27 16:43:36.551Z console.error
- text: Fetch error from http://localhost:3000/hcgi/platform/api/collections/users/auth-with-password: 

## 2026-08-27 16:43:36.552Z console.error
- text: [AuthContext] Login failed: {"status":404,"message":"Something went wrong while processing your request.","response":{},"isAbort":false}

## 2026-08-27 16:43:36.917Z console.warn
- text: [Perf] Low FPS detected: 53

## 2026-08-27 16:43:40.963Z console.warn
- text: [Perf] Low FPS detected: 22

## 2026-08-27 16:43:42.966Z console.warn
- text: [Perf] Low FPS detected: 53

## 2026-08-27 16:43:57.051Z console.warn
- text: [Perf] Low FPS detected: 49

## 2026-08-27 16:44:51.706Z console.warn
- text: [Perf] Low FPS detected: 2

## 2026-08-27 16:44:57.089Z console.warn
- text: [Perf] Low FPS detected: 28

## 2026-08-27 16:45:27.385Z console.warn
- text: [Perf] Low FPS detected: 54

## 2026-08-27 16:45:30.418Z console.warn
- text: [Perf] Low FPS detected: 47

## 2026-08-27 16:45:30.833Z console.warn
- text: [Perf] Low FPS detected: 1

## 2026-08-27 16:45:31.843Z console.warn
- text: [Perf] Low FPS detected: 53

## 2026-08-27 16:45:33.443Z console.warn
- text: [Perf] Low FPS detected: 51

## 2026-08-27 16:45:36.459Z console.warn
- text: [Perf] Low FPS detected: 52

## 2026-08-27 16:45:39.488Z console.warn
- text: [Perf] Low FPS detected: 47

## 2026-08-27 16:45:42.510Z console.warn
- text: [Perf] Low FPS detected: 49

## 2026-08-27 16:45:45.535Z console.warn
- text: [Perf] Low FPS detected: 51

## 2026-08-27 16:45:48.554Z console.warn
- text: [Perf] Low FPS detected: 50

## 2026-08-27 16:45:51.566Z console.warn
- text: [Perf] Low FPS detected: 50

## 2026-08-27 16:45:54.583Z console.warn
- text: [Perf] Low FPS detected: 54

## 2026-08-27 16:45:57.616Z console.warn
- text: [Perf] Low FPS detected: 54

## 2026-08-27 16:46:11.752Z console.warn
- text: [Perf] Low FPS detected: 47

## 2026-08-27 16:46:27.900Z console.warn
- text: [Perf] Low FPS detected: 53

## 2026-08-27 16:46:30.917Z console.warn
- text: [Perf] Low FPS detected: 54

## 2026-08-27 16:46:36.983Z console.warn
- text: [Perf] Low FPS detected: 54

## 2026-08-27 16:46:43.033Z console.warn
- text: [Perf] Low FPS detected: 54

## 2026-08-27 16:47:03.200Z console.warn
- text: [Perf] Low FPS detected: 49

## 2026-08-27 16:48:25.000Z console.warn
- text: [Perf] Low FPS detected: 54

## 2026-08-27 16:48:28.016Z console.warn
- text: [Perf] Low FPS detected: 53

## 2026-08-27 16:48:51.236Z console.warn
- text: [Perf] Low FPS detected: 51

## 2026-08-27 16:49:00.363Z console.warn
- text: [Perf] Low FPS detected: 52

## 2026-08-27 16:49:03.378Z console.warn
- text: [Perf] Low FPS detected: 54

## 2026-08-27 16:50:07.000Z console.warn
- text: [Perf] Low FPS detected: 54

## 2026-08-27 16:50:10.016Z console.warn
- text: [Perf] Low FPS detected: 48

## 2026-08-27 16:50:13.033Z console.warn
- text: [Perf] Low FPS detected: 49

## 2026-08-27 16:50:16.050Z console.warn
- text: [Perf] Low FPS detected: 51

## 2026-08-27 16:50:19.067Z console.warn
- text: [Perf] Low FPS detected: 49

## 2026-08-27 16:50:21.104Z console.warn
- text: [Perf] Low FPS detected: 49

## 2026-08-27 16:50:22.117Z console.warn
- text: [Perf] Low FPS detected: 51

## 2026-08-27 16:50:24.146Z console.warn
- text: [Perf] Low FPS detected: 49

## 2026-08-27 16:50:25.149Z console.warn
- text: [Perf] Low FPS detected: 52

## 2026-08-27 16:50:27.158Z console.warn
- text: [Perf] Low FPS detected: 49

## 2026-08-27 16:50:28.166Z console.warn
- text: [Perf] Low FPS detected: 51

## 2026-08-27 16:50:30.188Z console.warn
- text: [Perf] Low FPS detected: 49

## 2026-08-27 16:50:31.200Z console.warn
- text: [Perf] Low FPS detected: 50

## 2026-08-27 16:50:33.209Z console.warn
- text: [Perf] Low FPS detected: 46

## 2026-08-27 16:50:36.252Z console.warn
- text: [Perf] Low FPS detected: 49

## 2026-08-27 16:50:45.111Z console.warn
- text: [Perf] Low FPS detected: 1

## 2026-08-27 16:51:20.475Z console.warn
- text: [Perf] Low FPS detected: 52

## 2026-08-27 16:53:16.754Z console.warn
- text: [Perf] Low FPS detected: 27

## 2026-08-27 16:54:35.491Z console.warn
- text: [Perf] Low FPS detected: 54

## 2026-08-27 16:58:21.369Z console.warn
- text: [Perf] Low FPS detected: 54

## 2026-08-27 16:58:32.111Z load
- url: http://localhost:3000/

## 2026-08-27 16:58:35.294Z load
- url: http://localhost:3000/login

## 2026-08-27 16:58:36.950Z console.warn
- text: [Perf] Low FPS detected: 29

## 2026-08-27 16:58:37.951Z console.warn
- text: [Perf] Low FPS detected: 38

## 2026-08-27 16:58:38.967Z console.warn
- text: [Perf] Low FPS detected: 42

## 2026-08-27 16:58:39.972Z console.warn
- text: [Perf] Low FPS detected: 54

## 2026-08-27 16:58:40.974Z console.warn
- text: [Perf] Low FPS detected: 33

## 2026-08-27 16:58:41.990Z console.warn
- text: [Perf] Low FPS detected: 54

## 2026-08-27 16:58:43.003Z console.warn
- text: [Perf] Low FPS detected: 52

## 2026-08-27 16:58:44.011Z console.warn
- text: [Perf] Low FPS detected: 33

## 2026-08-27 16:58:45.343Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":" KONT PA OU"}

## 2026-08-27 16:58:45.347Z navigate
- url: http://localhost:3000/dashboard/oracle-trader-pro
- via: pushState

## 2026-08-27 16:58:45.376Z navigate
- url: http://localhost:3000/login
- via: replaceState

## 2026-08-27 16:58:47.009Z focus
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"login-email","placeholder":"jan@ekzanp.com","label":"email","value":"","valueLength":0,"text":""}

## 2026-08-27 16:58:47.126Z click
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"login-email","placeholder":"jan@ekzanp.com","label":"email","value":"","valueLength":0,"text":""}

## 2026-08-27 16:58:48.719Z click
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"login-email","placeholder":"jan@ekzanp.com","label":"email","value":"","valueLength":0,"text":""}

## 2026-08-27 16:58:57.755Z focus
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"login-email","placeholder":"jan@ekzanp.com","label":"email","value":"","valueLength":0,"text":""}

## 2026-08-27 16:58:57.877Z click
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"login-email","placeholder":"jan@ekzanp.com","label":"email","value":"","valueLength":0,"text":""}

## 2026-08-27 16:59:00.930Z change
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"login-email","placeholder":"jan@ekzanp.com","label":"email","value":"dadyhaiti1985@gmail.com","valueLength":23,"text":""}

## 2026-08-27 16:59:00.930Z blur
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"login-email","placeholder":"jan@ekzanp.com","label":"email","value":"dadyhaiti1985@gmail.com","valueLength":23,"text":""}

## 2026-08-27 16:59:00.931Z focus
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=0]","valueLength":0,"text":""}

## 2026-08-27 16:59:01.028Z click
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=0]","valueLength":0,"text":""}

## 2026-08-27 16:59:06.479Z change
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=14]","valueLength":14,"text":""}

## 2026-08-27 16:59:06.479Z click
- element: {"tag":"button","role":null,"ariaLabel":null,"name":null,"type":"submit","id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Konekte (Login)"}

## 2026-08-27 16:59:06.479Z submit
- action: http://localhost:3000/login
- fields: [{"label":"email","type":"email","value":"dadyhaiti1985@gmail.com","length":23,"redacted":false},{"label":"password","type":"password","value":"[redacted:length=14]","length":14,"redacted":true},{"label":"[submit]","type":"submit","value":"","length":0,"redacted":false}]

## 2026-08-27 16:59:06.485Z blur
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=14]","valueLength":14,"text":""}

## 2026-08-27 16:59:06.522Z network.error
- method: POST
- url: http://localhost:3000/hcgi/platform/api/collections/users/auth-with-password
- status: 400
- statusText: Bad Request
- requestBody: {"identity":"dadyhaiti1985@gmail.com","password":"[redacted:length=14]"}
- response: 
    {"data":{},"message":"Failed to authenticate.","status":400}
    
- durationMs: 40

## 2026-08-27 16:59:06.523Z console.error
- text: [AuthContext] Login failed: {"status":400,"message":"Failed to authenticate.","response":{"data":{},"message":"Failed to authenticate.","status":400},"isAbort":false}

## 2026-08-27 16:59:06.516Z pocketbase.error
- message: POST /api/collections/users/auth-with-password
- data: {"auth":"","details":"invalid login credentials","error":"Failed to authenticate.","execTime":10.615674,"method":"POST","referer":"http://localhost:3000/login","remoteIP":"127.0.0.1","status":400,"type":"request","url":"/api/collections/users/auth-with-password","userAgent":"Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Code/1.133.0 Chrome/148.0.7778.280 Electron/42.8.0 Safari/537.36","userIP":"127.0.0.1"}

## 2026-08-27 17:01:52.227Z pocketbase.error
- message: POST /api/collections/users/records
- data: {"auth":"","details":"TypeError: Object has no member 'dao' at /Users/macbook/Desktop/app/apps/pocketbase/pb.js:12:11(50)","error":"Failed to create record.","execTime":133.43736,"method":"POST","referer":"","remoteIP":"127.0.0.1","status":400,"type":"request","url":"/api/collections/users/records","userAgent":"curl/8.7.1","userIP":"127.0.0.1"}

## 2026-08-27 17:02:02.482Z pocketbase.error
- message: GET /api/collections/users
- data: {"auth":"_superusers","details":null,"error":"Not allowed to view collection.","execTime":1.882214,"method":"GET","referer":"","remoteIP":"127.0.0.1","status":400,"type":"request","url":"/api/collections/users","userAgent":"curl/8.7.1","userIP":"127.0.0.1"}

## 2026-08-27 17:02:34.540Z console.warn
- text: [Perf] Low FPS detected: 2

## 2026-08-27 17:02:38.400Z pocketbase.error
- message: POST /api/collections/users/records
- data: {"auth":"","details":{"data":{"email":"Value must be unique"},"raw":"email: Value must be unique."},"error":"Failed to create record.","execTime":128.498975,"method":"POST","referer":"","remoteIP":"127.0.0.1","status":400,"type":"request","url":"/api/collections/users/records","userAgent":"curl/8.7.1","userIP":"127.0.0.1"}

## 2026-08-27 17:04:27.643Z console.warn
- text: [Perf] Low FPS detected: 16

## 2026-08-27 17:05:29.713Z focus
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"login-email","placeholder":"jan@ekzanp.com","label":"email","value":"","valueLength":0,"text":""}

## 2026-08-27 17:05:29.828Z click
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"login-email","placeholder":"jan@ekzanp.com","label":"email","value":"","valueLength":0,"text":""}

## 2026-08-27 17:05:33.734Z click
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"login-email","placeholder":"jan@ekzanp.com","label":"email","value":"","valueLength":0,"text":""}

## 2026-08-27 17:05:50.433Z change
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"login-email","placeholder":"jan@ekzanp.com","label":"email","value":"dadyhaiti1985@gmail.com","valueLength":23,"text":""}

## 2026-08-27 17:05:50.433Z blur
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"login-email","placeholder":"jan@ekzanp.com","label":"email","value":"dadyhaiti1985@gmail.com","valueLength":23,"text":""}

## 2026-08-27 17:05:50.433Z focus
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=0]","valueLength":0,"text":""}

## 2026-08-27 17:05:50.582Z click
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=0]","valueLength":0,"text":""}

## 2026-08-27 17:05:56.897Z change
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=14]","valueLength":14,"text":""}

## 2026-08-27 17:05:56.897Z click
- element: {"tag":"button","role":null,"ariaLabel":null,"name":null,"type":"submit","id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Konekte (Login)"}

## 2026-08-27 17:05:56.897Z submit
- action: http://localhost:3000/login
- fields: [{"label":"email","type":"email","value":"dadyhaiti1985@gmail.com","length":23,"redacted":false},{"label":"password","type":"password","value":"[redacted:length=14]","length":14,"redacted":true},{"label":"[submit]","type":"submit","value":"","length":0,"redacted":false}]

## 2026-08-27 17:05:56.900Z blur
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=14]","valueLength":14,"text":""}

## 2026-08-27 17:05:56.967Z network.error
- method: POST
- url: http://localhost:3000/hcgi/platform/api/collections/users/auth-with-password
- status: 400
- statusText: Bad Request
- requestBody: {"identity":"dadyhaiti1985@gmail.com","password":"[redacted:length=14]"}
- response: 
    {"data":{},"message":"Failed to authenticate.","status":400}
    
- durationMs: 69

## 2026-08-27 17:05:56.967Z console.error
- text: [AuthContext] Login failed: {"status":400,"message":"Failed to authenticate.","response":{"data":{},"message":"Failed to authenticate.","status":400},"isAbort":false}

## 2026-08-27 17:05:59.527Z click
- element: {"tag":"button","role":null,"ariaLabel":null,"name":null,"type":"submit","id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Konekte (Login)"}

## 2026-08-27 17:05:59.527Z submit
- action: http://localhost:3000/login
- fields: [{"label":"email","type":"email","value":"dadyhaiti1985@gmail.com","length":23,"redacted":false},{"label":"password","type":"password","value":"[redacted:length=14]","length":14,"redacted":true},{"label":"[submit]","type":"submit","value":"","length":0,"redacted":false}]

## 2026-08-27 17:05:59.593Z network.error
- method: POST
- url: http://localhost:3000/hcgi/platform/api/collections/users/auth-with-password
- status: 400
- statusText: Bad Request
- requestBody: {"identity":"dadyhaiti1985@gmail.com","password":"[redacted:length=14]"}
- response: 
    {"data":{},"message":"Failed to authenticate.","status":400}
    
- durationMs: 66

## 2026-08-27 17:05:59.593Z console.error
- text: [AuthContext] Login failed: {"status":400,"message":"Failed to authenticate.","response":{"data":{},"message":"Failed to authenticate.","status":400},"isAbort":false}

## 2026-08-27 17:05:56.965Z pocketbase.error
- message: POST /api/collections/users/auth-with-password
- data: {"auth":"","details":"invalid login credentials","error":"Failed to authenticate.","execTime":61.430948,"method":"POST","referer":"http://localhost:3000/login","remoteIP":"127.0.0.1","status":400,"type":"request","url":"/api/collections/users/auth-with-password","userAgent":"Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Code/1.133.0 Chrome/148.0.7778.280 Electron/42.8.0 Safari/537.36","userIP":"127.0.0.1"}

## 2026-08-27 17:05:59.591Z pocketbase.error
- message: POST /api/collections/users/auth-with-password
- data: {"auth":"","details":"invalid login credentials","error":"Failed to authenticate.","execTime":60.842107,"method":"POST","referer":"http://localhost:3000/login","remoteIP":"127.0.0.1","status":400,"type":"request","url":"/api/collections/users/auth-with-password","userAgent":"Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Code/1.133.0 Chrome/148.0.7778.280 Electron/42.8.0 Safari/537.36","userIP":"127.0.0.1"}

## 2026-08-27 17:06:20.810Z focus
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"login-email","placeholder":"jan@ekzanp.com","label":"email","value":"dadyhaiti1985@gmail.com","valueLength":23,"text":""}

## 2026-08-27 17:06:20.897Z click
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"login-email","placeholder":"jan@ekzanp.com","label":"email","value":"dadyhaiti1985@gmail.com","valueLength":23,"text":""}

## 2026-08-27 17:06:22.093Z click
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"login-email","placeholder":"jan@ekzanp.com","label":"email","value":"dadyhaiti1985@gmail.com","valueLength":23,"text":""}

## 2026-08-27 17:06:25.155Z blur
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"login-email","placeholder":"jan@ekzanp.com","label":"email","value":"dadyhaiti1985@gmail.com","valueLength":23,"text":""}

## 2026-08-27 17:06:25.156Z focus
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=14]","valueLength":14,"text":""}

## 2026-08-27 17:06:25.307Z click
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=14]","valueLength":14,"text":""}

## 2026-08-27 17:06:29.006Z blur
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=14]","valueLength":14,"text":""}

## 2026-08-27 17:06:33.375Z focus
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=14]","valueLength":14,"text":""}

## 2026-08-27 17:06:33.479Z click
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=14]","valueLength":14,"text":""}

## 2026-08-27 17:06:34.405Z click
- element: {"tag":"div","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"RoboKriptoRetounen KonekteAntre pou wè pèfòmans ouImèl (Email)Modpas (Password)Konekte (Login)Oswa kontinye avèkGoogleOu poko gen kont? Enskri isit la"}

## 2026-08-27 17:06:38.822Z click
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=12557]","valueLength":12557,"text":""}

## 2026-08-27 17:06:41.887Z change
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=0]","valueLength":0,"text":""}

## 2026-08-27 17:06:48.614Z focus
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=0]","valueLength":0,"text":""}

## 2026-08-27 17:06:48.710Z click
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=0]","valueLength":0,"text":""}

## 2026-08-27 17:06:51.732Z change
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=14]","valueLength":14,"text":""}

## 2026-08-27 17:06:51.732Z blur
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=14]","valueLength":14,"text":""}

## 2026-08-27 17:06:51.858Z click
- element: {"tag":"button","role":null,"ariaLabel":null,"name":null,"type":"submit","id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Konekte (Login)"}

## 2026-08-27 17:06:51.858Z submit
- action: http://localhost:3000/login
- fields: [{"label":"email","type":"email","value":"dadyhaiti1985@gmail.com","length":23,"redacted":false},{"label":"password","type":"password","value":"[redacted:length=14]","length":14,"redacted":true},{"label":"[submit]","type":"submit","value":"","length":0,"redacted":false}]

## 2026-08-27 17:06:51.928Z network.error
- method: POST
- url: http://localhost:3000/hcgi/platform/api/collections/users/auth-with-password
- status: 400
- statusText: Bad Request
- requestBody: {"identity":"dadyhaiti1985@gmail.com","password":"[redacted:length=14]"}
- response: 
    {"data":{},"message":"Failed to authenticate.","status":400}
    
- durationMs: 67

## 2026-08-27 17:06:51.928Z console.error
- text: [AuthContext] Login failed: {"status":400,"message":"Failed to authenticate.","response":{"data":{},"message":"Failed to authenticate.","status":400},"isAbort":false}

## 2026-08-27 17:06:54.706Z click
- element: {"tag":"button","role":null,"ariaLabel":null,"name":null,"type":"submit","id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Konekte (Login)"}

## 2026-08-27 17:06:54.706Z submit
- action: http://localhost:3000/login
- fields: [{"label":"email","type":"email","value":"dadyhaiti1985@gmail.com","length":23,"redacted":false},{"label":"password","type":"password","value":"[redacted:length=14]","length":14,"redacted":true},{"label":"[submit]","type":"submit","value":"","length":0,"redacted":false}]

## 2026-08-27 17:06:54.778Z network.error
- method: POST
- url: http://localhost:3000/hcgi/platform/api/collections/users/auth-with-password
- status: 400
- statusText: Bad Request
- requestBody: {"identity":"dadyhaiti1985@gmail.com","password":"[redacted:length=14]"}
- response: 
    {"data":{},"message":"Failed to authenticate.","status":400}
    
- durationMs: 71

## 2026-08-27 17:06:54.778Z console.error
- text: [AuthContext] Login failed: {"status":400,"message":"Failed to authenticate.","response":{"data":{},"message":"Failed to authenticate.","status":400},"isAbort":false}

## 2026-08-27 17:06:51.927Z pocketbase.error
- message: POST /api/collections/users/auth-with-password
- data: {"auth":"","details":"invalid login credentials","error":"Failed to authenticate.","execTime":61.47798,"method":"POST","referer":"http://localhost:3000/login","remoteIP":"127.0.0.1","status":400,"type":"request","url":"/api/collections/users/auth-with-password","userAgent":"Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Code/1.133.0 Chrome/148.0.7778.280 Electron/42.8.0 Safari/537.36","userIP":"127.0.0.1"}

## 2026-08-27 17:06:54.775Z pocketbase.error
- message: POST /api/collections/users/auth-with-password
- data: {"auth":"","details":"invalid login credentials","error":"Failed to authenticate.","execTime":63.398378,"method":"POST","referer":"http://localhost:3000/login","remoteIP":"127.0.0.1","status":400,"type":"request","url":"/api/collections/users/auth-with-password","userAgent":"Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Code/1.133.0 Chrome/148.0.7778.280 Electron/42.8.0 Safari/537.36","userIP":"127.0.0.1"}

## 2026-08-27 17:07:18.340Z click
- element: {"tag":"div","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"RoboKriptoRetounen KonekteAntre pou wè pèfòmans ouImèl (Email)Modpas (Password)Konekte (Login)Oswa kontinye avèkGoogleOu poko gen kont? Enskri isit la"}

## 2026-08-27 17:07:19.856Z focus
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=0]","valueLength":0,"text":""}

## 2026-08-27 17:07:19.933Z click
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=0]","valueLength":0,"text":""}

## 2026-08-27 17:07:24.031Z click
- element: {"tag":"div","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"RoboKriptoRetounen KonekteAntre pou wè pèfòmans ouImèl (Email)Modpas (Password)Konekte (Login)Oswa kontinye avèkGoogleOu poko gen kont? Enskri isit la"}

## 2026-08-27 17:07:34.108Z focus
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=0]","valueLength":0,"text":""}

## 2026-08-27 17:07:34.124Z focus
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"login-email","placeholder":"jan@ekzanp.com","label":"email","value":"","valueLength":0,"text":""}

## 2026-08-27 17:07:34.236Z click
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"login-email","placeholder":"jan@ekzanp.com","label":"email","value":"","valueLength":0,"text":""}

## 2026-08-27 17:07:37.784Z change
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"login-email","placeholder":"jan@ekzanp.com","label":"email","value":"dadyhaiti1985@gmail.com","valueLength":23,"text":""}

## 2026-08-27 17:07:37.784Z blur
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"login-email","placeholder":"jan@ekzanp.com","label":"email","value":"dadyhaiti1985@gmail.com","valueLength":23,"text":""}

## 2026-08-27 17:07:37.784Z focus
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=0]","valueLength":0,"text":""}

## 2026-08-27 17:07:37.887Z click
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=0]","valueLength":0,"text":""}

## 2026-08-27 17:07:45.872Z focus
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=0]","valueLength":0,"text":""}

## 2026-08-27 17:07:45.979Z click
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=0]","valueLength":0,"text":""}

## 2026-08-27 17:07:49.240Z change
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=14]","valueLength":14,"text":""}

## 2026-08-27 17:07:49.240Z blur
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=14]","valueLength":14,"text":""}

## 2026-08-27 17:07:49.383Z click
- element: {"tag":"button","role":null,"ariaLabel":null,"name":null,"type":"submit","id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Konekte (Login)"}

## 2026-08-27 17:07:49.384Z submit
- action: http://localhost:3000/login
- fields: [{"label":"email","type":"email","value":"dadyhaiti1985@gmail.com","length":23,"redacted":false},{"label":"password","type":"password","value":"[redacted:length=14]","length":14,"redacted":true},{"label":"[submit]","type":"submit","value":"","length":0,"redacted":false}]

## 2026-08-27 17:07:49.453Z network.error
- method: POST
- url: http://localhost:3000/hcgi/platform/api/collections/users/auth-with-password
- status: 400
- statusText: Bad Request
- requestBody: {"identity":"dadyhaiti1985@gmail.com","password":"[redacted:length=14]"}
- response: 
    {"data":{},"message":"Failed to authenticate.","status":400}
    
- durationMs: 66

## 2026-08-27 17:07:49.454Z console.error
- text: [AuthContext] Login failed: {"status":400,"message":"Failed to authenticate.","response":{"data":{},"message":"Failed to authenticate.","status":400},"isAbort":false}

## 2026-08-27 17:07:50.858Z click
- element: {"tag":"button","role":null,"ariaLabel":null,"name":null,"type":"submit","id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Konekte (Login)"}

## 2026-08-27 17:07:50.858Z submit
- action: http://localhost:3000/login
- fields: [{"label":"email","type":"email","value":"dadyhaiti1985@gmail.com","length":23,"redacted":false},{"label":"password","type":"password","value":"[redacted:length=14]","length":14,"redacted":true},{"label":"[submit]","type":"submit","value":"","length":0,"redacted":false}]

## 2026-08-27 17:07:50.923Z network.error
- method: POST
- url: http://localhost:3000/hcgi/platform/api/collections/users/auth-with-password
- status: 400
- statusText: Bad Request
- requestBody: {"identity":"dadyhaiti1985@gmail.com","password":"[redacted:length=14]"}
- response: 
    {"data":{},"message":"Failed to authenticate.","status":400}
    
- durationMs: 64

## 2026-08-27 17:07:50.923Z console.error
- text: [AuthContext] Login failed: {"status":400,"message":"Failed to authenticate.","response":{"data":{},"message":"Failed to authenticate.","status":400},"isAbort":false}

## 2026-08-27 17:07:49.452Z pocketbase.error
- message: POST /api/collections/users/auth-with-password
- data: {"auth":"","details":"invalid login credentials","error":"Failed to authenticate.","execTime":60.807102,"method":"POST","referer":"http://localhost:3000/login","remoteIP":"127.0.0.1","status":400,"type":"request","url":"/api/collections/users/auth-with-password","userAgent":"Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/151.0.0.0 Safari/537.36","userIP":"127.0.0.1"}

## 2026-08-27 17:07:50.922Z pocketbase.error
- message: POST /api/collections/users/auth-with-password
- data: {"auth":"","details":"invalid login credentials","error":"Failed to authenticate.","execTime":60.000394,"method":"POST","referer":"http://localhost:3000/login","remoteIP":"127.0.0.1","status":400,"type":"request","url":"/api/collections/users/auth-with-password","userAgent":"Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/151.0.0.0 Safari/537.36","userIP":"127.0.0.1"}

## 2026-08-27 17:07:55.260Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Enskri isit la"}

## 2026-08-27 17:07:55.262Z navigate
- url: http://localhost:3000/signup
- via: pushState

## 2026-08-27 17:08:01.590Z click
- element: {"tag":"button","role":null,"ariaLabel":null,"name":null,"type":"submit","id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Enskri (Sign up)"}

## 2026-08-27 17:08:01.590Z submit
- action: http://localhost:3000/signup
- fields: [{"label":"email","type":"email","value":"","length":0,"redacted":false},{"label":"password","type":"password","value":"[redacted:length=0]","length":0,"redacted":true},{"label":"passwordConfirm","type":"password","value":"[redacted:length=0]","length":0,"redacted":true},{"label":"[submit]","type":"submit","value":"","length":0,"redacted":false}]

## 2026-08-27 17:08:03.194Z focus
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"signup-email","placeholder":"jan@ekzanp.com","label":"email","value":"","valueLength":0,"text":""}

## 2026-08-27 17:08:03.296Z click
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"signup-email","placeholder":"jan@ekzanp.com","label":"email","value":"","valueLength":0,"text":""}

## 2026-08-27 17:08:04.321Z change
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"signup-email","placeholder":"jan@ekzanp.com","label":"email","value":"meahunlimitedgroupe@gmail.com","valueLength":29,"text":""}

## 2026-08-27 17:08:05.004Z blur
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"signup-email","placeholder":"jan@ekzanp.com","label":"email","value":"meahunlimitedgroupe@gmail.com","valueLength":29,"text":""}

## 2026-08-27 17:08:05.005Z focus
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"signup-password","placeholder":"••••••••","label":"password","value":"[redacted:length=0]","valueLength":0,"text":""}

## 2026-08-27 17:08:05.106Z click
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"signup-password","placeholder":"••••••••","label":"password","value":"[redacted:length=0]","valueLength":0,"text":""}

## 2026-08-27 17:08:06.288Z click
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"signup-password","placeholder":"••••••••","label":"password","value":"[redacted:length=0]","valueLength":0,"text":""}

## 2026-08-27 17:08:07.562Z focus
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"signup-email","placeholder":"jan@ekzanp.com","label":"email","value":"meahunlimitedgroupe@gmail.com","valueLength":29,"text":""}

## 2026-08-27 17:08:07.563Z change
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"signup-email","placeholder":"jan@ekzanp.com","label":"email","value":"dadyhaiti1985@gmail.com","valueLength":23,"text":""}

## 2026-08-27 17:08:07.563Z blur
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"signup-email","placeholder":"jan@ekzanp.com","label":"email","value":"dadyhaiti1985@gmail.com","valueLength":23,"text":""}

## 2026-08-27 17:08:07.565Z change
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"signup-password","placeholder":"••••••••","label":"password","value":"[redacted:length=14]","valueLength":14,"text":""}

## 2026-08-27 17:08:08.560Z blur
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"signup-password","placeholder":"••••••••","label":"password","value":"[redacted:length=14]","valueLength":14,"text":""}

## 2026-08-27 17:08:08.704Z click
- element: {"tag":"button","role":null,"ariaLabel":null,"name":null,"type":"submit","id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Enskri (Sign up)"}

## 2026-08-27 17:08:08.705Z submit
- action: http://localhost:3000/signup
- fields: [{"label":"email","type":"email","value":"dadyhaiti1985@gmail.com","length":23,"redacted":false},{"label":"password","type":"password","value":"[redacted:length=14]","length":14,"redacted":true},{"label":"passwordConfirm","type":"password","value":"[redacted:length=0]","length":0,"redacted":true},{"label":"[submit]","type":"submit","value":"","length":0,"redacted":false}]

## 2026-08-27 17:08:13.105Z focus
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"passwordConfirm","type":"password","id":"signup-passwordConfirm","placeholder":"••••••••","label":"passwordConfirm","value":"[redacted:length=0]","valueLength":0,"text":""}

## 2026-08-27 17:08:13.240Z click
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"passwordConfirm","type":"password","id":"signup-passwordConfirm","placeholder":"••••••••","label":"passwordConfirm","value":"[redacted:length=0]","valueLength":0,"text":""}

## 2026-08-27 17:08:16.588Z change
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"passwordConfirm","type":"password","id":"signup-passwordConfirm","placeholder":"••••••••","label":"passwordConfirm","value":"[redacted:length=14]","valueLength":14,"text":""}

## 2026-08-27 17:08:16.588Z blur
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"passwordConfirm","type":"password","id":"signup-passwordConfirm","placeholder":"••••••••","label":"passwordConfirm","value":"[redacted:length=14]","valueLength":14,"text":""}

## 2026-08-27 17:08:16.740Z click
- element: {"tag":"button","role":null,"ariaLabel":null,"name":null,"type":"submit","id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Enskri (Sign up)"}

## 2026-08-27 17:08:16.741Z submit
- action: http://localhost:3000/signup
- fields: [{"label":"email","type":"email","value":"dadyhaiti1985@gmail.com","length":23,"redacted":false},{"label":"password","type":"password","value":"[redacted:length=14]","length":14,"redacted":true},{"label":"passwordConfirm","type":"password","value":"[redacted:length=14]","length":14,"redacted":true},{"label":"[submit]","type":"submit","value":"","length":0,"redacted":false}]

## 2026-08-27 17:08:16.867Z network.error
- method: POST
- url: http://localhost:3000/hcgi/platform/api/collections/users/records
- status: 400
- statusText: Bad Request
- requestBody: {"email":"dadyhaiti1985@gmail.com","password":"[redacted:length=14]","passwordConfirm":"[redacted:length=14]","emailVisibility":"true"}
- response: 
    {"data":{},"message":"Failed to create record.","status":400}
    
- durationMs: 126

## 2026-08-27 17:08:16.867Z console.error
- text: 
    Fetch error from http://localhost:3000/hcgi/platform/api/collections/users/records: {"data":{},"message":"Failed to create record.","status":400}
    

## 2026-08-27 17:08:16.868Z console.error
- text: [Signup] Full error: {"data":{},"message":"Failed to create record.","status":400}

## 2026-08-27 17:08:19.236Z click
- element: {"tag":"button","role":null,"ariaLabel":null,"name":null,"type":"submit","id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Enskri (Sign up)"}

## 2026-08-27 17:08:19.237Z submit
- action: http://localhost:3000/signup
- fields: [{"label":"email","type":"email","value":"dadyhaiti1985@gmail.com","length":23,"redacted":false},{"label":"password","type":"password","value":"[redacted:length=14]","length":14,"redacted":true},{"label":"passwordConfirm","type":"password","value":"[redacted:length=14]","length":14,"redacted":true},{"label":"[submit]","type":"submit","value":"","length":0,"redacted":false}]

## 2026-08-27 17:08:19.362Z network.error
- method: POST
- url: http://localhost:3000/hcgi/platform/api/collections/users/records
- status: 400
- statusText: Bad Request
- requestBody: {"email":"dadyhaiti1985@gmail.com","password":"[redacted:length=14]","passwordConfirm":"[redacted:length=14]","emailVisibility":"true"}
- response: 
    {"data":{"email":{"code":"validation_not_unique","message":"Value must be unique."}},"message":"Failed to create record.","status":400}
    
- durationMs: 125

## 2026-08-27 17:08:19.362Z console.warn
- text: 
    Fetch error from http://localhost:3000/hcgi/platform/api/collections/users/records: {"data":{"email":{"code":"validation_not_unique","message":"Value must be unique."}},"message":"Failed to create record.","status":400}
    

## 2026-08-27 17:08:19.362Z console.error
- text: [Signup] Full error: {"data":{"email":{"code":"validation_not_unique","message":"Value must be unique."}},"message":"Failed to create record.","status":400}

## 2026-08-27 17:08:16.866Z pocketbase.error
- message: POST /api/collections/users/records
- data: {"auth":"","details":"TypeError: Object has no member 'dao' at /Users/macbook/Desktop/app/apps/pocketbase/pb.js:12:11(50)","error":"Failed to create record.","execTime":121.883316,"method":"POST","referer":"http://localhost:3000/signup","remoteIP":"127.0.0.1","status":400,"type":"request","url":"/api/collections/users/records","userAgent":"Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/151.0.0.0 Safari/537.36","userIP":"127.0.0.1"}

## 2026-08-27 17:08:19.361Z pocketbase.error
- message: POST /api/collections/users/records
- data: {"auth":"","details":{"data":{"email":"Value must be unique"},"raw":"email: Value must be unique."},"error":"Failed to create record.","execTime":121.626908,"method":"POST","referer":"http://localhost:3000/signup","remoteIP":"127.0.0.1","status":400,"type":"request","url":"/api/collections/users/records","userAgent":"Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/151.0.0.0 Safari/537.36","userIP":"127.0.0.1"}

## 2026-08-27 17:08:25.288Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Konekte isit la"}

## 2026-08-27 17:08:25.289Z navigate
- url: http://localhost:3000/login
- via: pushState

## 2026-08-27 17:08:25.405Z focus
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"login-email","placeholder":"jan@ekzanp.com","label":"email","value":"","valueLength":0,"text":""}

## 2026-08-27 17:08:25.406Z change
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"login-email","placeholder":"jan@ekzanp.com","label":"email","value":"dadyhaiti1985@gmail.com","valueLength":23,"text":""}

## 2026-08-27 17:08:25.406Z blur
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"login-email","placeholder":"jan@ekzanp.com","label":"email","value":"dadyhaiti1985@gmail.com","valueLength":23,"text":""}

## 2026-08-27 17:08:25.406Z focus
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=0]","valueLength":0,"text":""}

## 2026-08-27 17:08:25.407Z change
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=14]","valueLength":14,"text":""}

## 2026-08-27 17:08:25.407Z blur
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=14]","valueLength":14,"text":""}

## 2026-08-27 17:08:44.890Z console.warn
- text: [Perf] Low FPS detected: 2

## 2026-08-27 17:08:46.184Z focus
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"login-email","placeholder":"jan@ekzanp.com","label":"email","value":"dadyhaiti1985@gmail.com","valueLength":23,"text":""}

## 2026-08-27 17:08:46.263Z click
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"login-email","placeholder":"jan@ekzanp.com","label":"email","value":"dadyhaiti1985@gmail.com","valueLength":23,"text":""}

## 2026-08-27 17:08:47.403Z blur
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"login-email","placeholder":"jan@ekzanp.com","label":"email","value":"dadyhaiti1985@gmail.com","valueLength":23,"text":""}

## 2026-08-27 17:08:47.515Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Enskri isit la"}

## 2026-08-27 17:08:47.515Z navigate
- url: http://localhost:3000/signup
- via: pushState

## 2026-08-27 17:08:48.560Z focus
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"signup-email","placeholder":"jan@ekzanp.com","label":"email","value":"","valueLength":0,"text":""}

## 2026-08-27 17:08:48.661Z click
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"signup-email","placeholder":"jan@ekzanp.com","label":"email","value":"","valueLength":0,"text":""}

## 2026-08-27 17:08:51.691Z change
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"signup-email","placeholder":"jan@ekzanp.com","label":"email","value":"coachsanssecrets@gmail.com","valueLength":26,"text":""}

## 2026-08-27 17:08:51.692Z blur
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"signup-email","placeholder":"jan@ekzanp.com","label":"email","value":"coachsanssecrets@gmail.com","valueLength":26,"text":""}

## 2026-08-27 17:08:51.692Z focus
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"signup-password","placeholder":"••••••••","label":"password","value":"[redacted:length=0]","valueLength":0,"text":""}

## 2026-08-27 17:08:51.827Z click
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"signup-password","placeholder":"••••••••","label":"password","value":"[redacted:length=0]","valueLength":0,"text":""}

## 2026-08-27 17:09:01.076Z change
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"signup-password","placeholder":"••••••••","label":"password","value":"[redacted:length=14]","valueLength":14,"text":""}

## 2026-08-27 17:09:01.076Z blur
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"signup-password","placeholder":"••••••••","label":"password","value":"[redacted:length=14]","valueLength":14,"text":""}

## 2026-08-27 17:09:01.076Z focus
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"passwordConfirm","type":"password","id":"signup-passwordConfirm","placeholder":"••••••••","label":"passwordConfirm","value":"[redacted:length=0]","valueLength":0,"text":""}

## 2026-08-27 17:09:01.187Z click
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"passwordConfirm","type":"password","id":"signup-passwordConfirm","placeholder":"••••••••","label":"passwordConfirm","value":"[redacted:length=0]","valueLength":0,"text":""}

## 2026-08-27 17:09:06.729Z change
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"passwordConfirm","type":"password","id":"signup-passwordConfirm","placeholder":"••••••••","label":"passwordConfirm","value":"[redacted:length=14]","valueLength":14,"text":""}

## 2026-08-27 17:09:06.729Z click
- element: {"tag":"button","role":null,"ariaLabel":null,"name":null,"type":"submit","id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Enskri (Sign up)"}

## 2026-08-27 17:09:06.729Z submit
- action: http://localhost:3000/signup
- fields: [{"label":"email","type":"email","value":"coachsanssecrets@gmail.com","length":26,"redacted":false},{"label":"password","type":"password","value":"[redacted:length=14]","length":14,"redacted":true},{"label":"passwordConfirm","type":"password","value":"[redacted:length=14]","length":14,"redacted":true},{"label":"[submit]","type":"submit","value":"","length":0,"redacted":false}]

## 2026-08-27 17:09:06.731Z blur
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"passwordConfirm","type":"password","id":"signup-passwordConfirm","placeholder":"••••••••","label":"passwordConfirm","value":"[redacted:length=14]","valueLength":14,"text":""}

## 2026-08-27 17:09:06.863Z network.error
- method: POST
- url: http://localhost:3000/hcgi/platform/api/collections/users/records
- status: 400
- statusText: Bad Request
- requestBody: {"email":"coachsanssecrets@gmail.com","password":"[redacted:length=14]","passwordConfirm":"[redacted:length=14]","emailVisibility":"true"}
- response: 
    {"data":{},"message":"Failed to create record.","status":400}
    
- durationMs: 134

## 2026-08-27 17:09:06.863Z console.error
- text: 
    Fetch error from http://localhost:3000/hcgi/platform/api/collections/users/records: {"data":{},"message":"Failed to create record.","status":400}
    

## 2026-08-27 17:09:06.864Z console.error
- text: [Signup] Full error: {"data":{},"message":"Failed to create record.","status":400}

## 2026-08-27 17:09:06.861Z pocketbase.error
- message: POST /api/collections/users/records
- data: {"auth":"","details":"TypeError: Object has no member 'dao' at /Users/macbook/Desktop/app/apps/pocketbase/pb.js:12:11(50)","error":"Failed to create record.","execTime":127.752492,"method":"POST","referer":"http://localhost:3000/signup","remoteIP":"127.0.0.1","status":400,"type":"request","url":"/api/collections/users/records","userAgent":"Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/151.0.0.0 Safari/537.36","userIP":"127.0.0.1"}

## 2026-08-27 17:09:14.191Z click
- element: {"tag":"button","role":null,"ariaLabel":null,"name":null,"type":"submit","id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Enskri (Sign up)"}

## 2026-08-27 17:09:14.192Z submit
- action: http://localhost:3000/signup
- fields: [{"label":"email","type":"email","value":"coachsanssecrets@gmail.com","length":26,"redacted":false},{"label":"password","type":"password","value":"[redacted:length=14]","length":14,"redacted":true},{"label":"passwordConfirm","type":"password","value":"[redacted:length=14]","length":14,"redacted":true},{"label":"[submit]","type":"submit","value":"","length":0,"redacted":false}]

## 2026-08-27 17:09:14.314Z network.error
- method: POST
- url: http://localhost:3000/hcgi/platform/api/collections/users/records
- status: 400
- statusText: Bad Request
- requestBody: {"email":"coachsanssecrets@gmail.com","password":"[redacted:length=14]","passwordConfirm":"[redacted:length=14]","emailVisibility":"true"}
- response: 
    {"data":{"email":{"code":"validation_not_unique","message":"Value must be unique."}},"message":"Failed to create record.","status":400}
    
- durationMs: 122

## 2026-08-27 17:09:14.314Z console.warn
- text: 
    Fetch error from http://localhost:3000/hcgi/platform/api/collections/users/records: {"data":{"email":{"code":"validation_not_unique","message":"Value must be unique."}},"message":"Failed to create record.","status":400}
    

## 2026-08-27 17:09:14.314Z console.error
- text: [Signup] Full error: {"data":{"email":{"code":"validation_not_unique","message":"Value must be unique."}},"message":"Failed to create record.","status":400}

## 2026-08-27 17:09:14.313Z pocketbase.error
- message: POST /api/collections/users/records
- data: {"auth":"","details":{"data":{"email":"Value must be unique"},"raw":"email: Value must be unique."},"error":"Failed to create record.","execTime":117.981541,"method":"POST","referer":"http://localhost:3000/signup","remoteIP":"127.0.0.1","status":400,"type":"request","url":"/api/collections/users/records","userAgent":"Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/151.0.0.0 Safari/537.36","userIP":"127.0.0.1"}

## 2026-08-27 17:09:20.826Z click
- element: {"tag":"button","role":null,"ariaLabel":null,"name":null,"type":"submit","id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Enskri (Sign up)"}

## 2026-08-27 17:09:20.826Z submit
- action: http://localhost:3000/signup
- fields: [{"label":"email","type":"email","value":"coachsanssecrets@gmail.com","length":26,"redacted":false},{"label":"password","type":"password","value":"[redacted:length=14]","length":14,"redacted":true},{"label":"passwordConfirm","type":"password","value":"[redacted:length=14]","length":14,"redacted":true},{"label":"[submit]","type":"submit","value":"","length":0,"redacted":false}]

## 2026-08-27 17:09:20.950Z network.error
- method: POST
- url: http://localhost:3000/hcgi/platform/api/collections/users/records
- status: 400
- statusText: Bad Request
- requestBody: {"email":"coachsanssecrets@gmail.com","password":"[redacted:length=14]","passwordConfirm":"[redacted:length=14]","emailVisibility":"true"}
- response: 
    {"data":{"email":{"code":"validation_not_unique","message":"Value must be unique."}},"message":"Failed to create record.","status":400}
    
- durationMs: 124

## 2026-08-27 17:09:20.950Z console.warn
- text: 
    Fetch error from http://localhost:3000/hcgi/platform/api/collections/users/records: {"data":{"email":{"code":"validation_not_unique","message":"Value must be unique."}},"message":"Failed to create record.","status":400}
    

## 2026-08-27 17:09:20.950Z console.error
- text: [Signup] Full error: {"data":{"email":{"code":"validation_not_unique","message":"Value must be unique."}},"message":"Failed to create record.","status":400}

## 2026-08-27 17:09:22.858Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Konekte isit la"}

## 2026-08-27 17:09:22.858Z navigate
- url: http://localhost:3000/login
- via: pushState

## 2026-08-27 17:09:22.973Z focus
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"login-email","placeholder":"jan@ekzanp.com","label":"email","value":"","valueLength":0,"text":""}

## 2026-08-27 17:09:22.973Z change
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"login-email","placeholder":"jan@ekzanp.com","label":"email","value":"dadyhaiti1985@gmail.com","valueLength":23,"text":""}

## 2026-08-27 17:09:22.973Z blur
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"email","type":"email","id":"login-email","placeholder":"jan@ekzanp.com","label":"email","value":"dadyhaiti1985@gmail.com","valueLength":23,"text":""}

## 2026-08-27 17:09:22.973Z focus
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=0]","valueLength":0,"text":""}

## 2026-08-27 17:09:22.974Z change
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=14]","valueLength":14,"text":""}

## 2026-08-27 17:09:22.974Z blur
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"password","type":"password","id":"login-password","placeholder":"••••••••","label":"password","value":"[redacted:length=14]","valueLength":14,"text":""}

## 2026-08-27 17:09:20.948Z pocketbase.error
- message: POST /api/collections/users/records
- data: {"auth":"","details":{"data":{"email":"Value must be unique"},"raw":"email: Value must be unique."},"error":"Failed to create record.","execTime":120.409151,"method":"POST","referer":"http://localhost:3000/signup","remoteIP":"127.0.0.1","status":400,"type":"request","url":"/api/collections/users/records","userAgent":"Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/151.0.0.0 Safari/537.36","userIP":"127.0.0.1"}

## 2026-08-27 17:09:24.564Z click
- element: {"tag":"button","role":null,"ariaLabel":null,"name":null,"type":"submit","id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Konekte (Login)"}

## 2026-08-27 17:09:24.564Z submit
- action: http://localhost:3000/login
- fields: [{"label":"email","type":"email","value":"dadyhaiti1985@gmail.com","length":23,"redacted":false},{"label":"password","type":"password","value":"[redacted:length=14]","length":14,"redacted":true},{"label":"[submit]","type":"submit","value":"","length":0,"redacted":false}]

## 2026-08-27 17:09:24.649Z navigate
- url: http://localhost:3000/dashboard
- via: replaceState

## 2026-08-27 17:09:24.866Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/ecommerce/subscriptions
- status: 503
- statusText: Service Unavailable
- response: {"error":"Subscription service is temporarily unavailable. Please retry.","code":"SUBSCRIPTIONS_UNAVAILABLE","subscriptions":[]}
- durationMs: 233

## 2026-08-27 17:09:25.024Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/ecommerce/subscriptions: {"error":"Subscription service is temporarily unavailable. Please retry.","code":"SUBSCRIPTIONS_UNAVAILABLE","subscriptions":[]}

## 2026-08-27 17:09:25.024Z console.error
- text: 
    Failed to fetch subscriptions: Error: Failed to fetch subscriptions: 503
        at getUserSubscriptions (http://localhost:3000/src/api/InternalEcommerceSubscriptionsApi.js:29:9)
        at async SubscriptionAuthProvider.fetchSubscriptionsRef.current (http://localhost:3000/src/contexts/SubscriptionAuthContext.jsx:20:19)

## 2026-08-27 17:09:25.130Z console.warn
- text: [Perf] Worker took 344.3ms (target <50ms)

## 2026-08-27 17:09:25.207Z console.warn
- text: [Perf] Low FPS detected: 42

## 2026-08-27 17:09:25.661Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/user/balance
- status: 400
- statusText: Bad Request
- response: {"success":false,"error":"API credentials not configured. Please add your Coinbase API keys in the dashboard.","code":"NO_CREDENTIALS"}
- durationMs: 17

## 2026-08-27 17:09:25.661Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/user/balance: {"success":false,"error":"API credentials not configured. Please add your Coinbase API keys in the dashboard.","code":"NO_CREDENTIALS"}

## 2026-08-27 17:10:25.605Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/user/balance
- status: 400
- statusText: Bad Request
- response: {"success":false,"error":"API credentials not configured. Please add your Coinbase API keys in the dashboard.","code":"NO_CREDENTIALS"}
- durationMs: 43

## 2026-08-27 17:10:25.605Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/user/balance: {"success":false,"error":"API credentials not configured. Please add your Coinbase API keys in the dashboard.","code":"NO_CREDENTIALS"}

## 2026-08-27 17:10:48.177Z console.warn
- text: [Perf] Low FPS detected: 1

## 2026-08-27 17:10:51.413Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"AI Signals"}

## 2026-08-27 17:10:51.413Z navigate
- url: http://localhost:3000/dashboard#signals
- via: pushState

## 2026-08-27 17:10:53.505Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Markets"}

## 2026-08-27 17:10:53.505Z navigate
- url: http://localhost:3000/dashboard#markets
- via: pushState

## 2026-08-27 17:11:00.556Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"AI Analysis"}

## 2026-08-27 17:11:00.557Z navigate
- url: http://localhost:3000/dashboard#analysis
- via: pushState

## 2026-08-27 17:11:02.527Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Trading"}

## 2026-08-27 17:11:02.527Z navigate
- url: http://localhost:3000/dashboard#trading
- via: pushState

## 2026-08-27 17:11:05.489Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Watchlist"}

## 2026-08-27 17:11:05.489Z navigate
- url: http://localhost:3000/dashboard#watchlist
- via: pushState

## 2026-08-27 17:11:07.242Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Dashboard"}

## 2026-08-27 17:11:07.242Z navigate
- url: http://localhost:3000/dashboard
- via: pushState

## 2026-08-27 17:11:07.504Z console.warn
- text: [Perf] Worker took 201.5ms (target <50ms)

## 2026-08-27 17:12:50.148Z console.warn
- text: [Perf] Low FPS detected: 6

## 2026-08-27 17:12:53.504Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Markets"}

## 2026-08-27 17:12:53.504Z navigate
- url: http://localhost:3000/dashboard#markets
- via: pushState

## 2026-08-27 17:12:59.729Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"AI Signals"}

## 2026-08-27 17:12:59.730Z navigate
- url: http://localhost:3000/dashboard#signals
- via: pushState

## 2026-08-27 17:13:06.414Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Orders"}

## 2026-08-27 17:13:06.414Z navigate
- url: http://localhost:3000/dashboard#orders
- via: pushState

## 2026-08-27 17:13:10.401Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Orders"}

## 2026-08-27 17:13:10.401Z navigate
- url: http://localhost:3000/dashboard#orders
- via: replaceState

## 2026-08-27 17:13:12.916Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Economic Calendar"}

## 2026-08-27 17:13:12.916Z navigate
- url: http://localhost:3000/dashboard#calendar
- via: pushState

## 2026-08-27 17:13:16.031Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Analytics"}

## 2026-08-27 17:13:16.032Z navigate
- url: http://localhost:3000/dashboard#analytics
- via: pushState

## 2026-08-27 17:13:17.681Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Trade History"}

## 2026-08-27 17:13:17.682Z navigate
- url: http://localhost:3000/dashboard#trade-history
- via: pushState

## 2026-08-27 17:13:19.197Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Deposits"}

## 2026-08-27 17:13:19.198Z navigate
- url: http://localhost:3000/dashboard#deposits
- via: pushState

## 2026-08-27 17:13:20.364Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Referral"}

## 2026-08-27 17:13:20.365Z navigate
- url: http://localhost:3000/dashboard#referral
- via: pushState

## 2026-08-27 17:13:21.948Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Settings"}

## 2026-08-27 17:13:21.948Z navigate
- url: http://localhost:3000/dashboard#settings
- via: pushState

## 2026-08-27 17:13:26.315Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Dashboard"}

## 2026-08-27 17:13:26.315Z navigate
- url: http://localhost:3000/dashboard
- via: pushState

## 2026-08-27 17:13:26.510Z console.warn
- text: [Perf] Low FPS detected: 53

## 2026-08-27 17:13:26.548Z console.warn
- text: [Perf] Worker took 181.2ms (target <50ms)

## 2026-08-27 17:13:35.420Z click
- element: {"tag":"button","role":null,"ariaLabel":"Open AI Assistant","name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":""}

## 2026-08-27 17:13:35.455Z focus
- element: {"tag":"input","role":null,"ariaLabel":null,"name":"message","type":"text","id":"ai-chat-input","placeholder":"Ask a question...","label":"message","value":"","valueLength":0,"text":""}

## 2026-08-27 17:13:37.092Z click
- element: {"tag":"button","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Analyze current market conditions"}

## 2026-08-27 17:13:37.239Z network.error
- method: POST
- url: http://localhost:3000/hcgi/api/integrated-ai/stream
- status: 500
- statusText: Internal Server Error
- requestBody: {"message":"[{\"text\":\"Please respond in English. [USER TRADING CONTEXT]\\nBalance: $0.00\\nBot Status: INACTIVE\\nTotal Trades: 0\\nWin Rate: 0%\\nTotal P&L: $0.00\\nRecent Trades (last 5): None\\n[/USER TRADING CONTEXT]\\n\\nAnalyze current market conditions\",\"type\":\"text\"}]"}
- response: {"message":"Something went wrong!","error":{"name":"TypeError","message":"Failed to parse URL from undefined/generate","stack":"TypeError: Failed to parse URL from undefined/generate"}}
- durationMs: 144

## 2026-08-27 17:13:37.239Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/integrated-ai/stream: {"message":"Something went wrong!","error":{"name":"TypeError","message":"Failed to parse URL from undefined/generate","stack":"TypeError: Failed to parse URL from undefined/generate"}}

## 2026-08-27 17:13:39.255Z network.error
- method: POST
- url: http://localhost:3000/hcgi/api/integrated-ai/stream
- status: 500
- statusText: Internal Server Error
- requestBody: {"message":"[{\"text\":\"Please respond in English. [USER TRADING CONTEXT]\\nBalance: $0.00\\nBot Status: INACTIVE\\nTotal Trades: 0\\nWin Rate: 0%\\nTotal P&L: $0.00\\nRecent Trades (last 5): None\\n[/USER TRADING CONTEXT]\\n\\nAnalyze current market conditions\",\"type\":\"text\"}]"}
- response: {"message":"Something went wrong!","error":{"name":"TypeError","message":"Failed to parse URL from undefined/generate","stack":"TypeError: Failed to parse URL from undefined/generate"}}
- durationMs: 14

## 2026-08-27 17:13:39.255Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/integrated-ai/stream: {"message":"Something went wrong!","error":{"name":"TypeError","message":"Failed to parse URL from undefined/generate","stack":"TypeError: Failed to parse URL from undefined/generate"}}

## 2026-08-27 17:13:43.283Z network.error
- method: POST
- url: http://localhost:3000/hcgi/api/integrated-ai/stream
- status: 500
- statusText: Internal Server Error
- requestBody: {"message":"[{\"text\":\"Please respond in English. [USER TRADING CONTEXT]\\nBalance: $0.00\\nBot Status: INACTIVE\\nTotal Trades: 0\\nWin Rate: 0%\\nTotal P&L: $0.00\\nRecent Trades (last 5): None\\n[/USER TRADING CONTEXT]\\n\\nAnalyze current market conditions\",\"type\":\"text\"}]"}
- response: {"message":"Something went wrong!","error":{"name":"TypeError","message":"Failed to parse URL from undefined/generate","stack":"TypeError: Failed to parse URL from undefined/generate"}}
- durationMs: 20

## 2026-08-27 17:13:43.283Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/integrated-ai/stream: {"message":"Something went wrong!","error":{"name":"TypeError","message":"Failed to parse URL from undefined/generate","stack":"TypeError: Failed to parse URL from undefined/generate"}}

## 2026-08-27 17:14:32.056Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/user/balance
- status: 400
- statusText: Bad Request
- response: {"success":false,"error":"API credentials not configured. Please add your Coinbase API keys in the dashboard.","code":"NO_CREDENTIALS"}
- durationMs: 195

## 2026-08-27 17:14:32.056Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/user/balance: {"success":false,"error":"API credentials not configured. Please add your Coinbase API keys in the dashboard.","code":"NO_CREDENTIALS"}

## 2026-08-27 17:15:45.508Z console.warn
- text: [Perf] Low FPS detected: 54

## 2026-08-27 17:15:53.964Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Portfolio"}

## 2026-08-27 17:15:53.965Z navigate
- url: http://localhost:3000/dashboard#portfolio
- via: pushState

## 2026-08-27 17:16:05.506Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"AI Signals"}

## 2026-08-27 17:16:05.506Z navigate
- url: http://localhost:3000/dashboard#signals
- via: pushState

## 2026-08-27 17:16:08.010Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Dashboard"}

## 2026-08-27 17:16:08.010Z navigate
- url: http://localhost:3000/dashboard
- via: pushState

## 2026-08-27 17:16:08.202Z console.warn
- text: [Perf] Worker took 138.4ms (target <50ms)

## 2026-08-15 04:48:17.172Z console.warn
- text: [Perf] Worker took 51.7ms (target <50ms)

## 2026-08-15 04:50:17.436Z console.warn
- text: [Perf] Worker took 90.6ms (target <50ms)

## 2026-08-15 04:53:24.892Z console.warn
- text: [Perf] Worker took 50.1ms (target <50ms)

## 2026-08-28 02:44:32.158Z load
- url: http://localhost:3000/

## 2026-08-28 02:44:33.952Z navigate
- url: http://localhost:3000/
- via: replaceState

## 2026-08-28 02:44:34.339Z network.error
- method: GET
- url: http://localhost:3000/hcgi/platform/api/collections/_integratedAiMessages/records?page=1&perPage=500&skipTotal=1&sort=created
- status: 500
- statusText: Internal Server Error
- durationMs: 274

## 2026-08-28 02:44:34.340Z network.error
- method: GET
- url: http://localhost:3000/hcgi/platform/api/collections/bot_account_balance/records?page=1&perPage=1&filter=userId%20%3D%20%22k3atxfk5yxgefz2%22&sort=-created
- status: 500
- statusText: Internal Server Error
- durationMs: 273

## 2026-08-28 02:44:34.340Z network.error
- method: GET
- url: http://localhost:3000/hcgi/platform/api/collections/bot_portfolio/records?page=1&perPage=20&filter=userId%20%3D%20%22k3atxfk5yxgefz2%22&sort=-created
- status: 500
- statusText: Internal Server Error
- durationMs: 273

## 2026-08-28 02:44:34.340Z network.error
- method: GET
- url: http://localhost:3000/hcgi/platform/api/collections/trades/records?page=1&perPage=10&filter=userId%20%3D%20%22k3atxfk5yxgefz2%22&sort=-created
- status: 500
- statusText: Internal Server Error
- durationMs: 273

## 2026-08-28 02:44:34.389Z network.error
- method: GET
- url: http://localhost:3000/hcgi/platform/api/collections/oracle_credentials/records?page=1&perPage=1&filter=owner%20%3D%20%22k3atxfk5yxgefz2%22&skipTotal=1
- status: 500
- statusText: Internal Server Error
- durationMs: 321

## 2026-08-28 02:44:34.389Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/ecommerce/subscriptions
- status: 500
- statusText: Internal Server Error
- durationMs: 309

## 2026-08-28 02:44:34.389Z network.error
- method: GET
- url: http://localhost:3000/hcgi/platform/api/collections/oracle_credentials/records?page=1&perPage=1&filter=owner%20%3D%20%22k3atxfk5yxgefz2%22&skipTotal=1
- status: 500
- statusText: Internal Server Error
- durationMs: 309

## 2026-08-28 02:44:34.404Z console.error
- text: Fetch error from http://localhost:3000/hcgi/platform/api/collections/_integratedAiMessages/records?page=1&perPage=500&skipTotal=1&sort=created: 

## 2026-08-28 02:44:34.409Z console.error
- text: Fetch error from http://localhost:3000/hcgi/platform/api/collections/bot_account_balance/records?page=1&perPage=1&filter=userId%20%3D%20%22k3atxfk5yxgefz2%22&sort=-created: 

## 2026-08-28 02:44:34.410Z console.error
- text: Fetch error from http://localhost:3000/hcgi/platform/api/collections/bot_portfolio/records?page=1&perPage=20&filter=userId%20%3D%20%22k3atxfk5yxgefz2%22&sort=-created: 

## 2026-08-28 02:44:34.411Z console.error
- text: Fetch error from http://localhost:3000/hcgi/platform/api/collections/trades/records?page=1&perPage=10&filter=userId%20%3D%20%22k3atxfk5yxgefz2%22&sort=-created: 

## 2026-08-28 02:44:34.497Z console.error
- text: Fetch error from http://localhost:3000/hcgi/platform/api/collections/oracle_credentials/records?page=1&perPage=1&filter=owner%20%3D%20%22k3atxfk5yxgefz2%22&skipTotal=1: 

## 2026-08-28 02:44:34.498Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/ecommerce/subscriptions: 

## 2026-08-28 02:44:34.498Z console.error
- text: 
    Failed to fetch subscriptions: Error: Failed to fetch subscriptions: 500
        at getUserSubscriptions (http://localhost:3000/src/api/InternalEcommerceSubscriptionsApi.js:29:9)
        at async SubscriptionAuthProvider.fetchSubscriptionsRef.current (http://localhost:3000/src/contexts/SubscriptionAuthContext.jsx:20:19)

## 2026-08-28 02:44:34.498Z console.error
- text: Fetch error from http://localhost:3000/hcgi/platform/api/collections/oracle_credentials/records?page=1&perPage=1&filter=owner%20%3D%20%22k3atxfk5yxgefz2%22&skipTotal=1: 

## 2026-08-28 02:44:34.941Z console.warn
- text: [Perf] Low FPS detected: 29

## 2026-08-28 02:44:36.334Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":" KONT PA OU"}

## 2026-08-28 02:44:36.335Z navigate
- url: http://localhost:3000/dashboard/oracle-trader-pro
- via: pushState

## 2026-08-28 02:44:36.643Z network.error
- method: GET
- url: http://localhost:3000/hcgi/platform/api/collections/_integratedAiMessages/records?page=1&perPage=500&skipTotal=1&sort=created
- status: 500
- statusText: Internal Server Error
- durationMs: 106

## 2026-08-28 02:44:36.643Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/health
- status: 500
- statusText: Internal Server Error
- durationMs: 105

## 2026-08-28 02:44:36.643Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/bot/status
- status: 500
- statusText: Internal Server Error
- durationMs: 105

## 2026-08-28 02:44:36.643Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/oracle-trader-pro/trades
- status: 500
- statusText: Internal Server Error
- durationMs: 105

## 2026-08-28 02:44:36.651Z console.error
- text: Fetch error from http://localhost:3000/hcgi/platform/api/collections/_integratedAiMessages/records?page=1&perPage=500&skipTotal=1&sort=created: 

## 2026-08-28 02:44:36.652Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/health: 

## 2026-08-28 02:44:36.652Z console.warn
- text: [useAIConnection] Backend unreachable (500). Retry 1/8 in 1000ms

## 2026-08-28 02:44:36.652Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/bot/status: 

## 2026-08-28 02:44:36.653Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/oracle-trader-pro/trades: 

## 2026-08-28 02:44:36.706Z console.warn
- text: [Perf] Worker took 245.0ms (target <50ms)

## 2026-08-28 02:44:36.958Z console.warn
- text: [Perf] Low FPS detected: 50

## 2026-08-28 02:44:37.163Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/user/balance
- status: 500
- statusText: Internal Server Error
- durationMs: 9

## 2026-08-28 02:44:37.166Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/user/balance: 

## 2026-08-28 02:44:37.664Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/health
- status: 500
- statusText: Internal Server Error
- durationMs: 10

## 2026-08-28 02:44:37.666Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/health: 

## 2026-08-28 02:44:37.666Z console.warn
- text: [useAIConnection] Backend unreachable (500). Retry 2/8 in 2000ms

## 2026-08-28 02:44:39.684Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/health
- status: 500
- statusText: Internal Server Error
- durationMs: 16

## 2026-08-28 02:44:39.684Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/health: 

## 2026-08-28 02:44:39.685Z console.warn
- text: [useAIConnection] Backend unreachable (500). Retry 3/8 in 4000ms

## 2026-08-28 02:44:40.298Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Portfolio"}

## 2026-08-28 02:44:40.299Z navigate
- url: http://localhost:3000/dashboard#portfolio
- via: pushState

## 2026-08-28 02:44:40.381Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/user/balance
- status: 500
- statusText: Internal Server Error
- durationMs: 43

## 2026-08-28 02:44:40.385Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/user/balance: 

## 2026-08-28 02:44:42.154Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Orders"}

## 2026-08-28 02:44:42.155Z navigate
- url: http://localhost:3000/dashboard#orders
- via: pushState

## 2026-08-28 02:44:42.187Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 9

## 2026-08-28 02:44:42.187Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 02:44:43.437Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Watchlist"}

## 2026-08-28 02:44:43.437Z navigate
- url: http://localhost:3000/dashboard#watchlist
- via: pushState

## 2026-08-28 02:44:43.690Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/health
- status: 500
- statusText: Internal Server Error
- durationMs: 5

## 2026-08-28 02:44:43.691Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/health: 

## 2026-08-28 02:44:43.691Z console.warn
- text: [useAIConnection] Backend unreachable (500). Retry 4/8 in 8000ms

## 2026-08-28 02:44:44.759Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"News Intelligence"}

## 2026-08-28 02:44:44.759Z navigate
- url: http://localhost:3000/dashboard#news
- via: pushState

## 2026-08-28 02:44:45.937Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Smart Money"}

## 2026-08-28 02:44:45.937Z navigate
- url: http://localhost:3000/dashboard#smartmoney
- via: pushState

## 2026-08-28 02:44:47.977Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Economic Calendar"}

## 2026-08-28 02:44:47.977Z navigate
- url: http://localhost:3000/dashboard#calendar
- via: pushState

## 2026-08-28 02:44:48.012Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/economic-calendar?range=week&impact=all&currency=all
- status: 500
- statusText: Internal Server Error
- durationMs: 7

## 2026-08-28 02:44:48.012Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/economic-calendar?range=week&impact=all&currency=all: 

## 2026-08-28 02:44:48.012Z console.error
- text: 
    Failed to load economic calendar: SyntaxError: Unexpected end of JSON input
        at load (http://localhost:3000/src/views/EconomicCalendarView.jsx:161:40)

## 2026-08-28 02:44:49.001Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Analytics"}

## 2026-08-28 02:44:49.002Z navigate
- url: http://localhost:3000/dashboard#analytics
- via: pushState

## 2026-08-28 02:44:49.058Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/oracle-trader-pro/trades
- status: 500
- statusText: Internal Server Error
- durationMs: 22

## 2026-08-28 02:44:49.061Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/oracle-trader-pro/trades: 

## 2026-08-28 02:44:49.062Z console.error
- text: 
    Failed to load analytics trades: Error: HTTP 500
        at loadTrades (http://localhost:3000/src/views/AnalyticsView.jsx:321:17)

## 2026-08-28 02:44:51.536Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Trade History"}

## 2026-08-28 02:44:51.537Z navigate
- url: http://localhost:3000/dashboard#trade-history
- via: pushState

## 2026-08-28 02:44:51.574Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/oracle-trader-pro/trades
- status: 500
- statusText: Internal Server Error
- durationMs: 12

## 2026-08-28 02:44:51.574Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/oracle-trader-pro/trades: 

## 2026-08-28 02:44:51.574Z console.error
- text: 
    Failed to load trade history: Error: HTTP 500
        at loadTrades (http://localhost:3000/src/views/TradeHistoryView.jsx:201:33)

## 2026-08-28 02:44:51.698Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/health
- status: 500
- statusText: Internal Server Error
- durationMs: 4

## 2026-08-28 02:44:51.698Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/health: 

## 2026-08-28 02:44:51.698Z console.warn
- text: [useAIConnection] Backend unreachable (500). Retry 5/8 in 16000ms

## 2026-08-28 02:44:53.452Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Dashboard"}

## 2026-08-28 02:44:53.452Z navigate
- url: http://localhost:3000/dashboard
- via: pushState

## 2026-08-28 02:44:53.620Z console.warn
- text: [Perf] Worker took 74.1ms (target <50ms)

## 2026-08-28 02:45:07.730Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/health
- status: 500
- statusText: Internal Server Error
- durationMs: 31

## 2026-08-28 02:45:07.730Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/health: 

## 2026-08-28 02:45:07.730Z console.warn
- text: [useAIConnection] Backend unreachable (500). Retry 6/8 in 30000ms

## 2026-08-28 02:45:17.521Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Markets"}

## 2026-08-28 02:45:17.521Z navigate
- url: http://localhost:3000/dashboard#markets
- via: pushState

## 2026-08-28 02:45:18.693Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Dashboard"}

## 2026-08-28 02:45:18.693Z navigate
- url: http://localhost:3000/dashboard
- via: pushState

## 2026-08-28 02:45:18.823Z console.warn
- text: [Perf] Worker took 86.0ms (target <50ms)

## 2026-08-28 02:45:19.874Z click
- element: {"tag":"button","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":" START AI TRADING"}

## 2026-08-28 02:45:19.926Z network.error
- method: POST
- url: http://localhost:3000/hcgi/api/bot/toggle
- status: 500
- statusText: Internal Server Error
- requestBody: {"botActive":"true"}
- durationMs: 51

## 2026-08-28 02:45:19.936Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/bot/toggle: 

## 2026-08-28 02:45:19.937Z console.warn
- text: [useBotToggle] Attempt 1 failed: HTTP 500. Retrying in 1000ms…

## 2026-08-28 02:45:20.942Z network.error
- method: POST
- url: http://localhost:3000/hcgi/api/bot/toggle
- status: 500
- statusText: Internal Server Error
- requestBody: {"botActive":"true"}
- durationMs: 3

## 2026-08-28 02:45:20.942Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/bot/toggle: 

## 2026-08-28 02:45:20.942Z console.warn
- text: [useBotToggle] Attempt 2 failed: HTTP 500. Retrying in 2000ms…

## 2026-08-28 02:45:22.949Z network.error
- method: POST
- url: http://localhost:3000/hcgi/api/bot/toggle
- status: 500
- statusText: Internal Server Error
- requestBody: {"botActive":"true"}
- durationMs: 7

## 2026-08-28 02:45:22.949Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/bot/toggle: 

## 2026-08-28 02:45:22.949Z console.warn
- text: [useBotToggle] Attempt 3 failed: HTTP 500. Retrying in 4000ms…

## 2026-08-28 02:45:26.959Z network.error
- method: POST
- url: http://localhost:3000/hcgi/api/bot/toggle
- status: 500
- statusText: Internal Server Error
- requestBody: {"botActive":"true"}
- durationMs: 5

## 2026-08-28 02:45:26.959Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/bot/toggle: 

## 2026-08-28 02:45:36.552Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/user/balance
- status: 500
- statusText: Internal Server Error
- durationMs: 11

## 2026-08-28 02:45:36.552Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/user/balance: 

## 2026-08-28 02:45:37.736Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/health
- status: 500
- statusText: Internal Server Error
- durationMs: 4

## 2026-08-28 02:45:37.736Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/health: 

## 2026-08-28 02:45:37.736Z console.warn
- text: [useAIConnection] Backend unreachable (500). Retry 7/8 in 30000ms

## 2026-08-28 02:45:39.536Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"AI Analysis"}

## 2026-08-28 02:45:39.536Z navigate
- url: http://localhost:3000/dashboard#analysis
- via: pushState

## 2026-08-28 02:45:40.382Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"AI Analysis"}

## 2026-08-28 02:45:40.382Z navigate
- url: http://localhost:3000/dashboard#analysis
- via: replaceState

## 2026-08-28 02:45:41.417Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Trading"}

## 2026-08-28 02:45:41.418Z navigate
- url: http://localhost:3000/dashboard#trading
- via: pushState

## 2026-08-28 02:45:41.452Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/oracle-trader-pro/candles?symbol=BTC-USD&interval=900&limit=160
- status: 500
- statusText: Internal Server Error
- durationMs: 9

## 2026-08-28 02:45:41.452Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/oracle-trader-pro/positions?symbol=BTC-USD
- status: 500
- statusText: Internal Server Error
- durationMs: 9

## 2026-08-28 02:45:41.452Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/oracle-trader-pro/candles?symbol=BTC-USD&interval=900&limit=160: 

## 2026-08-28 02:45:41.452Z console.error
- text: 
    Failed to load candles: Error: HTTP 500
        at http://localhost:3000/src/views/TradingView.jsx:231:15

## 2026-08-28 02:45:41.452Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/oracle-trader-pro/positions?symbol=BTC-USD: 

## 2026-08-28 02:45:41.453Z console.error
- text: 
    Failed to load positions: Error: HTTP 500
        at http://localhost:3000/src/views/TradingView.jsx:265:15

## 2026-08-28 02:45:42.688Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Orders"}

## 2026-08-28 02:45:42.688Z navigate
- url: http://localhost:3000/dashboard#orders
- via: pushState

## 2026-08-28 02:45:42.724Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 14

## 2026-08-28 02:45:42.724Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 02:45:45.472Z click
- element: {"tag":"p","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"INTELLIGENCE"}

## 2026-08-28 02:45:46.890Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Watchlist"}

## 2026-08-28 02:45:46.891Z navigate
- url: http://localhost:3000/dashboard#watchlist
- via: pushState

## 2026-08-28 02:45:48.962Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"News Intelligence"}

## 2026-08-28 02:45:48.962Z navigate
- url: http://localhost:3000/dashboard#news
- via: pushState

## 2026-08-28 02:45:50.476Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Watchlist"}

## 2026-08-28 02:45:50.476Z navigate
- url: http://localhost:3000/dashboard#watchlist
- via: pushState

## 2026-08-28 02:45:52.270Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Dashboard"}

## 2026-08-28 02:45:52.270Z navigate
- url: http://localhost:3000/dashboard
- via: pushState

## 2026-08-28 02:45:52.443Z console.warn
- text: [Perf] Worker took 119.4ms (target <50ms)

## 2026-08-28 02:45:54.722Z click
- element: {"tag":"div","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"BTC67,245+2.3%ETH3,512+1.8%SOL182.4+4.1%XRP0.628-0.9%GOLD2,341+0.4%EUR/USD1.0842-0.1%BTC67,245+2.3%ETH3,512+1.8%SOL182.4+4.1%XRP0.628-0.9%GOLD2,341+0.4%EUR/USD1.0842-0.1%AI LIVE12ms99.9%ENTraderOracle AI EngineACTIVE Market ConnectedScanning Global Markets...AI Confidence86%Opportunity70%Risk LevelMediumSentimentBullishAI RecommendationSTRONG BUY — BTC/USDTarget: $71,200 · SL: $65,800 · R/R: 1:2.8HIGH CONFIDENCE START AI TRADINGScanning MarketsLive Market OverviewallcryptoindexforexcommodityBTBTC/USDBitcoin+2.30%$67,245Vol: 42.1BHighAnalyzeETETH/USDEthereum+1.80%$3,512Vol: 18.3BMedAnalyzeSOSOL/USDSolana+4.10%$182.40Vol: 5.2BHighAnalyzeXRXRP/USDXRP-0.90%$0.6280Vol: 2.1BMedAnalyzeBNBNB/USDBNB+0.60%$418.20Vol: 1.4BLowAnalyzeNANASDAQNASDAQ-0.40%$19,128Vol: 8.9BLowAnalyzeS&S&P500S&P 500+0.20%$5,432Vol: 12.1BLowAnalyzeGOGOLDGold+0.40%$2,341Vol: 3.2BLowAnalyzeEUEUR/USDEuro-0.10%$1.0842Vol: 6.4BLowAnalyzeGBGBP/USDPound+0.30%$1.2641Vol: 2.8BLowAnalyzeUSUSD/JPYDollar/Yen-0.20%$156.78Vol: 4.1BMedAnalyzeBTC/USD+2.3%1m5m15m1H4H1D1W1MEMA 9EMA 21RSIMACDVWAPBBAI Analysis PanelLIVE87%AI Confidence ScoreStrong BuyBTC/USD — 4H timeframeBullish Score73%Bearish Score28%Buy Probability81%Sell Probability19%Trend Strength78%Market Volatility17%Momentum68%Liquidity85%Institutional64%Expected Move3.2% Bulls 73% Bears 27%Trade ExecutionBTC/USD · $67,245AssetBTC/USDETH/USDSOL/USDXRP/USDBNB/USDGOLDEUR/USDGBP/USDCurrent Price$67,245Spread$12.4Order TypeMarketLimitStopStop-LimitLeverage1x2x5x10x20x50x100xLot SizeRisk %Take ProfitStop LossMargin: $67.25Risk: $13.45 BUY SELLAI SignalsUpdated 10:45:52 PMAssetSignalConf.TFRiskTargetStop LossEst. ProfitStatusBTC/USDBUY87%4HLow71,20065,800+8.4%ActiveETH/USDBUY74%1DMed3,8503,320+9.6%ActiveSOL/USDSELL62%4HHigh165.00195.00+9.5%PendingGOLDBUY78%1DLow2,3902,295+2.1%ActiveEUR/USDSELL55%1HLow1.071.09+0.85%PendingGBP/USDHOLD51%4HMed1.271.26+0.62%WatchXRP/USDBUY69%1DHigh0.72000.5900+14.6%ActiveNASDAQHOLD58%1DLow19,50018,800+1.9%WatchPortfolioTotal Balance$0.00..."}

## 2026-08-28 02:45:56.987Z console.warn
- text: [Perf] Low FPS detected: 36

## 2026-08-28 02:46:07.917Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/health
- status: 500
- statusText: Internal Server Error
- durationMs: 179

## 2026-08-28 02:46:07.917Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/health: 

## 2026-08-28 02:46:07.917Z console.warn
- text: [useAIConnection] Backend unreachable (500). Retry 8/8 in 30000ms

## 2026-08-28 02:46:38.089Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/health
- status: 500
- statusText: Internal Server Error
- durationMs: 170

## 2026-08-28 02:46:38.089Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/health: 

## 2026-08-28 02:46:38.090Z console.error
- text: [useAIConnection] Max reconnect attempts reached. Giving up.

## 2026-08-28 02:46:41.218Z click
- element: {"tag":"div","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Oracle AI EngineACTIVE Market ConnectedScanning Global Markets...AI Confidence85%Opportunity67%Risk LevelMediumSentimentBullishAI RecommendationSTRONG BUY — BTC/USDTarget: $71,200 · SL: $65,800 · R/R: 1:2.8HIGH CONFIDENCE START AI TRADING"}

## 2026-08-28 02:46:46.693Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"AI Signals"}

## 2026-08-28 02:46:46.693Z navigate
- url: http://localhost:3000/dashboard#signals
- via: pushState

## 2026-08-28 02:46:48.192Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"AI Analysis"}

## 2026-08-28 02:46:48.193Z navigate
- url: http://localhost:3000/dashboard#analysis
- via: pushState

## 2026-08-28 02:46:49.547Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Portfolio"}

## 2026-08-28 02:46:49.547Z navigate
- url: http://localhost:3000/dashboard#portfolio
- via: pushState

## 2026-08-28 02:46:49.562Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/user/balance
- status: 500
- statusText: Internal Server Error
- durationMs: 6

## 2026-08-28 02:46:49.562Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/user/balance: 

## 2026-08-28 02:46:51.690Z click
- element: {"tag":"button","role":null,"ariaLabel":null,"name":null,"type":"button","id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Principal (Par défaut)14,10 $US • 12.96%"}

## 2026-08-28 02:46:52.649Z click
- element: {"tag":"button","role":null,"ariaLabel":null,"name":null,"type":"button","id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"DADY94,71 $US • 87.04%"}

## 2026-08-28 02:46:53.742Z click
- element: {"tag":"div","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"0.00%"}

## 2026-08-28 02:46:54.286Z click
- element: {"tag":"div","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"0.00%"}

## 2026-08-28 02:46:54.969Z click
- element: {"tag":"div","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"0.00%"}

## 2026-08-28 02:46:55.927Z click
- element: {"tag":"button","role":null,"ariaLabel":null,"name":null,"type":"button","id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Principal (Par défaut)14,10 $US • 12.96%"}

## 2026-08-28 02:46:56.621Z click
- element: {"tag":"button","role":null,"ariaLabel":null,"name":null,"type":"button","id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Tous les portefeuilles108,80 $US"}

## 2026-08-28 02:46:57.986Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Orders"}

## 2026-08-28 02:46:57.986Z navigate
- url: http://localhost:3000/dashboard#orders
- via: pushState

## 2026-08-28 02:46:58.026Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 17

## 2026-08-28 02:46:58.027Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 02:47:02.138Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Dashboard"}

## 2026-08-28 02:47:02.138Z navigate
- url: http://localhost:3000/dashboard
- via: pushState

## 2026-08-28 02:47:02.333Z console.warn
- text: [Perf] Worker took 131.9ms (target <50ms)

## 2026-08-28 02:47:21.022Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Markets"}

## 2026-08-28 02:47:21.022Z navigate
- url: http://localhost:3000/dashboard#markets
- via: pushState

## 2026-08-28 02:47:22.558Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"AI Signals"}

## 2026-08-28 02:47:22.558Z navigate
- url: http://localhost:3000/dashboard#signals
- via: pushState

## 2026-08-28 02:47:23.941Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"AI Analysis"}

## 2026-08-28 02:47:23.941Z navigate
- url: http://localhost:3000/dashboard#analysis
- via: pushState

## 2026-08-28 02:47:24.918Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Trading"}

## 2026-08-28 02:47:24.918Z navigate
- url: http://localhost:3000/dashboard#trading
- via: pushState

## 2026-08-28 02:47:24.944Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/oracle-trader-pro/candles?symbol=BTC-USD&interval=900&limit=160
- status: 500
- statusText: Internal Server Error
- durationMs: 5

## 2026-08-28 02:47:24.944Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/oracle-trader-pro/positions?symbol=BTC-USD
- status: 500
- statusText: Internal Server Error
- durationMs: 5

## 2026-08-28 02:47:24.944Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/oracle-trader-pro/candles?symbol=BTC-USD&interval=900&limit=160: 

## 2026-08-28 02:47:24.944Z console.error
- text: 
    Failed to load candles: Error: HTTP 500
        at http://localhost:3000/src/views/TradingView.jsx:231:15

## 2026-08-28 02:47:24.944Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/oracle-trader-pro/positions?symbol=BTC-USD: 

## 2026-08-28 02:47:24.944Z console.error
- text: 
    Failed to load positions: Error: HTTP 500
        at http://localhost:3000/src/views/TradingView.jsx:265:15

## 2026-08-28 02:47:25.808Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Portfolio"}

## 2026-08-28 02:47:25.808Z navigate
- url: http://localhost:3000/dashboard#portfolio
- via: pushState

## 2026-08-28 02:47:25.830Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/user/balance
- status: 500
- statusText: Internal Server Error
- durationMs: 3

## 2026-08-28 02:47:25.830Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/user/balance: 

## 2026-08-28 02:47:26.896Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"AI Analysis"}

## 2026-08-28 02:47:26.896Z navigate
- url: http://localhost:3000/dashboard#analysis
- via: pushState

## 2026-08-28 02:47:28.177Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Trading"}

## 2026-08-28 02:47:28.177Z navigate
- url: http://localhost:3000/dashboard#trading
- via: pushState

## 2026-08-28 02:47:28.193Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/oracle-trader-pro/candles?symbol=BTC-USD&interval=900&limit=160
- status: 500
- statusText: Internal Server Error
- durationMs: 5

## 2026-08-28 02:47:28.193Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/oracle-trader-pro/candles?symbol=BTC-USD&interval=900&limit=160: 

## 2026-08-28 02:47:28.193Z console.error
- text: 
    Failed to load candles: Error: HTTP 500
        at http://localhost:3000/src/views/TradingView.jsx:231:15

## 2026-08-28 02:47:28.203Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/oracle-trader-pro/positions?symbol=BTC-USD
- status: 500
- statusText: Internal Server Error
- durationMs: 15

## 2026-08-28 02:47:28.204Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/oracle-trader-pro/positions?symbol=BTC-USD: 

## 2026-08-28 02:47:28.204Z console.error
- text: 
    Failed to load positions: Error: HTTP 500
        at http://localhost:3000/src/views/TradingView.jsx:265:15

## 2026-08-28 02:47:31.107Z click
- element: {"tag":"div","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"BTC67,245+2.3%ETH3,512+1.8%SOL182.4+4.1%XRP0.628-0.9%GOLD2,341+0.4%EUR/USD1.0842-0.1%BTC67,245+2.3%ETH3,512+1.8%SOL182.4+4.1%XRP0.628-0.9%GOLD2,341+0.4%EUR/USD1.0842-0.1%AI LIVE12ms99.9%ENTraderTradingExecute trades with real-time market data and live order placement📊Advanced chart unavailableNo candle data returned for the selected market.Place OrderSideBUYSELLOrder TypeMarketLimitSymbolQuantityBUY NOWOpen PositionsNo open positions — place a trade above to get started"}

## 2026-08-28 02:47:43.364Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/oracle-trader-pro/candles?symbol=BTC-USD&interval=900&limit=160
- status: 500
- statusText: Internal Server Error
- durationMs: 174

## 2026-08-28 02:47:43.364Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/oracle-trader-pro/candles?symbol=BTC-USD&interval=900&limit=160: 

## 2026-08-28 02:47:43.365Z console.error
- text: 
    Failed to load candles: Error: HTTP 500
        at http://localhost:3000/src/views/TradingView.jsx:231:15

## 2026-08-28 02:47:43.371Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/oracle-trader-pro/positions?symbol=BTC-USD
- status: 500
- statusText: Internal Server Error
- durationMs: 180

## 2026-08-28 02:47:43.371Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/oracle-trader-pro/positions?symbol=BTC-USD: 

## 2026-08-28 02:47:43.371Z console.error
- text: 
    Failed to load positions: Error: HTTP 500
        at http://localhost:3000/src/views/TradingView.jsx:265:15

## 2026-08-28 02:47:58.195Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/oracle-trader-pro/candles?symbol=BTC-USD&interval=900&limit=160
- status: 500
- statusText: Internal Server Error
- durationMs: 5

## 2026-08-28 02:47:58.195Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/oracle-trader-pro/candles?symbol=BTC-USD&interval=900&limit=160: 

## 2026-08-28 02:47:58.195Z console.error
- text: 
    Failed to load candles: Error: HTTP 500
        at http://localhost:3000/src/views/TradingView.jsx:231:15

## 2026-08-28 02:47:58.199Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/oracle-trader-pro/positions?symbol=BTC-USD
- status: 500
- statusText: Internal Server Error
- durationMs: 9

## 2026-08-28 02:47:58.200Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/oracle-trader-pro/positions?symbol=BTC-USD: 

## 2026-08-28 02:47:58.200Z console.error
- text: 
    Failed to load positions: Error: HTTP 500
        at http://localhost:3000/src/views/TradingView.jsx:265:15

## 2026-08-28 02:48:14.116Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/oracle-trader-pro/candles?symbol=BTC-USD&interval=900&limit=160
- status: 500
- statusText: Internal Server Error
- durationMs: 3

## 2026-08-28 02:48:14.116Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/oracle-trader-pro/candles?symbol=BTC-USD&interval=900&limit=160: 

## 2026-08-28 02:48:14.116Z console.error
- text: 
    Failed to load candles: Error: HTTP 500
        at http://localhost:3000/src/views/TradingView.jsx:231:15

## 2026-08-28 02:48:14.121Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/oracle-trader-pro/positions?symbol=BTC-USD
- status: 500
- statusText: Internal Server Error
- durationMs: 9

## 2026-08-28 02:48:14.122Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/oracle-trader-pro/positions?symbol=BTC-USD: 

## 2026-08-28 02:48:14.122Z console.error
- text: 
    Failed to load positions: Error: HTTP 500
        at http://localhost:3000/src/views/TradingView.jsx:265:15

## 2026-08-28 02:48:30.319Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/oracle-trader-pro/candles?symbol=BTC-USD&interval=900&limit=160
- status: 500
- statusText: Internal Server Error
- durationMs: 6

## 2026-08-28 02:48:30.320Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/oracle-trader-pro/candles?symbol=BTC-USD&interval=900&limit=160: 

## 2026-08-28 02:48:30.320Z console.error
- text: 
    Failed to load candles: Error: HTTP 500
        at http://localhost:3000/src/views/TradingView.jsx:231:15

## 2026-08-28 02:48:30.320Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/oracle-trader-pro/positions?symbol=BTC-USD
- status: 500
- statusText: Internal Server Error
- durationMs: 6

## 2026-08-28 02:48:30.413Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/oracle-trader-pro/positions?symbol=BTC-USD: 

## 2026-08-28 02:48:30.414Z console.error
- text: 
    Failed to load positions: Error: HTTP 500
        at http://localhost:3000/src/views/TradingView.jsx:265:15

## 2026-08-28 02:48:45.569Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/oracle-trader-pro/candles?symbol=BTC-USD&interval=900&limit=160
- status: 500
- statusText: Internal Server Error
- durationMs: 5

## 2026-08-28 02:48:45.569Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/oracle-trader-pro/positions?symbol=BTC-USD
- status: 500
- statusText: Internal Server Error
- durationMs: 5

## 2026-08-28 02:48:45.569Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/oracle-trader-pro/candles?symbol=BTC-USD&interval=900&limit=160: 

## 2026-08-28 02:48:45.570Z console.error
- text: 
    Failed to load candles: Error: HTTP 500
        at http://localhost:3000/src/views/TradingView.jsx:231:15

## 2026-08-28 02:48:45.570Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/oracle-trader-pro/positions?symbol=BTC-USD: 

## 2026-08-28 02:48:45.570Z console.error
- text: 
    Failed to load positions: Error: HTTP 500
        at http://localhost:3000/src/views/TradingView.jsx:265:15

## 2026-08-28 02:49:01.420Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/oracle-trader-pro/candles?symbol=BTC-USD&interval=900&limit=160
- status: 500
- statusText: Internal Server Error
- durationMs: 6

## 2026-08-28 02:49:01.421Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/oracle-trader-pro/candles?symbol=BTC-USD&interval=900&limit=160: 

## 2026-08-28 02:49:01.421Z console.error
- text: 
    Failed to load candles: Error: HTTP 500
        at http://localhost:3000/src/views/TradingView.jsx:231:15

## 2026-08-28 02:49:01.473Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/oracle-trader-pro/positions?symbol=BTC-USD
- status: 500
- statusText: Internal Server Error
- durationMs: 59

## 2026-08-28 02:49:01.474Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/oracle-trader-pro/positions?symbol=BTC-USD: 

## 2026-08-28 02:49:01.474Z console.error
- text: 
    Failed to load positions: Error: HTTP 500
        at http://localhost:3000/src/views/TradingView.jsx:265:15

## 2026-08-28 02:49:37.119Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/user/balance
- status: 500
- statusText: Internal Server Error
- durationMs: 5

## 2026-08-28 02:49:37.119Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/user/balance: 

## 2026-08-28 02:49:42.272Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/oracle-trader-pro/candles?symbol=BTC-USD&interval=900&limit=160
- status: 500
- statusText: Internal Server Error
- durationMs: 4

## 2026-08-28 02:49:42.272Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/oracle-trader-pro/candles?symbol=BTC-USD&interval=900&limit=160: 

## 2026-08-28 02:49:42.272Z console.error
- text: 
    Failed to load candles: Error: HTTP 500
        at http://localhost:3000/src/views/TradingView.jsx:231:15

## 2026-08-28 02:49:42.326Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/oracle-trader-pro/positions?symbol=BTC-USD
- status: 500
- statusText: Internal Server Error
- durationMs: 58

## 2026-08-28 02:49:42.326Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/oracle-trader-pro/positions?symbol=BTC-USD: 

## 2026-08-28 02:49:42.326Z console.error
- text: 
    Failed to load positions: Error: HTTP 500
        at http://localhost:3000/src/views/TradingView.jsx:265:15

## 2026-08-28 02:50:02.482Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/oracle-trader-pro/candles?symbol=BTC-USD&interval=900&limit=160
- status: 500
- statusText: Internal Server Error
- durationMs: 18

## 2026-08-28 02:50:02.482Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/oracle-trader-pro/positions?symbol=BTC-USD
- status: 500
- statusText: Internal Server Error
- durationMs: 18

## 2026-08-28 02:50:02.483Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/oracle-trader-pro/candles?symbol=BTC-USD&interval=900&limit=160: 

## 2026-08-28 02:50:02.483Z console.error
- text: 
    Failed to load candles: Error: HTTP 500
        at http://localhost:3000/src/views/TradingView.jsx:231:15

## 2026-08-28 02:50:02.483Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/oracle-trader-pro/positions?symbol=BTC-USD: 

## 2026-08-28 02:50:02.483Z console.error
- text: 
    Failed to load positions: Error: HTTP 500
        at http://localhost:3000/src/views/TradingView.jsx:265:15

## 2026-08-28 03:13:18.341Z load
- url: http://localhost:3000/

## 2026-08-28 03:13:18.683Z navigate
- url: http://localhost:3000/
- via: replaceState

## 2026-08-28 03:13:19.329Z network.error
- method: GET
- url: http://localhost:3000/hcgi/platform/api/collections/_integratedAiMessages/records?page=1&perPage=500&skipTotal=1&sort=created
- status: 500
- statusText: Internal Server Error
- durationMs: 472

## 2026-08-28 03:13:19.330Z network.error
- method: GET
- url: http://localhost:3000/hcgi/platform/api/collections/bot_account_balance/records?page=1&perPage=1&filter=userId%20%3D%20%22k3atxfk5yxgefz2%22&sort=-created
- status: 500
- statusText: Internal Server Error
- durationMs: 471

## 2026-08-28 03:13:19.330Z network.error
- method: GET
- url: http://localhost:3000/hcgi/platform/api/collections/bot_portfolio/records?page=1&perPage=20&filter=userId%20%3D%20%22k3atxfk5yxgefz2%22&sort=-created
- status: 500
- statusText: Internal Server Error
- durationMs: 471

## 2026-08-28 03:13:19.330Z network.error
- method: GET
- url: http://localhost:3000/hcgi/platform/api/collections/trades/records?page=1&perPage=10&filter=userId%20%3D%20%22k3atxfk5yxgefz2%22&sort=-created
- status: 500
- statusText: Internal Server Error
- durationMs: 470

## 2026-08-28 03:13:19.330Z network.error
- method: GET
- url: http://localhost:3000/hcgi/platform/api/collections/oracle_credentials/records?page=1&perPage=1&filter=owner%20%3D%20%22k3atxfk5yxgefz2%22&skipTotal=1
- status: 500
- statusText: Internal Server Error
- durationMs: 470

## 2026-08-28 03:13:19.330Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/ecommerce/subscriptions
- status: 500
- statusText: Internal Server Error
- durationMs: 458

## 2026-08-28 03:13:19.330Z network.error
- method: GET
- url: http://localhost:3000/hcgi/platform/api/collections/oracle_credentials/records?page=1&perPage=1&filter=owner%20%3D%20%22k3atxfk5yxgefz2%22&skipTotal=1
- status: 500
- statusText: Internal Server Error
- durationMs: 458

## 2026-08-28 03:13:19.340Z console.error
- text: Fetch error from http://localhost:3000/hcgi/platform/api/collections/_integratedAiMessages/records?page=1&perPage=500&skipTotal=1&sort=created: 

## 2026-08-28 03:13:19.342Z console.error
- text: Fetch error from http://localhost:3000/hcgi/platform/api/collections/bot_account_balance/records?page=1&perPage=1&filter=userId%20%3D%20%22k3atxfk5yxgefz2%22&sort=-created: 

## 2026-08-28 03:13:19.343Z console.error
- text: Fetch error from http://localhost:3000/hcgi/platform/api/collections/bot_portfolio/records?page=1&perPage=20&filter=userId%20%3D%20%22k3atxfk5yxgefz2%22&sort=-created: 

## 2026-08-28 03:13:19.343Z console.error
- text: Fetch error from http://localhost:3000/hcgi/platform/api/collections/trades/records?page=1&perPage=10&filter=userId%20%3D%20%22k3atxfk5yxgefz2%22&sort=-created: 

## 2026-08-28 03:13:19.343Z console.error
- text: Fetch error from http://localhost:3000/hcgi/platform/api/collections/oracle_credentials/records?page=1&perPage=1&filter=owner%20%3D%20%22k3atxfk5yxgefz2%22&skipTotal=1: 

## 2026-08-28 03:13:19.343Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/ecommerce/subscriptions: 

## 2026-08-28 03:13:19.344Z console.error
- text: 
    Failed to fetch subscriptions: Error: Failed to fetch subscriptions: 500
        at getUserSubscriptions (http://localhost:3000/src/api/InternalEcommerceSubscriptionsApi.js:29:9)
        at async SubscriptionAuthProvider.fetchSubscriptionsRef.current (http://localhost:3000/src/contexts/SubscriptionAuthContext.jsx:20:19)

## 2026-08-28 03:13:19.344Z console.error
- text: Fetch error from http://localhost:3000/hcgi/platform/api/collections/oracle_credentials/records?page=1&perPage=1&filter=owner%20%3D%20%22k3atxfk5yxgefz2%22&skipTotal=1: 

## 2026-08-28 03:13:19.659Z console.warn
- text: [Perf] Low FPS detected: 25

## 2026-08-28 03:13:22.519Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":" KONT PA OU"}

## 2026-08-28 03:13:22.520Z navigate
- url: http://localhost:3000/dashboard/oracle-trader-pro
- via: pushState

## 2026-08-28 03:13:22.786Z console.warn
- text: [Perf] Low FPS detected: 51

## 2026-08-28 03:13:22.911Z network.error
- method: GET
- url: http://localhost:3000/hcgi/platform/api/collections/_integratedAiMessages/records?page=1&perPage=500&skipTotal=1&sort=created
- status: 500
- statusText: Internal Server Error
- durationMs: 138

## 2026-08-28 03:13:22.911Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/health
- status: 500
- statusText: Internal Server Error
- durationMs: 138

## 2026-08-28 03:13:22.911Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/bot/status
- status: 500
- statusText: Internal Server Error
- durationMs: 137

## 2026-08-28 03:13:22.912Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/oracle-trader-pro/trades
- status: 500
- statusText: Internal Server Error
- durationMs: 137

## 2026-08-28 03:13:22.922Z console.error
- text: Fetch error from http://localhost:3000/hcgi/platform/api/collections/_integratedAiMessages/records?page=1&perPage=500&skipTotal=1&sort=created: 

## 2026-08-28 03:13:22.922Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/health: 

## 2026-08-28 03:13:22.923Z console.warn
- text: [useAIConnection] Backend unreachable (500). Retry 1/8 in 1000ms

## 2026-08-28 03:13:22.923Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/bot/status: 

## 2026-08-28 03:13:22.923Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/oracle-trader-pro/trades: 

## 2026-08-28 03:13:23.016Z console.warn
- text: [Perf] Worker took 347.7ms (target <50ms)

## 2026-08-28 03:13:23.470Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/user/balance
- status: 500
- statusText: Internal Server Error
- durationMs: 37

## 2026-08-28 03:13:23.473Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/user/balance: 

## 2026-08-28 03:13:23.792Z console.warn
- text: [Perf] Low FPS detected: 52

## 2026-08-28 03:13:23.968Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/health
- status: 500
- statusText: Internal Server Error
- durationMs: 15

## 2026-08-28 03:13:23.971Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/health: 

## 2026-08-28 03:13:23.972Z console.warn
- text: [useAIConnection] Backend unreachable (500). Retry 2/8 in 2000ms

## 2026-08-28 03:13:25.990Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/health
- status: 500
- statusText: Internal Server Error
- durationMs: 17

## 2026-08-28 03:13:25.990Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/health: 

## 2026-08-28 03:13:25.991Z console.warn
- text: [useAIConnection] Backend unreachable (500). Retry 3/8 in 4000ms

## 2026-08-28 03:13:30.001Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/health
- status: 500
- statusText: Internal Server Error
- durationMs: 7

## 2026-08-28 03:13:30.001Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/health: 

## 2026-08-28 03:13:30.001Z console.warn
- text: [useAIConnection] Backend unreachable (500). Retry 4/8 in 8000ms

## 2026-08-28 03:13:31.000Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Dashboard"}

## 2026-08-28 03:13:31.001Z navigate
- url: http://localhost:3000/dashboard
- via: pushState

## 2026-08-28 03:13:32.663Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Markets"}

## 2026-08-28 03:13:32.664Z navigate
- url: http://localhost:3000/dashboard#markets
- via: pushState

## 2026-08-28 03:13:38.008Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/health
- status: 500
- statusText: Internal Server Error
- durationMs: 6

## 2026-08-28 03:13:38.009Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/health: 

## 2026-08-28 03:13:38.009Z console.warn
- text: [useAIConnection] Backend unreachable (500). Retry 5/8 in 16000ms

## 2026-08-28 03:13:54.020Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/health
- status: 500
- statusText: Internal Server Error
- durationMs: 9

## 2026-08-28 03:13:54.020Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/health: 

## 2026-08-28 03:13:54.020Z console.warn
- text: [useAIConnection] Backend unreachable (500). Retry 6/8 in 30000ms

## 2026-08-28 03:14:03.564Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Orders"}

## 2026-08-28 03:14:03.565Z navigate
- url: http://localhost:3000/dashboard#orders
- via: pushState

## 2026-08-28 03:14:03.649Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Orders"}

## 2026-08-28 03:14:03.649Z navigate
- url: http://localhost:3000/dashboard#orders
- via: replaceState

## 2026-08-28 03:14:03.657Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 53

## 2026-08-28 03:14:03.663Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:14:03.855Z click
- element: {"tag":"a","role":null,"ariaLabel":null,"name":null,"type":null,"id":null,"placeholder":null,"label":null,"value":null,"valueLength":0,"text":"Orders"}

## 2026-08-28 03:14:03.856Z navigate
- url: http://localhost:3000/dashboard#orders
- via: replaceState

## 2026-08-28 03:14:22.787Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/user/balance
- status: 500
- statusText: Internal Server Error
- durationMs: 9

## 2026-08-28 03:14:22.787Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/user/balance: 

## 2026-08-28 03:14:24.030Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/health
- status: 500
- statusText: Internal Server Error
- durationMs: 7

## 2026-08-28 03:14:24.030Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/health: 

## 2026-08-28 03:14:24.030Z console.warn
- text: [useAIConnection] Backend unreachable (500). Retry 7/8 in 30000ms

## 2026-08-28 03:14:33.611Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 5

## 2026-08-28 03:14:33.612Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:14:54.042Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/health
- status: 500
- statusText: Internal Server Error
- durationMs: 10

## 2026-08-28 03:14:54.042Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/health: 

## 2026-08-28 03:14:54.043Z console.warn
- text: [useAIConnection] Backend unreachable (500). Retry 8/8 in 30000ms

## 2026-08-28 03:15:03.616Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 8

## 2026-08-28 03:15:03.616Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:15:24.067Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/health
- status: 500
- statusText: Internal Server Error
- durationMs: 22

## 2026-08-28 03:15:24.067Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/health: 

## 2026-08-28 03:15:24.068Z console.error
- text: [useAIConnection] Max reconnect attempts reached. Giving up.

## 2026-08-28 03:15:33.644Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 33

## 2026-08-28 03:15:33.651Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:16:03.622Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 14

## 2026-08-28 03:16:03.622Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:16:29.517Z console.warn
- text: [Perf] Low FPS detected: 42

## 2026-08-28 03:16:33.899Z load
- url: http://localhost:3000/dashboard#orders

## 2026-08-28 03:16:38.882Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 1097

## 2026-08-28 03:16:38.884Z network.error
- method: GET
- url: http://localhost:3000/hcgi/platform/api/collections/_integratedAiMessages/records?page=1&perPage=500&skipTotal=1&sort=created
- status: 500
- statusText: Internal Server Error
- durationMs: 1057

## 2026-08-28 03:16:38.884Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/health
- status: 500
- statusText: Internal Server Error
- durationMs: 1051

## 2026-08-28 03:16:38.884Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/bot/status
- status: 500
- statusText: Internal Server Error
- durationMs: 1015

## 2026-08-28 03:16:38.885Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/oracle-trader-pro/trades
- status: 500
- statusText: Internal Server Error
- durationMs: 1014

## 2026-08-28 03:16:38.885Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/ecommerce/subscriptions
- status: 500
- statusText: Internal Server Error
- durationMs: 1002

## 2026-08-28 03:16:38.923Z network.error
- method: GET
- url: http://localhost:3000/hcgi/platform/api/collections/oracle_credentials/records?page=1&perPage=1&filter=owner%20%3D%20%22k3atxfk5yxgefz2%22&skipTotal=1
- status: 500
- statusText: Internal Server Error
- durationMs: 1002

## 2026-08-28 03:16:38.926Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:16:38.933Z console.error
- text: Fetch error from http://localhost:3000/hcgi/platform/api/collections/_integratedAiMessages/records?page=1&perPage=500&skipTotal=1&sort=created: 

## 2026-08-28 03:16:38.935Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/health: 

## 2026-08-28 03:16:38.970Z console.warn
- text: [useAIConnection] Backend unreachable (500). Retry 1/8 in 1000ms

## 2026-08-28 03:16:38.971Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/bot/status: 

## 2026-08-28 03:16:38.975Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/oracle-trader-pro/trades: 

## 2026-08-28 03:16:38.976Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/ecommerce/subscriptions: 

## 2026-08-28 03:16:38.978Z console.error
- text: 
    Failed to fetch subscriptions: Error: Failed to fetch subscriptions: 500
        at getUserSubscriptions (http://localhost:3000/src/api/InternalEcommerceSubscriptionsApi.js:29:9)
        at async SubscriptionAuthProvider.fetchSubscriptionsRef.current (http://localhost:3000/src/contexts/SubscriptionAuthContext.jsx:20:19)

## 2026-08-28 03:16:38.980Z console.error
- text: Fetch error from http://localhost:3000/hcgi/platform/api/collections/oracle_credentials/records?page=1&perPage=1&filter=owner%20%3D%20%22k3atxfk5yxgefz2%22&skipTotal=1: 

## 2026-08-28 03:17:54.169Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/user/balance
- status: 500
- statusText: Internal Server Error
- durationMs: 713

## 2026-08-28 03:17:54.170Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/user/balance: 

## 2026-08-28 03:17:54.185Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/health
- status: 500
- statusText: Internal Server Error
- durationMs: 698

## 2026-08-28 03:17:54.185Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 637

## 2026-08-28 03:17:54.185Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/health: 

## 2026-08-28 03:17:54.186Z console.warn
- text: [useAIConnection] Backend unreachable (500). Retry 2/8 in 2000ms

## 2026-08-28 03:17:54.186Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:17:55.011Z console.warn
- text: [Perf] Low FPS detected: 54

## 2026-08-28 03:17:56.197Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/health
- status: 500
- statusText: Internal Server Error
- durationMs: 10

## 2026-08-28 03:17:56.197Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/health: 

## 2026-08-28 03:17:56.198Z console.warn
- text: [useAIConnection] Backend unreachable (500). Retry 3/8 in 4000ms

## 2026-08-28 03:18:00.236Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/health
- status: 500
- statusText: Internal Server Error
- durationMs: 37

## 2026-08-28 03:18:00.236Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/health: 

## 2026-08-28 03:18:00.236Z console.warn
- text: [useAIConnection] Backend unreachable (500). Retry 4/8 in 8000ms

## 2026-08-28 03:18:08.261Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/health
- status: 500
- statusText: Internal Server Error
- durationMs: 22

## 2026-08-28 03:18:08.262Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/health: 

## 2026-08-28 03:18:08.263Z console.warn
- text: [useAIConnection] Backend unreachable (500). Retry 5/8 in 16000ms

## 2026-08-28 03:18:15.147Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 16

## 2026-08-28 03:18:15.147Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:18:24.272Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/health
- status: 500
- statusText: Internal Server Error
- durationMs: 8

## 2026-08-28 03:18:24.273Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/health: 

## 2026-08-28 03:18:24.273Z console.warn
- text: [useAIConnection] Backend unreachable (500). Retry 6/8 in 30000ms

## 2026-08-28 03:18:45.149Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 17

## 2026-08-28 03:18:45.149Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:18:53.453Z console.warn
- text: [Perf] Low FPS detected: 42

## 2026-08-28 03:18:54.355Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/health
- status: 500
- statusText: Internal Server Error
- durationMs: 80

## 2026-08-28 03:18:54.356Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/health: 

## 2026-08-28 03:18:54.356Z console.warn
- text: [useAIConnection] Backend unreachable (500). Retry 7/8 in 30000ms

## 2026-08-28 03:18:56.481Z console.warn
- text: [Perf] Low FPS detected: 49

## 2026-08-28 03:18:57.502Z console.warn
- text: [Perf] Low FPS detected: 26

## 2026-08-28 03:18:58.520Z console.warn
- text: [Perf] Low FPS detected: 34

## 2026-08-28 03:18:59.522Z console.warn
- text: [Perf] Low FPS detected: 35

## 2026-08-28 03:19:00.543Z console.warn
- text: [Perf] Low FPS detected: 33

## 2026-08-28 03:19:01.544Z console.warn
- text: [Perf] Low FPS detected: 29

## 2026-08-28 03:19:02.546Z console.warn
- text: [Perf] Low FPS detected: 42

## 2026-08-28 03:19:03.554Z console.warn
- text: [Perf] Low FPS detected: 38

## 2026-08-28 03:19:04.556Z console.warn
- text: [Perf] Low FPS detected: 36

## 2026-08-28 03:19:05.557Z console.warn
- text: [Perf] Low FPS detected: 35

## 2026-08-28 03:19:06.560Z console.warn
- text: [Perf] Low FPS detected: 41

## 2026-08-28 03:19:07.576Z console.warn
- text: [Perf] Low FPS detected: 30

## 2026-08-28 03:19:08.596Z console.warn
- text: [Perf] Low FPS detected: 30

## 2026-08-28 03:19:09.602Z console.warn
- text: [Perf] Low FPS detected: 44

## 2026-08-28 03:19:12.790Z console.warn
- text: [Perf] Low FPS detected: 48

## 2026-08-28 03:19:14.796Z console.warn
- text: [Perf] Low FPS detected: 44

## 2026-08-28 03:19:16.319Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 1187

## 2026-08-28 03:19:16.320Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:19:20.816Z console.warn
- text: [Perf] Low FPS detected: 43

## 2026-08-28 03:19:21.853Z console.warn
- text: [Perf] Low FPS detected: 45

## 2026-08-28 03:19:22.869Z console.warn
- text: [Perf] Low FPS detected: 47

## 2026-08-28 03:19:23.893Z console.warn
- text: [Perf] Low FPS detected: 54

## 2026-08-28 03:19:24.461Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/health
- status: 500
- statusText: Internal Server Error
- durationMs: 104

## 2026-08-28 03:19:24.461Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/health: 

## 2026-08-28 03:19:24.473Z console.warn
- text: [useAIConnection] Backend unreachable (500). Retry 8/8 in 30000ms

## 2026-08-28 03:19:24.908Z console.warn
- text: [Perf] Low FPS detected: 51

## 2026-08-28 03:19:34.990Z console.warn
- text: [Perf] Low FPS detected: 48

## 2026-08-28 03:19:36.006Z console.warn
- text: [Perf] Low FPS detected: 49

## 2026-08-28 03:19:39.013Z console.warn
- text: [Perf] Low FPS detected: 54

## 2026-08-28 03:19:45.265Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 122

## 2026-08-28 03:19:45.265Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:19:54.544Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/health
- status: 500
- statusText: Internal Server Error
- durationMs: 64

## 2026-08-28 03:19:54.544Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/health: 

## 2026-08-28 03:19:54.555Z console.error
- text: [useAIConnection] Max reconnect attempts reached. Giving up.

## 2026-08-28 03:20:15.139Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 5

## 2026-08-28 03:20:15.139Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:20:15.194Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/user/balance
- status: 500
- statusText: Internal Server Error
- durationMs: 7

## 2026-08-28 03:20:15.194Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/user/balance: 

## 2026-08-28 03:20:45.148Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 14

## 2026-08-28 03:20:45.148Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:20:48.573Z console.warn
- text: [Perf] Low FPS detected: 54

## 2026-08-28 03:21:15.155Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 18

## 2026-08-28 03:21:15.155Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:21:45.142Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 7

## 2026-08-28 03:21:45.143Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:22:15.146Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 9

## 2026-08-28 03:22:15.146Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:22:45.142Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 5

## 2026-08-28 03:22:45.142Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:22:52.548Z console.warn
- text: [Perf] Low FPS detected: 54

## 2026-08-28 03:23:15.147Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 10

## 2026-08-28 03:23:15.147Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:23:43.986Z console.warn
- text: [Perf] Low FPS detected: 41

## 2026-08-28 03:23:45.166Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 28

## 2026-08-28 03:23:45.166Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:24:01.138Z console.warn
- text: [Perf] Low FPS detected: 46

## 2026-08-28 03:24:03.158Z console.warn
- text: [Perf] Low FPS detected: 22

## 2026-08-28 03:24:15.165Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 26

## 2026-08-28 03:24:15.165Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:24:15.210Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/user/balance
- status: 500
- statusText: Internal Server Error
- durationMs: 9

## 2026-08-28 03:24:15.211Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/user/balance: 

## 2026-08-28 03:24:28.529Z console.warn
- text: [Perf] Low FPS detected: 39

## 2026-08-28 03:24:45.182Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 43

## 2026-08-28 03:24:45.182Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:24:56.657Z console.warn
- text: [Perf] Low FPS detected: 51

## 2026-08-28 03:25:15.164Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 23

## 2026-08-28 03:25:15.165Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:25:24.745Z console.warn
- text: [Perf] Low FPS detected: 53

## 2026-08-28 03:25:45.155Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 15

## 2026-08-28 03:25:45.155Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:26:15.149Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 8

## 2026-08-28 03:26:15.149Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:26:45.151Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 10

## 2026-08-28 03:26:45.151Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:27:15.152Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 10

## 2026-08-28 03:27:15.152Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:27:45.156Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 13

## 2026-08-28 03:27:45.156Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:28:15.148Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 5

## 2026-08-28 03:28:15.148Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:28:45.150Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 5

## 2026-08-28 03:28:45.150Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:29:15.151Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 6

## 2026-08-28 03:29:15.151Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:29:15.235Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/user/balance
- status: 500
- statusText: Internal Server Error
- durationMs: 5

## 2026-08-28 03:29:15.235Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/user/balance: 

## 2026-08-28 03:29:25.787Z console.warn
- text: [Perf] Low FPS detected: 47

## 2026-08-28 03:29:45.194Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 48

## 2026-08-28 03:29:45.194Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:30:15.153Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 7

## 2026-08-28 03:30:15.153Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:30:40.410Z console.warn
- text: [Perf] Low FPS detected: 47

## 2026-08-28 03:30:45.175Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 26

## 2026-08-28 03:30:45.175Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:31:15.156Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 9

## 2026-08-28 03:31:15.157Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:31:25.739Z console.warn
- text: [Perf] Low FPS detected: 48

## 2026-08-28 03:31:26.739Z console.warn
- text: [Perf] Low FPS detected: 42

## 2026-08-28 03:31:27.757Z console.warn
- text: [Perf] Low FPS detected: 54

## 2026-08-28 03:31:28.775Z console.warn
- text: [Perf] Low FPS detected: 49

## 2026-08-28 03:31:29.782Z console.warn
- text: [Perf] Low FPS detected: 53

## 2026-08-28 03:31:31.818Z console.warn
- text: [Perf] Low FPS detected: 45

## 2026-08-28 03:31:32.835Z console.warn
- text: [Perf] Low FPS detected: 53

## 2026-08-28 03:31:34.850Z console.warn
- text: [Perf] Low FPS detected: 41

## 2026-08-28 03:31:45.170Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 12

## 2026-08-28 03:31:45.170Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:32:15.167Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 19

## 2026-08-28 03:32:15.167Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:32:45.158Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 9

## 2026-08-28 03:32:45.159Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:33:15.161Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 10

## 2026-08-28 03:33:15.161Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:33:45.157Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 6

## 2026-08-28 03:33:45.157Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:34:15.156Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 5

## 2026-08-28 03:34:15.156Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:34:15.251Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/user/balance
- status: 500
- statusText: Internal Server Error
- durationMs: 8

## 2026-08-28 03:34:15.251Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/user/balance: 

## 2026-08-28 03:34:45.162Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 10

## 2026-08-28 03:34:45.162Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:35:15.158Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 6

## 2026-08-28 03:35:15.159Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:35:45.162Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 9

## 2026-08-28 03:35:45.162Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:36:15.161Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 7

## 2026-08-28 03:36:15.161Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:36:45.179Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 24

## 2026-08-28 03:36:45.180Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:36:46.301Z console.warn
- text: [Perf] Low FPS detected: 54

## 2026-08-28 03:36:54.324Z console.warn
- text: [Perf] Low FPS detected: 52

## 2026-08-28 03:36:58.337Z console.warn
- text: [Perf] Low FPS detected: 42

## 2026-08-28 03:36:59.338Z console.warn
- text: [Perf] Low FPS detected: 54

## 2026-08-28 03:37:00.412Z console.warn
- text: [Perf] Low FPS detected: 40

## 2026-08-28 03:37:01.449Z console.warn
- text: [Perf] Low FPS detected: 22

## 2026-08-28 03:37:02.479Z console.warn
- text: [Perf] Low FPS detected: 36

## 2026-08-28 03:37:03.499Z console.warn
- text: [Perf] Low FPS detected: 32

## 2026-08-28 03:37:04.570Z console.warn
- text: [Perf] Low FPS detected: 40

## 2026-08-28 03:37:05.577Z console.warn
- text: [Perf] Low FPS detected: 46

## 2026-08-28 03:37:06.594Z console.warn
- text: [Perf] Low FPS detected: 43

## 2026-08-28 03:37:07.600Z console.warn
- text: [Perf] Low FPS detected: 45

## 2026-08-28 03:37:08.600Z console.warn
- text: [Perf] Low FPS detected: 51

## 2026-08-28 03:37:09.619Z console.warn
- text: [Perf] Low FPS detected: 50

## 2026-08-28 03:37:10.626Z console.warn
- text: [Perf] Low FPS detected: 54

## 2026-08-28 03:37:11.627Z console.warn
- text: [Perf] Low FPS detected: 54

## 2026-08-28 03:37:12.631Z console.warn
- text: [Perf] Low FPS detected: 50

## 2026-08-28 03:37:13.637Z console.warn
- text: [Perf] Low FPS detected: 52

## 2026-08-28 03:37:14.640Z console.warn
- text: [Perf] Low FPS detected: 44

## 2026-08-28 03:37:15.643Z console.warn
- text: [Perf] Low FPS detected: 44

## 2026-08-28 03:37:17.467Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 2311

## 2026-08-28 03:37:17.467Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:37:17.916Z console.warn
- text: [Perf] Low FPS detected: 38

## 2026-08-28 03:37:18.922Z console.warn
- text: [Perf] Low FPS detected: 50

## 2026-08-28 03:37:19.923Z console.warn
- text: [Perf] Low FPS detected: 46

## 2026-08-28 03:37:20.926Z console.warn
- text: [Perf] Low FPS detected: 47

## 2026-08-28 03:37:21.944Z console.warn
- text: [Perf] Low FPS detected: 37

## 2026-08-28 03:37:22.949Z console.warn
- text: [Perf] Low FPS detected: 35

## 2026-08-28 03:37:24.034Z console.warn
- text: [Perf] Low FPS detected: 36

## 2026-08-28 03:37:25.037Z console.warn
- text: [Perf] Low FPS detected: 44

## 2026-08-28 03:37:26.039Z console.warn
- text: [Perf] Low FPS detected: 45

## 2026-08-28 03:37:30.139Z console.warn
- text: [Perf] Low FPS detected: 53

## 2026-08-28 03:37:34.150Z console.warn
- text: [Perf] Low FPS detected: 48

## 2026-08-28 03:37:36.174Z console.warn
- text: [Perf] Low FPS detected: 42

## 2026-08-28 03:37:37.176Z console.warn
- text: [Perf] Low FPS detected: 49

## 2026-08-28 03:37:38.177Z console.warn
- text: [Perf] Low FPS detected: 53

## 2026-08-28 03:37:40.183Z console.warn
- text: [Perf] Low FPS detected: 52

## 2026-08-28 03:37:41.185Z console.warn
- text: [Perf] Low FPS detected: 53

## 2026-08-28 03:37:42.208Z console.warn
- text: [Perf] Low FPS detected: 52

## 2026-08-28 03:37:43.375Z console.warn
- text: [Perf] Low FPS detected: 38

## 2026-08-28 03:37:44.375Z console.warn
- text: [Perf] Low FPS detected: 41

## 2026-08-28 03:37:45.321Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 165

## 2026-08-28 03:37:45.321Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:37:45.378Z console.warn
- text: [Perf] Low FPS detected: 53

## 2026-08-28 03:37:46.378Z console.warn
- text: [Perf] Low FPS detected: 36

## 2026-08-28 03:37:47.384Z console.warn
- text: [Perf] Low FPS detected: 49

## 2026-08-28 03:37:48.418Z console.warn
- text: [Perf] Low FPS detected: 39

## 2026-08-28 03:37:49.439Z console.warn
- text: [Perf] Low FPS detected: 52

## 2026-08-28 03:37:51.444Z console.warn
- text: [Perf] Low FPS detected: 49

## 2026-08-28 03:37:52.447Z console.warn
- text: [Perf] Low FPS detected: 49

## 2026-08-28 03:37:53.451Z console.warn
- text: [Perf] Low FPS detected: 50

## 2026-08-28 03:37:54.454Z console.warn
- text: [Perf] Low FPS detected: 49

## 2026-08-28 03:37:55.477Z console.warn
- text: [Perf] Low FPS detected: 47

## 2026-08-28 03:37:56.483Z console.warn
- text: [Perf] Low FPS detected: 51

## 2026-08-28 03:37:57.502Z console.warn
- text: [Perf] Low FPS detected: 52

## 2026-08-28 03:37:58.510Z console.warn
- text: [Perf] Low FPS detected: 45

## 2026-08-28 03:37:59.528Z console.warn
- text: [Perf] Low FPS detected: 52

## 2026-08-28 03:38:00.530Z console.warn
- text: [Perf] Low FPS detected: 49

## 2026-08-28 03:38:01.535Z console.warn
- text: [Perf] Low FPS detected: 39

## 2026-08-28 03:38:02.557Z console.warn
- text: [Perf] Low FPS detected: 50

## 2026-08-28 03:38:03.581Z console.warn
- text: [Perf] Low FPS detected: 47

## 2026-08-28 03:38:04.586Z console.warn
- text: [Perf] Low FPS detected: 45

## 2026-08-28 03:38:05.608Z console.warn
- text: [Perf] Low FPS detected: 49

## 2026-08-28 03:38:06.609Z console.warn
- text: [Perf] Low FPS detected: 46

## 2026-08-28 03:38:07.612Z console.warn
- text: [Perf] Low FPS detected: 45

## 2026-08-28 03:38:08.618Z console.warn
- text: [Perf] Low FPS detected: 51

## 2026-08-28 03:38:09.622Z console.warn
- text: [Perf] Low FPS detected: 48

## 2026-08-28 03:38:10.640Z console.warn
- text: [Perf] Low FPS detected: 51

## 2026-08-28 03:38:11.642Z console.warn
- text: [Perf] Low FPS detected: 50

## 2026-08-28 03:38:12.645Z console.warn
- text: [Perf] Low FPS detected: 48

## 2026-08-28 03:38:13.648Z console.warn
- text: [Perf] Low FPS detected: 44

## 2026-08-28 03:38:14.652Z console.warn
- text: [Perf] Low FPS detected: 50

## 2026-08-28 03:38:15.207Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 48

## 2026-08-28 03:38:15.207Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:38:15.652Z console.warn
- text: [Perf] Low FPS detected: 43

## 2026-08-28 03:38:17.676Z console.warn
- text: [Perf] Low FPS detected: 39

## 2026-08-28 03:38:20.685Z console.warn
- text: [Perf] Low FPS detected: 53

## 2026-08-28 03:38:21.687Z console.warn
- text: [Perf] Low FPS detected: 52

## 2026-08-28 03:38:23.691Z console.warn
- text: [Perf] Low FPS detected: 53

## 2026-08-28 03:38:24.744Z console.warn
- text: [Perf] Low FPS detected: 53

## 2026-08-28 03:38:25.761Z console.warn
- text: [Perf] Low FPS detected: 45

## 2026-08-28 03:38:26.765Z console.warn
- text: [Perf] Low FPS detected: 29

## 2026-08-28 03:38:27.768Z console.warn
- text: [Perf] Low FPS detected: 48

## 2026-08-28 03:38:45.344Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 186

## 2026-08-28 03:38:45.344Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:38:47.862Z console.warn
- text: [Perf] Low FPS detected: 53

## 2026-08-28 03:38:50.887Z console.warn
- text: [Perf] Low FPS detected: 47

## 2026-08-28 03:38:51.907Z console.warn
- text: [Perf] Low FPS detected: 54

## 2026-08-28 03:38:53.912Z console.warn
- text: [Perf] Low FPS detected: 41

## 2026-08-28 03:38:55.921Z console.warn
- text: [Perf] Low FPS detected: 51

## 2026-08-28 03:39:15.181Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 24

## 2026-08-28 03:39:15.182Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:39:34.084Z console.warn
- text: [Perf] Low FPS detected: 50

## 2026-08-28 03:39:37.089Z console.warn
- text: [Perf] Low FPS detected: 54

## 2026-08-28 03:39:45.106Z console.warn
- text: [Perf] Low FPS detected: 44

## 2026-08-28 03:39:45.205Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 36

## 2026-08-28 03:39:45.205Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:39:47.110Z console.warn
- text: [Perf] Low FPS detected: 37

## 2026-08-28 03:39:48.179Z console.warn
- text: [Perf] Low FPS detected: 39

## 2026-08-28 03:39:49.183Z console.warn
- text: [Perf] Low FPS detected: 44

## 2026-08-28 03:39:50.267Z console.warn
- text: [Perf] Low FPS detected: 18

## 2026-08-28 03:39:51.300Z console.warn
- text: [Perf] Low FPS detected: 23

## 2026-08-28 03:39:52.320Z console.warn
- text: [Perf] Low FPS detected: 30

## 2026-08-28 03:39:53.847Z console.warn
- text: [Perf] Low FPS detected: 16

## 2026-08-28 03:39:55.415Z console.warn
- text: [Perf] Low FPS detected: 3

## 2026-08-28 03:39:56.519Z console.warn
- text: [Perf] Low FPS detected: 28

## 2026-08-28 03:39:57.556Z console.warn
- text: [Perf] Low FPS detected: 27

## 2026-08-28 03:39:58.575Z console.warn
- text: [Perf] Low FPS detected: 31

## 2026-08-28 03:39:59.577Z console.warn
- text: [Perf] Low FPS detected: 33

## 2026-08-28 03:40:00.713Z console.warn
- text: [Perf] Low FPS detected: 33

## 2026-08-28 03:40:01.724Z console.warn
- text: [Perf] Low FPS detected: 30

## 2026-08-28 03:40:02.752Z console.warn
- text: [Perf] Low FPS detected: 42

## 2026-08-28 03:40:03.756Z console.warn
- text: [Perf] Low FPS detected: 36

## 2026-08-28 03:40:04.883Z console.warn
- text: [Perf] Low FPS detected: 38

## 2026-08-28 03:40:05.887Z console.warn
- text: [Perf] Low FPS detected: 37

## 2026-08-28 03:40:06.888Z console.warn
- text: [Perf] Low FPS detected: 42

## 2026-08-28 03:40:07.892Z console.warn
- text: [Perf] Low FPS detected: 43

## 2026-08-28 03:40:11.920Z console.warn
- text: [Perf] Low FPS detected: 48

## 2026-08-28 03:40:15.190Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 22

## 2026-08-28 03:40:15.190Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:40:16.949Z console.warn
- text: [Perf] Low FPS detected: 54

## 2026-08-28 03:40:21.977Z console.warn
- text: [Perf] Low FPS detected: 53

## 2026-08-28 03:40:27.117Z console.warn
- text: [Perf] Low FPS detected: 41

## 2026-08-28 03:40:28.151Z console.warn
- text: [Perf] Low FPS detected: 24

## 2026-08-28 03:40:29.168Z console.warn
- text: [Perf] Low FPS detected: 53

## 2026-08-28 03:40:31.177Z console.warn
- text: [Perf] Low FPS detected: 52

## 2026-08-28 03:40:45.300Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 135

## 2026-08-28 03:40:45.300Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:40:53.314Z console.warn
- text: [Perf] Low FPS detected: 40

## 2026-08-28 03:40:55.318Z console.warn
- text: [Perf] Low FPS detected: 44

## 2026-08-28 03:41:13.364Z console.warn
- text: [Perf] Low FPS detected: 46

## 2026-08-28 03:41:15.452Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 286

## 2026-08-28 03:41:15.452Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:41:45.307Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 137

## 2026-08-28 03:41:45.307Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:41:48.479Z console.warn
- text: [Perf] Low FPS detected: 54

## 2026-08-28 03:42:01.501Z console.warn
- text: [Perf] Low FPS detected: 41

## 2026-08-28 03:42:09.532Z console.warn
- text: [Perf] Low FPS detected: 54

## 2026-08-28 03:42:14.539Z console.warn
- text: [Perf] Low FPS detected: 51

## 2026-08-28 03:42:15.679Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 518

## 2026-08-28 03:42:15.679Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:42:21.571Z console.warn
- text: [Perf] Low FPS detected: 54

## 2026-08-28 03:42:22.577Z console.warn
- text: [Perf] Low FPS detected: 52

## 2026-08-28 03:42:24.583Z console.warn
- text: [Perf] Low FPS detected: 50

## 2026-08-28 03:42:28.595Z console.warn
- text: [Perf] Low FPS detected: 50

## 2026-08-28 03:42:29.634Z console.warn
- text: [Perf] Low FPS detected: 48

## 2026-08-28 03:42:30.637Z console.warn
- text: [Perf] Low FPS detected: 40

## 2026-08-28 03:42:31.691Z console.warn
- text: [Perf] Low FPS detected: 46

## 2026-08-28 03:42:33.699Z console.warn
- text: [Perf] Low FPS detected: 54

## 2026-08-28 03:42:32.695Z console.warn
- text: [Perf] Low FPS detected: 47

## 2026-08-28 03:42:34.702Z console.warn
- text: [Perf] Low FPS detected: 39

## 2026-08-28 03:42:35.718Z console.warn
- text: [Perf] Low FPS detected: 46

## 2026-08-28 03:42:37.727Z console.warn
- text: [Perf] Low FPS detected: 44

## 2026-08-28 03:42:44.757Z console.warn
- text: [Perf] Low FPS detected: 48

## 2026-08-28 03:42:45.289Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 125

## 2026-08-28 03:42:45.289Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:42:50.779Z console.warn
- text: [Perf] Low FPS detected: 48

## 2026-08-28 03:42:53.786Z console.warn
- text: [Perf] Low FPS detected: 51

## 2026-08-28 03:42:56.793Z console.warn
- text: [Perf] Low FPS detected: 36

## 2026-08-28 03:43:01.825Z console.warn
- text: [Perf] Low FPS detected: 44

## 2026-08-28 03:43:02.828Z console.warn
- text: [Perf] Low FPS detected: 50

## 2026-08-28 03:43:04.835Z console.warn
- text: [Perf] Low FPS detected: 52

## 2026-08-28 03:43:05.864Z console.warn
- text: [Perf] Low FPS detected: 52

## 2026-08-28 03:43:06.868Z console.warn
- text: [Perf] Low FPS detected: 53

## 2026-08-28 03:43:15.198Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 32

## 2026-08-28 03:43:15.198Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:43:16.904Z console.warn
- text: [Perf] Low FPS detected: 41

## 2026-08-28 03:43:45.327Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 164

## 2026-08-28 03:43:45.328Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:43:49.136Z console.warn
- text: [Perf] Low FPS detected: 53

## 2026-08-28 03:43:50.138Z console.warn
- text: [Perf] Low FPS detected: 53

## 2026-08-28 03:43:53.161Z console.warn
- text: [Perf] Low FPS detected: 49

## 2026-08-28 03:43:56.215Z console.warn
- text: [Perf] Low FPS detected: 48

## 2026-08-28 03:43:57.221Z console.warn
- text: [Perf] Low FPS detected: 53

## 2026-08-28 03:44:14.432Z console.warn
- text: [Perf] Low FPS detected: 39

## 2026-08-28 03:44:15.307Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 142

## 2026-08-28 03:44:15.307Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:44:41.961Z console.warn
- text: [Perf] Low FPS detected: 3

## 2026-08-28 03:44:42.978Z console.warn
- text: [Perf] Low FPS detected: 49

## 2026-08-28 03:44:44.981Z console.warn
- text: [Perf] Low FPS detected: 52

## 2026-08-28 03:44:45.206Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 40

## 2026-08-28 03:44:45.206Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:44:45.982Z console.warn
- text: [Perf] Low FPS detected: 49

## 2026-08-28 03:45:03.024Z console.warn
- text: [Perf] Low FPS detected: 54

## 2026-08-28 03:45:15.195Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 27

## 2026-08-28 03:45:15.196Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:45:18.554Z console.warn
- text: [Perf] Low FPS detected: 35

## 2026-08-28 03:45:45.276Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 111

## 2026-08-28 03:45:45.276Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:46:15.185Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 11

## 2026-08-28 03:46:15.185Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:46:29.926Z console.warn
- text: [Perf] Low FPS detected: 40

## 2026-08-28 03:46:30.939Z console.warn
- text: [Perf] Low FPS detected: 48

## 2026-08-28 03:46:45.189Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 23

## 2026-08-28 03:46:45.190Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:47:15.172Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 5

## 2026-08-28 03:47:15.172Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:47:45.173Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 6

## 2026-08-28 03:47:45.173Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:48:15.173Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 4

## 2026-08-28 03:48:15.173Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:48:45.203Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 5

## 2026-08-28 03:48:45.203Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:49:15.212Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 5

## 2026-08-28 03:49:15.212Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:49:45.216Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 7

## 2026-08-28 03:49:45.216Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:50:15.215Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 4

## 2026-08-28 03:50:15.215Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:50:45.216Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 5

## 2026-08-28 03:50:45.217Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:51:15.223Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 11

## 2026-08-28 03:51:15.223Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:51:45.223Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 10

## 2026-08-28 03:51:45.224Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:52:15.219Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 5

## 2026-08-28 03:52:15.219Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:52:45.224Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 8

## 2026-08-28 03:52:45.224Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:53:15.221Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 6

## 2026-08-28 03:53:15.221Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:53:16.249Z console.warn
- text: [Perf] Low FPS detected: 54

## 2026-08-28 03:53:45.222Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 6

## 2026-08-28 03:53:45.222Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:54:15.228Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 10

## 2026-08-28 03:54:15.228Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:54:45.223Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 5

## 2026-08-28 03:54:45.223Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:55:15.223Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 5

## 2026-08-28 03:55:15.223Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:55:45.227Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 7

## 2026-08-28 03:55:45.227Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:56:15.250Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 27

## 2026-08-28 03:56:15.252Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:56:45.248Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 26

## 2026-08-28 03:56:45.249Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:57:15.229Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 6

## 2026-08-28 03:57:15.229Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:57:45.230Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 7

## 2026-08-28 03:57:45.230Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:58:15.232Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 7

## 2026-08-28 03:58:15.232Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:58:45.231Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 6

## 2026-08-28 03:58:45.231Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:59:15.231Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 5

## 2026-08-28 03:59:15.231Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 03:59:45.233Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 6

## 2026-08-28 03:59:45.233Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 04:00:15.235Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 7

## 2026-08-28 04:00:15.235Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 04:00:45.235Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 5

## 2026-08-28 04:00:45.235Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 04:01:14.476Z console.warn
- text: [Perf] Low FPS detected: 48

## 2026-08-28 04:01:15.259Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 27

## 2026-08-28 04:01:15.259Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 04:01:45.237Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 6

## 2026-08-28 04:01:45.237Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 04:02:15.245Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 13

## 2026-08-28 04:02:15.245Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 04:02:45.241Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 8

## 2026-08-28 04:02:45.241Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 04:03:15.239Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 5

## 2026-08-28 04:03:15.239Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 04:03:45.241Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 6

## 2026-08-28 04:03:45.241Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 04:04:15.241Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 5

## 2026-08-28 04:04:15.242Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 04:04:45.241Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 5

## 2026-08-28 04:04:45.241Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 04:05:15.230Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 4

## 2026-08-28 04:05:15.230Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 04:05:38.562Z console.warn
- text: [Perf] Low FPS detected: 49

## 2026-08-28 04:05:45.227Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 4

## 2026-08-28 04:05:45.227Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 04:06:15.227Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 4

## 2026-08-28 04:06:15.227Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 04:06:45.228Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 3

## 2026-08-28 04:06:45.228Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 04:07:15.228Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 4

## 2026-08-28 04:07:15.228Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 04:07:45.229Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 4

## 2026-08-28 04:07:45.229Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 04:08:15.240Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 14

## 2026-08-28 04:08:15.241Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 04:08:45.232Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/coinbase/fills?limit=60
- status: 500
- statusText: Internal Server Error
- durationMs: 5

## 2026-08-28 04:08:45.232Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/coinbase/fills?limit=60: 

## 2026-08-28 04:10:19.481Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/health
- status: 500
- statusText: Internal Server Error
- durationMs: 4

## 2026-08-28 04:10:19.481Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/health: 

## 2026-08-28 04:10:19.481Z console.warn
- text: [useAIConnection] Backend unreachable (500). Retry 5/8 in 16000ms

## 2026-08-28 04:10:35.485Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/health
- status: 500
- statusText: Internal Server Error
- durationMs: 3

## 2026-08-28 04:10:35.485Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/health: 

## 2026-08-28 04:10:35.486Z console.warn
- text: [useAIConnection] Backend unreachable (500). Retry 6/8 in 30000ms

## 2026-08-28 04:11:04.451Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/user/balance
- status: 500
- statusText: Internal Server Error
- durationMs: 5

## 2026-08-28 04:11:04.451Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/user/balance: 

## 2026-08-28 04:11:05.490Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/health
- status: 500
- statusText: Internal Server Error
- durationMs: 2

## 2026-08-28 04:11:05.490Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/health: 

## 2026-08-28 04:11:05.490Z console.warn
- text: [useAIConnection] Backend unreachable (500). Retry 7/8 in 30000ms

## 2026-08-28 04:11:35.495Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/health
- status: 500
- statusText: Internal Server Error
- durationMs: 3

## 2026-08-28 04:11:35.495Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/health: 

## 2026-08-28 04:11:35.496Z console.warn
- text: [useAIConnection] Backend unreachable (500). Retry 8/8 in 30000ms

## 2026-08-28 04:12:05.502Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/health
- status: 500
- statusText: Internal Server Error
- durationMs: 4

## 2026-08-28 04:12:05.502Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/health: 

## 2026-08-28 04:12:05.502Z console.error
- text: [useAIConnection] Max reconnect attempts reached. Giving up.

## 2026-08-28 04:13:33.210Z console.warn
- text: [Perf] Low FPS detected: 46

## 2026-08-28 04:14:53.881Z console.warn
- text: [Perf] Low FPS detected: 50

## 2026-08-28 04:15:04.470Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/user/balance
- status: 500
- statusText: Internal Server Error
- durationMs: 11

## 2026-08-28 04:15:04.470Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/user/balance: 

## 2026-08-28 04:16:06.571Z console.warn
- text: [Perf] Low FPS detected: 47

## 2026-08-28 04:17:48.542Z console.warn
- text: [Perf] Low FPS detected: 51

## 2026-08-28 04:20:04.506Z network.error
- method: GET
- url: http://localhost:3000/hcgi/api/user/balance
- status: 500
- statusText: Internal Server Error
- durationMs: 24

## 2026-08-28 04:20:04.506Z console.error
- text: Fetch error from http://localhost:3000/hcgi/api/user/balance: 

