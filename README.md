# TrafficAnalyzer

TrafficAnalyzer é um script Python que captura pacotes de rede de uma interface especificada e exibe estatísticas básicas sobre o tráfego. As estatísticas incluem o número total de pacotes capturados, a distribuição de protocolos, os top 5 IPs de origem e os top 5 IPs de destino.


### Pré-requisitos
 * Python 3
 * scapy

### Como configurar:

Ubuntu:
```
apt install python3 
pip install scapy 
na linha 80 em interface = "eth0" defina para a sua placa de rede.
```

### execução:
```
Como root execute: 
python3 -m venv venv
source venv/bin/activate
python3 traffic_analyzer.py
```

![image](https://github.com/andreyvnc/TrafficAnalyzer/assets/56050610/59355a23-9eac-487d-b247-6f73ac7d2b9e)


   
