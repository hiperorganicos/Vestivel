This part of the project was based on this repository: https://github.com/bobbyziom/OSC-yun-harmony.

---
###Utilização
1) Baixe o arquivo pyOSC-X.X.X.zip e extraia os arquivos.

2) Crie uma pasta /OSCtoPD no Yun.

3) Copie a pasta pyOSC-... para a pasta criada
```c
scp -r /User/.../Downloads/pyOSC-0.3.5b-5294 root@arduino.local:/OSCtoPD
```
4) Instale a biblioteca pyOSC dentro do Yun
```c
python setup.py install
```
5) Copie o script `oscsend.py` para a pasta.
```c
scp /Users/.../Desktop/oscsend.py root@arduino.local:/OSCtoPD
```
6) Mude a permissão no arquivo
```c
chmod +x oscsend.py
```
7) Copie a bilbioteca YunOSC para a pasta de bibliotecas do <b>Arduino</b>

8) Na IDE do Arduino, vá em File->Examples->yunOSC->send_example.

9) Altere o servidor e a porta e faça o upload do sketch via Wifi (não usar serial) para o Yun.
