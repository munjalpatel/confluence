# Atlassian Confluence
---

## Build

docker build -t munjalpatel/confluence .

## Run

docker run -d --name confluence -p 8090:8090 munjalpatel/confluence:latest