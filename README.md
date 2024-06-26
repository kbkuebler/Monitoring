This should help as a Promhetheus/Grafana quick start for SEs and others that just want to test things out in a non-production environment.
In order to get started, clone this repo and change the values of `prometheus/prometheus.yaml` to what's appropriate for your Hammerspace cluster.

It's recommended that you're on the latest version of Hammerspace (Version 5.0.7 or greater).

SSH into your anvil and enable the Prometheus exporters:
`cluster-update --prometheus-exporters-enable`

For older versions, please see the Hammerspace documentation.

Once that has been done, go to folder that has the `docker-compose.yaml` file and run `docker compose up` and monitor the output. If everything has come up and is working as desired, you can `ctrl-c` and then restart with 
`docker compose up -d` and you should be able to demo and POC.

Note that the default login and password is `admin:admin1`
