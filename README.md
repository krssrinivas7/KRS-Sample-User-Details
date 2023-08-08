Sample User Details form
Pre-requisites:
- PHP, Apache Server, Mysql

Procedure:
- Clone the Repository.
- Configure the files to Webserver root directory.
- Configure the mysql database credentials
- Reload the apache2 service
- Access using http://localhost(or)pubip/

  By using Docker
  - Install Docker
  - Pull the image
    $ docker pull krssrinivas/userdetails:1
  - Create container with the pulled image
    $ docker run -d -p 80:80 --name userdetails krssrinivas/userdetails:1
  - Access using http://localhost(or)pubip/
    
