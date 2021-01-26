# Middleware APIs

## Potres2020 checkSha256
When a report is created or updated, Ushahidi Platform / Potres2020 can send a POST request to a third- party application listening to HTTP requests on the internet.

Your application receiving the web hook call may check this signature to verify that the web hook payload was originated in the Platform.

More info: [Ushahidi - Web hooks](https://docs.ushahidi.com/platform-developer-documentation/tech-stack/connected-app-development/web-hooks)

This is a helper API to verify the sha256 digest.

API doc: [here](https://documenter.getpostman.com/view/130981/TW6urA3w)



### Development & Deployment
https://repl.it/@dpoldrugo/potres2020

It's currently deployed on Repl.it: https://potres2020.dpoldrugo.repl.co/api/utils/checkSha256

[![Run your version on Repl.it](https://repl.it/badge/github/potres2020/middleware-api)](https://repl.it/github/potres2020/middleware-api)