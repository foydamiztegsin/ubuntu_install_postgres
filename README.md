#  1).Ubuntu serverga PostgreSQL ni to'g'ri o'rnatish
#  2).PostgreSQL da Database va User yaratish 
#  3).Serverdagi PostgreSQL ga local Kompyuterimizdan bog'lanish



 <hr>
 
✅ Ubuntu 20.04 yoki undan keyingi versiyalar uchun:
```rb
sudo apt update
sudo apt install postgresql
```

<br>


✅ PostgreSQL ga bog'lanish:
```rb
sudo -i -u postgres
psql
```
![postgres](images/1.jpg)

<br>


✅ PostgreSQL da Database va unga User yaratish:
```rb
create database my_db;
create user my_user with password '12345';
```
![postgres](images/2.jpg)

<br>


✅ PostgreSQL dan chiqish:
```rb
\q 
logout
```
![postgres](images/3.jpg)

<br>


✅ PostgreSQL ni DJANGO loyihada ishlatmoqchi bo'lsangiz o'rnating::
```rb
# ❌ pip install pyscopg2 buni o'rnatmang
pip install psycopg2-binary
# agar pip da xato bersa
sudo apt install python3-pip
```














