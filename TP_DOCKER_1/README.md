3.  
  
    a. docker pull httpd  
    ![Q 3a](image3a.png)  
  
    ![Q 3b](image3b.png)  
  
    c. ![Q 3c](image3c.png)  
  
    d. docker run -d -p 3000:80 --name mondocker -v ./  public-html:/usr/local/apache2/htdocs/ httpd   
    ![Q 3d](image3d.png)  
  
    e. docker stop mondocker  
    docker rm mondocker  
    ![Q 3e](image3e.png)  
  
    f. docker run -d -p 3000:80 --name mondocker httpd   
    ![Q 3f1](image3f1.png)  
    docker cp ./public-html mondocker:/usr/local/apache2/htdocs/  
    ![Q 3f2](image3f2.png)  
  
4.  
  
  a. echo >> "Dockerfile" ou clique droit  

  b. 