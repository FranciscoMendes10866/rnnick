# Project Idea

The idea of this small project was the creation of a simple web page created with [Vue.js](https://v3.vuejs.org/), which is later served by the server through [Nginx](https://hub.docker.com/_/nginx). All of this while both coexist within a single [Docker](https://docs.docker.com/) container.

## How to Build

First step:

```bash
cd vue-app
```

Second step:

```bash
docker build -t rnnick:latest .
```

Third step:

```bash
docker run -d -p 80:80 rnnick:latest
```

Fourth step:

```bash
http://localhost:80
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)
