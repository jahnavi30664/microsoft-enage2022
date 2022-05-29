# microsoft-enage2022

Process to run this application:

step-1: Cloning

git clone https://github.com/jahnavi30664/microsoft-enage2022

step-2:

Open the project in visual studio code

step-3: installing requirements using pip

pip install -r requirements.txt

step-4: 
  1)Now login to azure portal 
  
     Services we use :
     
          1)Azure FaceAPI
          
          2)Azure postgres
          
          3)Azure blob
          
          4)App services

  2)create a postgres server with public access and allow azure services. Enable Allow public access from Azure service within Azure to this server
  
  3)Copy the host name from the Connection Strings
 
  4)Now create a firewall rule with your public IP as start and end IP addresses by going to networking
  
  5)Download and install pgadmin app
  
  6)Now go to connection and copy host name
  
  7)Enter the hostname and credentials in pg admin app
  
  8)create a database with name mydb
  
  9)Add hostname and password to database in settings.py
  
  10)Enter python manage.py makemigrations in terminal
  
  11)Enter python manage.py migrate    
  
  12)Enter python manage.py runserver
