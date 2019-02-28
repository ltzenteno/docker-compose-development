  # Local development compose files

  to run postgres 9.5 and mongo inside docker containers, with a custom volume:

  1. run `docker pull postgres:9.5.16`

  2. run `docker pull mongo`

  2. run `docker-compose -f databases-compose.yml up -d`

  to stop it, run `docker-compose -f databases-compose.yml down`

