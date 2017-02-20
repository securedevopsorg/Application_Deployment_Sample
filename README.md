# Application_Deployment_Sample

An 'Application Code Sample' - Provided for demonstration only - you are required to replace this with your own application before final deployment.

There are 2 distinct code components to any deployment. These are:

  1. *Infrastructure Code* -  Can be virtualized, is consumed by codedeploy or etc., and is used to specify/define the infrastructure as code that the application runs on/in.
  2. *Application Code* - Your application code - What this sample is.

Use this Application Code Sample as a basic 'example' or demo application to push to your infrastructure to verify it is working.

This application represents a fully prepared deployment ready application typically served from a web root directory (path: /var/www/.) Commonly these files are written in HTML and contain index.html as the starting point !(/var/www/index.html)!.

**Contents:**
* LICENSE - Apache License (for information only)
* README.md - This files (for information only)
* appspec.yml - Defines basic parameters for the application deployment - such as runas user (root), timeout for handling of sripts
* index.html - Starting point of application (see above)
* Application_Deployment_Sample.zip - A zipped copy of this application
* scripts - Folder containing scripts to handle deployment steps for application
  * install_dependencies - Installs dependencies into deployment (ie httpd, nginx, etc.)
  * start_server - Starts dependencies (ie httpd)
  * stop_server - Stops dependencies (ie httpd)


Typically this application is served up by your web server daemon (such as Apache or NGINX) to visitors to your web site.

This would be replaced by your own deployment ready application.
