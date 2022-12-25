# Metrics
* __Machine:__ linux x64 | 2 vCPUs | 6.8GB Mem
* __Node:__ `v18.12.1`
* __Run:__ Sun Dec 25 2022 12:57:59 GMT+0000 (Coordinated Universal Time)
* __Method:__ `npm run metrics` (samples: 5)
* __startup:__ time elapsed to setup the application
* __listen:__ time elapsed until the http server is ready to accept requests (cold start)

| | startup(ms) | listen(ms) |
|-| -       | -      |
| 1-startup-routes-schema.js | 190.86 | 268.57 |
| 1-startup-routes.js | 180.74 | 194.57 |
| 10-startup-routes-schema.js | 199.75 | 294.80 |
| 10-startup-routes.js | 187.45 | 204.23 |
| 100-startup-routes-schema.js | 203.28 | 433.47 |
| 100-startup-routes.js | 203.31 | 237.84 |
| 1000-startup-routes-schema.js | 502.07 | 1937.66 |
| 1000-startup-routes.js | 469.00 | 683.86 |
| 10000-startup-routes-schema.js | 8776.42 | 23900.66 |
| 10000-startup-routes.js | 7817.19 | 11764.19 |
| startup-listen.js | 184.00 | 200.48 |
