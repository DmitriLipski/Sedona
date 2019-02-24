# Project «Sedona»
[![Build status][travis-image]][travis-url] [![Dependency status][dependency-image]][dependency-url]


### Install
```
npm install
```

### Run
```
npm run start
```

### Build Docker image
```
npm run build
docker build -t sedona .
```

### Run Docker container on the port 5000
```
docker run -p 5000:80 --name sedona -d sedona
```






[travis-image]: https://travis-ci.org/htmlacademy-adaptive/384725-sedona.svg?branch=master
[travis-url]: https://travis-ci.org/htmlacademy-adaptive/384725-sedona
[dependency-image]: https://david-dm.org/htmlacademy-adaptive/384725-sedona/dev-status.svg?style=flat-square
[dependency-url]: https://david-dm.org/htmlacademy-adaptive/384725-sedona?type=dev
