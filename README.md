Node Application Deployment
===========================

Usage
-----
    ansible-playbook mare.yml --ask-sudo-pass


This is a sample ansible deployment playbook for deploying a node application to a server. Currently this makes some assumptions like there is an upstart job running that wiill need to be restarted and your node_modules are *not* checked into your git repository. This is currently used to deploy a Sails.js application to staging or production.

