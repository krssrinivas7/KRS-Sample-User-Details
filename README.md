Sample User Details form 

It is a simple webpage having Registration form to fill details for demo projects.

- Pre-requisites:-
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
- Go inside container and update mysql database credentials if required the data.
- Access using http://localhost(or)pubip/
    
