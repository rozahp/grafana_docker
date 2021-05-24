# Grafana Docker 

Build a grafana docker image with which you can provision dashboards and datasources. Based on [dockerfiles](https://github.com/grafana/grafana/tree/main/packaging/docker) from the grafana repository.

## AUTHOR OF THIS COMPILATION 

Phazor / Cascade 1733 

## INSPIRATION

Got inspiration and examples from other coders on Github.

## LICENSE

Please feel free to copy, distribute and change this program in any way you like.

## INSTALLATION

1. Download latest [grafana-binary.tar.gz](https://grafana.com/grafana/download?platform=linux) or run ./download-grafana.sh 

2. Rename downloaded file to: grafana-latest.linux-amd64.tar.gz

2. Copy your dashboards or datasources to directories: grafana/datasources or grafana/dashboards

    docker-compose -f docker-compose.yml build 

and

    docker-compose -f docker-compose.yml up

## CONFIGURATION

None.

## TODO

Nothing yet.

