# Docker Compose odoo 12.0 community
# Docker Compose odoo 12.0 and enterprise with offical docker odoo



## Requirements


 - docker-compose v2 version or later https://docs.docker.com/compose/install/
 - Docker CE or EE https://docs.docker.com/install/
 - git 
 
 

## How to run 

 - Install the requirements 
 - Clone the repo

     `` git clone git@github.com:quenode/odoo-docker-compose.git ``

## How to use
Download the docker-compose.yml file in some folder example "odoo-12-testing"

Run the command from console shell docker-compose up 

Connect to http://localhost:8069

Enjoy odoo 12.0


## Odoo Enteprise and Custom modules and odoo config 

 The new option is allows to use own odoo config with custom modules also
 you can add an enterprise odoo option.
 
 The structure you can copy enterprise modules is ./repo/odoo/enterprise when Downloaded from odoo 
 https://github.com/odoo/enterprise.  
 Note: You have to have valid access to this repo since this private repo.




