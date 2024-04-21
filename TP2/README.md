3.  
  
  
    a. docker pull httpd  
    ![Q 3a](image3a.png)  

    b. docker images
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
  
3.  
  
  a. echo >> "Dockerfile" ou clique droit  

  b. docker build -t serverweb .  
  ![Q 4b](image4b.png)  
  
  c. La méthode de la question 4 est mieux pour créer les images  
  Q3 points forts/faibles :  
  - beaucoup de commandes  
  - moins bien  
    

  Q4 points forts/faibles :  
  + mettre dans un fichier c'est mieux pour y accéder  
  + c'est mieux, j'ai mieux compris  

5.  
  
  a. docker pull mariadb  
  docker pull phpmyadmin  
  
  b.docker run -d -p 8080:80 mariadb  
  docker run -d -p 8080:80 phpmyadmin  
  ![Q 5b](image5b.png)  
  
  ![Q 5bb](image5bb.png)  
  Je n'arrive pas a me connecter    
    
6.  
  
  a. Docker compose permet de lancer plusieurs container. Elle permet de les créer et de les lancer tout les services que l'on souhaite et elle peut donner pleins d'informations sur les services. Tandis que docker run ne permet d'agir que sur un seul container a la fois.  
  
  b. docker compose up  
  docker compose down  
  
  c. docker compose up -d  
  ![Q 6c](image6c.png)  
