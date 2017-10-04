# budget-website
## 20170920
* Crated a small Amazon Linux server on the free tier. Researched how to install nginx, but "Amazon Linux" did not have an immediately evident supported package. Further research indicated the Amazon Linux OS was originally based on CentOS, so I attempted to install using the command `sudo yum install -y nginx`. The version installed seems to align with the nginx site documentation.
* Step 3 of the Project Plan should now be complete, figuring out how to complete step 4 to deploy the website. Going to push the `install-nginx` branch now so that I can clone the repo onto the new server
## 20171003
* Need to get better about notating work and progress. Stepped back from working on nginx after getting it installed to focus on Chef. In Learn Chef Rally, I completed the "Getting Started" track and the first module of the "Infrastructure Automation" track (Learn the Chef Basics). Built a test webserver with Chef and httpd and got a good initial feel for creating recipes and cookbooks
## 20171004
* I am reviewing Annie's Basic Chef Fluency Study Guide (https://github.com/anniehedgpeth/basic-chef-fluency-study-guide) and will looking into adding an hour-long Chef Kata into my daily routine based on the guide
* Starting today on module 2 of the Infrastructure Automation track: "Manage a node with Chef server". I have decided to set up my own Chef server as opposed to using a hosted server (to gain additional practice and experience)