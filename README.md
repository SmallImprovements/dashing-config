#Dashing Dashboard Configuration
Configuration for the dashing dashboard.

This is read by the dashing container on the teamcity server.

### Usage
``
docker run\
  -e CONFIG=https://raw.githubusercontent.com/SmallImprovements/dashing-config/master\
  frvi/dashing:latest
``

