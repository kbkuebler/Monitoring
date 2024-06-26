This should help as a Promhetheus/Grafana quick start for SEs and others that just want to test things out in a non-production environment.
In order to get started, clone this repo and change the values of `prometheus/prometheus.yaml` to what's appropriate for your Hammerspace cluster.

Once that has been done, go to folder that has the `docker-compose.yaml` file and run `docker compose up` and monitor the output. If everything has come up and is working as desired, you can `ctrl-c` and then restart with 
`docker compose up -d` and you should be able to demo and POC.
