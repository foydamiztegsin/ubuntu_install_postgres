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


✅ PostgreSQL ni DJANGO loyihada ishlatmoqchi bo'lsangiz o'rnating:
```rb
# ❌ pip install pyscopg2 buni o'rnatmang
pip install psycopg2-binary
# agar pip da xato bersa
sudo apt install python3-pip
```

<br>


# PostgreSQL ga Local Kompyuterimizdan bog'lanish uchun kerakli dastur:

[DBeaver](https://dbeaver.io/download/)  # Ishlatishda pgAdmindan ancha qulay


<br>


✅ DBeaver dasturini oching va rasmlardagi ketma ketlikda bajaring:

![postgres](images/4.jpg)

![postgres](images/5.jpg)


<br>

✅ Belgilangan joylarga ma'lumotlarni kiriting va Test Connection... ni bosing:


![postgres](images/6.jpg)


<br>

✅ Ushbu Xatolik chiqishi kerak!:
![postgres](images/7.jpg)


<br>

✅ Yuqoridagi xatolik serverdan ruxsat yuqligi sababli kelib chiqadi sozlash uchun serverdagi PostgreSQL ni sozlamalariga o'zgarishlar kiritamiz!
 - Sizda versiyasi boshqa bo'lishi mumkin!
![postgres](images/8.jpg)


<br>

✅ Rasmdagi qismni fayldan qidiring va ketma ketlikni bajaring!
 - ❗️Faylga yozib bo'lganingizdan so'ng
 - Avvalgi holati
![postgres](images/9.jpg)


 - O'zgarish
![postgres](images/10.jpg)

```rb
   ctrl+s
   ctrl+x
   Y
   Enter # ni bosing va faylni saqlab chiqib ketadi
```


<br>


✅ Keyingi fayni sozlang!
 - ❗️Faylga yozib bo'lganingizdan so'ng


![postgres](images/11.jpg)

- Avvalgi holati
![postgres](images/12.jpg)

- O'zgarish
![postgres](images/13.jpg)

  ```rb
   ctrl+s
   ctrl+x
   Y
   Enter # ni bosing va faylni saqlab chiqib ketadi
  ```


<br>

✅ O'zgarishlarni tugatib DBeaver Test Connection... ni qayta bosing xatolik yuqolishi va rasmdagidek chiqishi kerak:


![postgres](images/14.jpg)

- Finishni bosing bazaga ualansiz bemalol bazani boshqarishingiz mumkin 🥳
![postgres](images/15.jpg)


<hr>
 Mehnatimiz sizga foyda berayotgan bolsa GITHUB profilimizga obuna bo'ling va telegram kanalimizda reaksiyalarni qoldiring 👍
 
# *E'tiboringiz uchun rahmat* Savollaringiz bo'lsa [Telegram](https://t.me/foydamizteg_sin)









