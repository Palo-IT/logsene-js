# Origin
This repository is forked from https://github.com/sematext/logsene-js

# Usage
This patched libaray aims to ship the application logs generated in docker container to the self-hosted ELKX stack
Please provide the followed four variables:
ELK_HOST
ELK_PASSWORD
ELK_PORT
LK_USERNAME

It uses index "application-logs" for logs to store in Elasicsearch
