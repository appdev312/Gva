
# GVA APP built on Vue.js

## Using

> Frontend

- [Vue.js](https://github.com/vuejs/vue)
- [vue-router](https://github.com/vuejs/vue-router)
- [vue-resource](https://github.com/pagekit/vue-resource)
- [vuex](https://github.com/vuejs/vuex)
- [cooking](https://github.com/elemefe/cooking/)
- [webpack](https://github.com/webpack/webpack)
- [Muse-UI](https://github.com/museui/muse-ui)

> Backend

- [Springboot](https://github.com/spring-projects/spring-boot)
- [OkHttp](https://github.com/square/okhttp)
- [Kotlin](https://github.com/JetBrains/kotlin)

> etc

- [docker](https://www.docker.com/)
- Nginx
- Apache Tomcat

### Debug

runtime environment

- Node.js 4+
- npm 3+
- Python 2.7.x

install cooking
```

  npm i cooking-cli -g

```

- deploy nga-data-delegate
- modify baseurl (in ./vuex/store.js) to local adress (default localhost:8888)
- start debugging

```

  npm install
  cooking watch

```
- open localhost:8808/home

***

## Building

```
  cooking build
```
