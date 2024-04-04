# AngularDockerSampleApp

## Development

1. Clone the repository
2. Go to the root directory of [angular-docker-sample-app](./angular-docker-sample-app)
3. Execute the following commands
```shell
# install dependencies
npm install

# start app
ng serve
```
4. Access the app at http://localhost:4200

## Docker Deployment

### Prerequisites

Before deploying the Portal with Docker, ensure that you have the following installed:

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

### Steps for Docker Deployment

1. Go to the root directory of [angular-docker-sample-app](./angular-docker-sample-app)
2. Create `.env` file using values in [.env.example](./angular-docker-sample-app/.env.example)
3. Start Docker
4. Run the following command
```shell
docker-compose -f docker-compose.yml up
```
5. Access the app at http://localhost:5000. If you specified a different port in your `docker-compose.yml` file (via `.env` file), adjust the port number accordingly.
6. To stop the running containers, use the following command
```shell
docker-compose down
```

### Additional Notes

- Customize the `docker-compose.yml` file if you need to adjust port mappings or other configurations.
- If your application relies on additional environment variables, you can set them in the `.env` file in the same directory as your `docker-compose.yml` file.