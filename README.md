# APPXEN DRUPAL STACK

The AppXen Drupal Stack provides a single-click install solution for Drupal, containerized on EC2 for portability. Drupal is one of the most versatile open source content management systems available, with over a thousand developers contributing to the code. Drupal is built for high performance and is horizontally scalable, has easy integration via REST, JSON, SOAP and other formats, and features a whopping 15,000 plugins to extend and customize the application for just about any type of website.

# QUICKSTART

When installing drupal, when you the "Set up database" step use:

 - type: postgresql
 - database: postgres
 - username: postgres
 - password: [insert password from docker-compose.yml (autogenerated on first boot)]

Then click on Advanced Options and set the hostname to "postgres" (without the quotes).
(Containers on the same docker-network are routable by their container-name)

That's it! You should be ready to go. If you need support, please visit https://appxen.com/app/drupal
