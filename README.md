# Bike Service

## SCREENSHOTS
### Home Page
![dashboard snap](https://raw.githubusercontent.com/Kishore37sk/Bike-Service-Application/master/Screen%20Shot/Home%20Page.png?token=GHSAT0AAAAAABUTJOH74RECF4GONTNBO2WOYULFONA)
### Owner Dashboard 
![dashboard snap](https://raw.githubusercontent.com/Kishore37sk/Bike-Service-Application/master/Screen%20Shot/Owner%20DashBoard.png?token=GHSAT0AAAAAABUTJOH6PDIK2RCRXAW6JP2AYULFPVQ)
### Customer Dashboard
![dashboard snap](https://raw.githubusercontent.com/Kishore37sk/Bike-Service-Application/master/Screen%20Shot/Customer%20DashBoard.png?token=GHSAT0AAAAAABUTJOH64GQQH4TQYO7YSBTAYULFQ3Q)

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
      Front-End -> HTML,CSS,JavaScript,Boot
      Back-End  -> Python (Programming Language)
      DataBase  -> MySql
      




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
