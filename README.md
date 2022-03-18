Basic Back-end : Food Order & Delivery App with Django.

# Process
1. Customer : Select store with 'order/shops' > Move to 'order/menus/<shop:id>' > Select Menus
2. Master : Check menus with 'boss/orders/<shop:id>' > Input estimated delivery time
3. Delivery : Check menus & Finish delivery using 'delivery/orders/'

## Local Test
1. check backend/setting.py
2. set the database 
# Package Install
pip install -r requirement.txt

# App Start
python manage.py runserver

## AWS Test
Use Ubuntu 20.04 lts & RDS(mysql)
Modify backend/setting.py > 'databases' and 'allowed host'

# Command
1. apt update && upgrade
2. apt install build-essential && libmysqlclient-dev
3. check python3, python3-pip
4. git clone
5. mv 'clone-directory'
6. pip3 install -r requirements.txt
7. python3 manage.py runserver 0.0.0.0:8000
8. ctrl+z > bg > disown -h