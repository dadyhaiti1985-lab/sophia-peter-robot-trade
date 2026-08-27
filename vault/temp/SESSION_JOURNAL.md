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

