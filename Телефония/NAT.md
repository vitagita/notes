**Настройка NAT**
на linksys/cisco
linksys переходим в Admin Login -> Advenced и далее проверяем настройки

в cisco просто проверяем настройки
Идем в меню SIP и сморим параметры:
1) PRT Parametrs 
значения: PRT Packet Size 0.020 !!!
2) NAT Support Parametrs 
значения: 
Handle VIA recived = yes
Handle VIA rport = yes
Insert VIA recived = yes
Inserv VIA rpprt =yes

Делаее идем в LIne 1-n+1
сверяем параметры:
Proxy and Registrations:
Register Expiries= 180

Subscriber Information	
только user_id и password

Supplementary Service Subscription
Call Waiting Serv = no!!!!

Audio Configuration	 
	Preferred Codec: G711a!
	Use Pref Codec Only: yes!