После установки мы можем зайти на WebGUI самого PfSense по адресу в браузере “192.168.1.1“, но если у вас, как и у меня WAN адрес такой же как и у LAN, то лучше бы LAN адрес сменить на другой.

1. Выбираем пункт 2 “Set interface(s) IP address“
   
   <img src="https://raw.githubusercontent.com/AndromedaNGC/Workstation/main/PfSense/img/%D0%9F%D1%80%D0%BE%D0%B1%D0%B8%D1%80%D0%B0%D0%B5%D0%BC%D1%81%D1%8F%20%D0%B2%20WebGUI/Pasted%20image%2020230521201856.png" width=500>
   
2. Тут также выбираем пункт 2 “LAN (em1 - static)“
    Так как LAN, является нашей локальной сетью.
    
    <img src="https://raw.githubusercontent.com/AndromedaNGC/Workstation/main/PfSense/img/%D0%9F%D1%80%D0%BE%D0%B1%D0%B8%D1%80%D0%B0%D0%B5%D0%BC%D1%81%D1%8F%20%D0%B2%20WebGUI/Pasted%20image%2020230521201900.png" width=500>
    
3. Вводим необходимый IP адресс и маску сети и нажимаем Enter
   
   <img src="https://raw.githubusercontent.com/AndromedaNGC/Workstation/main/PfSense/img/%D0%9F%D1%80%D0%BE%D0%B1%D0%B8%D1%80%D0%B0%D0%B5%D0%BC%D1%81%D1%8F%20%D0%B2%20WebGUI/Pasted%20image%2020230521201906.png" width=500>
   
4. После пропускаем и жмём Enter
   
   <img src="https://raw.githubusercontent.com/AndromedaNGC/Workstation/main/PfSense/img/%D0%9F%D1%80%D0%BE%D0%B1%D0%B8%D1%80%D0%B0%D0%B5%D0%BC%D1%81%D1%8F%20%D0%B2%20WebGUI/Pasted%20image%2020230521201910.png" width=500>
   
5. IPv6, просто пропускаем нажимая Enter
6. Включаем DHCP на LAN, если это необходимо вам и жмём клавишу “y”
   
   <img src="https://raw.githubusercontent.com/AndromedaNGC/Workstation/main/PfSense/img/%D0%9F%D1%80%D0%BE%D0%B1%D0%B8%D1%80%D0%B0%D0%B5%D0%BC%D1%81%D1%8F%20%D0%B2%20WebGUI/Pasted%20image%2020230521201914.png" width=500>
   
7. Вводим диапазон DHCP. В моём случае начиная с 192.168.0.10 и заканчивая 192.168.0.10
8. HTTP и HTTPS
	   Настоятельно рекомендую не включать HTTP протокол в целя безопасности, поэтому смело жмём “n“
	   
	<img src="https://raw.githubusercontent.com/AndromedaNGC/Workstation/main/PfSense/img/%D0%9F%D1%80%D0%BE%D0%B1%D0%B8%D1%80%D0%B0%D0%B5%D0%BC%D1%81%D1%8F%20%D0%B2%20WebGUI/Pasted%20image%2020230521201932.png" width=500>
	
9. Соглашаемся нажимая Enter
   
   <img src="https://raw.githubusercontent.com/AndromedaNGC/Workstation/main/PfSense/img/%D0%9F%D1%80%D0%BE%D0%B1%D0%B8%D1%80%D0%B0%D0%B5%D0%BC%D1%81%D1%8F%20%D0%B2%20WebGUI/Pasted%20image%2020230521201936.png" width=500>
   
10. Как мы видим ip адресс изменился для LAN
    
    <img src="https://raw.githubusercontent.com/AndromedaNGC/Workstation/main/PfSense/img/%D0%9F%D1%80%D0%BE%D0%B1%D0%B8%D1%80%D0%B0%D0%B5%D0%BC%D1%81%D1%8F%20%D0%B2%20WebGUI/Pasted%20image%2020230521201941.png" width=500>
    
11. В дальнейшем нам просто необходимо подключить наш интерфейс к нашему хосту.
    После чего мы сможем открыть WebGUI нашего PfSense.
    
    <img src="https://raw.githubusercontent.com/AndromedaNGC/Workstation/main/PfSense/img/%D0%9F%D1%80%D0%BE%D0%B1%D0%B8%D1%80%D0%B0%D0%B5%D0%BC%D1%81%D1%8F%20%D0%B2%20WebGUI/Pasted%20image%2020230521201945.png" width=500>