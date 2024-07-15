# Compose Apps

A repo for the compose files for different applications.

**Note:**

The data of the services will be stored in `/compose-apps/data/` directory. To create data storage directory use the following command.
```shell
sudo mkdir -p /compose-apps/data
```

## Steps:
1. Clone the repo `git clone https://github.com/codesark/compose-apps.git`.
2. Change directory to the repo `cd compose-apps` and select the service you want to run. Eg. `cd nginx-proxy-manager`. 
3. To manage the service run the following command
4. **Important**: change the configuration in `compose.yaml` file for respective project.

### Start Service 

```shell
docker compose up -d
```

### Stop Service 

```shell
docker compose down 
```

