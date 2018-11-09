# OpenBSD httpd playbook

This repository has a very simple playbook for getting a webserver set up on
OpenBSD. 
It handles getting the TLS certificate from Let's Encrypt with a bootstrap
configuration file and then switches to a configuration that redirects all HTTP
requests to the HTTPS version of the site.
