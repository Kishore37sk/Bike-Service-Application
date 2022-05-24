# Bike Service

## SCREENSHOTS

### Home Page

![Home Page](https://user-images.githubusercontent.com/96305967/169760510-e7050f4d-4ec8-4d69-85ef-76a857e7b1b9.png)

### Owner Dashboard 

![Owner DashBoard](https://user-images.githubusercontent.com/96305967/169760539-35457144-3b49-4953-8b4f-062eed6a799f.png)


### Customer Dashboard

![Customer DashBoard](https://user-images.githubusercontent.com/96305967/169760561-07f01975-8382-4a8f-93b1-f307e134eec6.png)


𝐅𝐔𝐍𝐂𝐓𝐈𝐎𝐍𝐒:

𝐂𝐮𝐬𝐭𝐨𝐦𝐞𝐫:
- Should be able to register for an account with his email address and mobile
 number
- Book a service at a particular date
- See the status of his booking
- See all his previous bookings

𝐁𝐢𝐤𝐞 𝐬𝐭𝐚𝐭𝐢𝐨𝐧 𝐨𝐰𝐧𝐞𝐫:

- First admin will login ( for username/password run following command in cmd )
  py manage.py createsuperuser
- Should be able to create / edit / delete all his services and their details
- View a list of all bookings ( pending, ready for delivery and completed)
- View details of each booking
- Mark a booking as ready for delivery
- Mark a booking as completed


𝐓𝐞𝐜𝐡𝐧𝐨𝐥𝐨𝐠𝐲 𝐒𝐭𝐚𝐜𝐤 𝐔𝐬𝐞𝐝 :

      FrameWork ->  Django
      Front-End -> HTML,CSS,JavaScript,BootStrap
      Back-End  -> Python (Programming Language)
      DataBase  -> MySql
      

𝐃𝐚𝐭𝐚𝐁𝐚𝐬𝐞 𝐒𝐜𝐡𝐞𝐦𝐚 :

            mysql> use bike service;
            mysql> show tables;
            +--------------------+
            | Tables_in_workshop |
            +--------------------+
            | customer           |
            | owner              |
            | Machine            |
            +--------------------+
            
            This application has Three tables 
              
                1.) customer - to handle all booking Details and history
                2.) Machine - to handle service data
                3.) owner - to handle user data
                
         In order to handle owner data I make property file it is much convenient than table data


𝐇𝐎𝐖 𝐓𝐎 𝐑𝐔𝐍 𝐓𝐇𝐈𝐒 𝐏𝐑𝐎𝐉𝐄𝐂𝐓

Install Python(3.7.6) (Dont Forget to Tick Add to Path while installing Python)

Open Terminal and Execute Following Commands :

pip install django==3.0.5

pip install django-widget-tweaks

Download This Project Zip Folder and Extract it
Move to project folder in Terminal. 

Then run following Commands :
py manage.py makemigrations
py manage.py migrate
py manage.py runserver
Now enter following URL in Your Browser Installed On Your Pc
http://127.0.0.1:8000/ 
