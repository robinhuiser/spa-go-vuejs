# My Single-Page App with Go and Vue

A side project in order to get familiar with the combination Golang / Vue.js as well as applying OIDC and (hopefully) full Oauth2 access_token support with consent management.

# Prerequisites

~~~bash
# Vue.js cli
$ yarn global add @vue/cli
~~~

## Run the webapp and (ExpressJS) API

~~~bash
$ cd pkg/http/web/app
$ PORT=3000 npm run dev
~~~