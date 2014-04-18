shiny-server
===============

Adapted from https://github.com/rstudio/shiny-server/tree/master/vagrant/ubuntu13.04.

These scripts will start a Ubuntu 13.04 VM and provision it with (https://github.com/rstudio/shiny-server/).

The port 3838 will be forwarded to the host system.
Simply copying shiny apps into the `./apps` directory will make them available to shiny-server


Run:
  $ vagrant up
  
  
To view your shiny apps
  $ cp -R <my app> ./apps

Open a browser and goto `localhost:3838`


