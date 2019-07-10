# Docker with NodeJS

Dockerfile and package.json for a simple NodeJS application in docker with express.

### Installing

Install dependencies

```
npm install
```

Build the image

```
docker build -t image-name .
```

Run the image on the desired port as localPort:imagePort (image port needs to be your NodeJS listen port)

```
docker run -p 3000:3000 -it image-name
```