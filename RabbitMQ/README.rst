# Terminal üzerinden docker kurulumu

* docker run -d --restart always -p 5672:5672 -p 15672:15672 --name rabbitmq rabbitmq:3-management
* default user-name = guest
* default password = guest
* localhost:15672 üzerinden erişim sağlanabilir.