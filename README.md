# AngularDockerSampleApp

## Development

1. Clone the repository
2. Go to root directory of [angular-docker-sample-app](./angular-docker-sample-app)
3. Execute the following commands
```shell
# install dependencies
npm install

# start app
ng serve
```
4. Access the app at http://localhost:4200

## Docker

1. Go to root directory of [angular-docker-sample-app](./angular-docker-sample-app)
2. Create `.env` file using values in [.env.example](./angular-docker-sample-app/.env.example)
3. Start Docker
4. Run the following command
```shell
docker-compose -f docker-compose.yaml up
```
5. Access the app at http://localhost:5000
