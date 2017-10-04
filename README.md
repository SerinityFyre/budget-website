# budget-website
## 20170920
* Crated a small Amazon Linux server on the free tier. Researched how to install nginx, but "Amazon Linux" did not have an immediately evident supported package. Further research indicated the Amazon Linux OS was originally based on CentOS, so I attempted to install using the command `sudo yum install -y nginx`. The version installed seems to align with the nginx site documentation.
* Step 3 of the Project Plan should now be complete, figuring out how to complete step 4 to deploy the website. Going to push the `install-nginx` branch now so that I can clone the repo onto the new server
## 20171003
* Need to get better about notating work and progress. Stepped back from working on nginx after getting it installed to focus on Chef. In Learn Chef Rally, I completed the "Getting Started" module and the first track of the "Infrastructure Automation" module (Learn the Chef Basics). Built a test webserver with Chef and httpd and got a good initial feel for creating recipes and cookbooks
