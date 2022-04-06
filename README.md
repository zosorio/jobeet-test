# jobeet-test
jobeet-test Symfony Step by Step

Day 1: Starting up the Project
------------------------------

* Project Creation
> $ php lib/vendor/symfony/data/bin/symfony generate:project jobeet

* Application Creation
> $ php symfony generate:app frontend

* Web Server Configuration: The secure Way
> DirectoryIndex: index.php
> 
> Directory route: /home/sfprojects/jobeet/web
> 
> Virtual directory route: /home/sfprojects/jobeet/lib/vendor/symfony/data/web/sf
> 
> Note: The /sf alias gives you access to images and javascript files needed to properly display default symfony pages and the web debug toolbar|Web Debug Toolbar.

* Test the New Configuration
> http://localhost:8080/index.php/, or http://www.jobeet.com.localhost/index.php/ depending on the Apache configuration you chose in the previous section.
> 
> You should also try to access the application in the development environment: http://www.jobeet.com.localhost/frontend_dev.php/
