# x-y
# نصب 

```bash
# اول در ترمینال بزنید
sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev libevent-dev make unzip git redis-server g++ libjansson-dev libpython-dev expat libexpat1-dev
```

```bash
# سپس نصب بات
cd $HOME
git clone https://github.com/makearobot/x-y.git.git
cd x-y
chmod +x launch.sh
./launch.sh install
./launch.sh # سپس برای شماره تلفن از شما سوال میشود
```

### نکته مهم
برای راه اندازی  ایکس ایگرگ خود
>باید فایل های یک ربات کامل را داشته باشید
>>درگیت هاب ما تنها پلاگین ها پابلیک شده اند
>
>سعی کنید که اگر بات رو خواستید بسازید وارد فایل اینگروه شوید و قبل دستورات اسپم خور علامتی قرار دهید مانند زیر
>> --id 

>فراموش نکنید ایدی هارا تنظیم کنید

### تنظیم ایدی
>در فایل yourid.lua 
>>ایدی خود را در بخش مورد نظر بگذارید
>در فایل xid.lua
>>ایدی ایکس خودرا قرار دهید
>در فایل yid.lua
>>ایدی ایگرگ خودرا قرار دهید.

#مهم مهم
* سعی کنید دو الی سه بات بسازید مانند
> x-y-w-z
#سازنده و چنل
چنل > [@make_a_robot](http://telegram.me/make_a_robot)
سازنده > [@Mr_Vigeo](http://telegram.me/mr_vigeo)
