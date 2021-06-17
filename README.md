**Installation Process Using PaaS - AWS (Rocket.Chat Challenge)**

**By**  **Leonardo Torres**  **–** [**mailto:lemarto@gmail.com**](mailto:lemarto@gmail.com)

1. Register and Login at AWS account

2. Setup an AWS EC2 instance with Ubuntu Server 18.04 LTS 64bits(x86) architecture
3. Launch the Instance

4. Allocate Elastic IP in order to have a Public IP and Public DNS

![](https://github.com/leotorres76/Rocket.Chat_ES_Leonardo_Torres/blob/main/aws_elastic_ip_setup.png)

5. Setup DNS and create a CNAME Record (www)as a Subdomain using my own Domain - [luckyowee.com.br](https://luckyowee.com.br/)

![](https://github.com/leotorres76/Rocket.Chat_ES_Leonardo_Torres/blob/main/aws_dns_setup.png)

6. Install an SSL certificate (I used Let&#39;s Encrypt as suggested)

7. Setup Nginx web with TLS/SSL

8. Install Docker and Docker Compose

9. Setup Docker Containers and start them in order to have Rocket.Chat up and running

![](https://github.com/leotorres76/Rocket.Chat_ES_Leonardo_Torres/blob/main/rocketchat_installation_success.png)

10. Log into [https://luckyowee.com.br](https://luckyowee.com.br/) (Rocket.Chat Server) and register for the first time as Admin

11. Success Login! (USER: leotorres | PASSWORD: 30t@o99Xyz)

![](https://github.com/leotorres76/Rocket.Chat_ES_Leonardo_Torres/blob/main/success_log_in.png)

12. The day after the successfull instalation and login I tried to access again and had some technical issues on AWS side and the server became unreachable so I can't perform API Endpoint tests as requested on the assesment. :-(

![](https://github.com/leotorres76/Rocket.Chat_ES_Leonardo_Torres/blob/main/aws_instance_status_check_faillure.png)


**That's all and thank you all for the opportunity!**
