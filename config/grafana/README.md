# Run grafana
sudo docker run --network monitoring -p 3000:3000 -v ~/nexa/monitoring-stack/config/grafana/grafana.ini:/etc/grafana/grafana.ini -d  grafana/grafana