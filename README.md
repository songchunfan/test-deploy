# test-deploy

## Project setup

```
yarn install
```

### Compiles and hot-reloads for development

```
yarn serve
```

### Compiles and minifies for production

```
yarn build
```

### Lints and fixes files

```
yarn lint
```

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).

### docker

docker run -d -p 9000:80 -v /opt/local/var/lib/jenkins/.jenkins/workspace/test-deploy/dist:/usr/share/nginx/html/test-deploy nginx
