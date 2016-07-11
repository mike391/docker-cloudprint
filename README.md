# docker-cloudprint

To run:
`docker create --name=cloudprint -v /opt/cloudprint:/config -e CUPS_SERVER="***" kmlucy/docker-cloudprint`

To create config: 
`docker run -it -v /opt/cloudprint:/config -w /config kmlucy/docker-cloudprint gcp-connector-util init`
