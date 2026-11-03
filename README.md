1) Написать плейбук, который:
   
   <br>- Устанавливает пакеты tree и jq;</br>
   <br>- Создаёт директорию /opt/app/config;</br>
   <br>- Копирует files/app.conf в /opt/app/config/app.conf (содержимое app.conf https://github.com/anestesia001/static-demo-app/blob/main/app.conf);</br>
   <br>- Устанавливает права 0644;</br>
   
 ```

```
2) Написать плейбук, который:

   <br>- Создаёт группу devops;</br>
   <br>- Создаёт пользователя ecom: shell — /bin/bash; домашняя директория — /home/ecom; пользователь входит в группу devops;</br>
   <br>- Создаёт директорию /home/ecom/.ssh с правами 0700;</br>
   <br>- Создаёт файл /home/ecom/.ssh/authorized_keys;</br>
   <br>- Вставляет в authorized_keys публичный SSH-ключ, который лежит в файле files/ecom_key.pub;</br>
   <br>- Устанавливает владельца ecom и права 0600 на authorized_keys;</br>
  
 ```

```
![](https://github.com/matveyframe/Lesson_18/blob/main/notes_status.PNG "Logo Title Text 1")

3) Написать плейбук, который:
   
   <br>- Создаёт пользователя demoapp без возможности входа по паролю;</br>
   <br>- Создаёт директорию /opt/demo_app с владельцем demoapp;</br>
   <br>- Копирует index.html (https://github.com/anestesia001/static-demo-app/blob/main/index.html) в /opt/demo_app/index.html;</br>
   <br>- Копирует unit-файл (https://github.com/anestesia001/static-demo-app/blob/main/demo-app.service) в /etc/systemd/system/demo-app.service;</br>
   <br>- Выполняет systemctl daemon-reload;</br>
   <br>- Включает и запускает сервис demo-app;</br>
   <br>- Выполняет проверку через curl;</br>
   
```

```
![](https://github.com/matveyframe/Lesson_18/blob/main/nginx_status_health.PNG "Logo Title Text 1")


