Basic Back-end : Food Order & Delivery App with Django.

# App Start
python manage.py runserver

# Process
1. Customer : Select store with 'order/shops' > Move to 'order/menus/<shop:id>' > Select Menus
2. Master : Check menus with 'boss/orders/<shop:id>' > Input estimated delivery time
3. Delivery : Check menus & Finish delivery using 'delivery/orders/'