# fbcore-docker-runner

This script runs (or stops) docker containers with FBCORE app. Before it, setup your localGateway address and pull latest images. It is also possible to run initData.

# Configuration
set variable `docker_compose_file` - path to your *docker-compose.yml* file

# Instalation
copy script to /usr/local/bin/ or create custom alias

# Arguments
| argument             | description |
| --- | --- |
| start, up, s  | setup your ip address, pull latest images and (re)create and start containers |
| stop, down    | stop end remove containers |
| si            | same as start with initData |
| sia           | same as start with initData for Alegro |

# How to use
`fbcore sia`
