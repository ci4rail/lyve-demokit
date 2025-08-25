# lyve-demokit-docker
Docker setup for LYVE Demo Kit


# Initial setup

Start all containers with docker compose:
```
$ docker compose up -d
```

# View Grafana Dashboard

1. Open your web browser and navigate to [http://localhost:3000](http://localhost:3000).  
2. Log in with the following credentials:  
   - **Username:** `lyve-demo`  
   - **Password:** `lyve123`  
3. Go to **Dashboards** and select the one you want to view.  

> **Note:** If this is the first time the Grafana container is started (or its volume has been deleted), click on **New** and import `dashboard-single-tracelet.json`.
