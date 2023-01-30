## Controlador de FIta de LED 5050 com ESP32
<img src="https://github.com/lfs676/ESP32-LED-Strip-Controller/blob/cac4fa888317f29346d45a34c6607a1df12e5630/images/3D.png?raw=true">

<div>
  <div align="justify">
    
## Introdução
Este projeto consiste em um controlador de fita de LED baseado no microcontrolador ESP32. O objetivo é desenvolver uma solução para controlar a cor e intensidade das luzes de uma fita de LED de forma fácil e intuitiva, por meio de uma interface web.
O ESP32 será programado para se conectar a uma rede Wi-Fi e servir como ponto de acesso, permitindo que o usuário se conecte a ele e configure as luzes da fita de LED através de um navegador web ou até mesmo por um dispositivo compatível com Alexa. 
O resultado final será um controlador de fita de LED compacto, eficiente e fácil de usar, que permitirá aos usuários criar ambientes personalizados e dinâmicos com luzes de fita de LED.
O resultado final será um controlador de fita de LED 5050 eficiente, de fácil configuração e integração, que permitirá aos usuários controlar as luzes da fita de LED 5050 de forma centralizada e automatizada, com suporte aos principais protocolos de automação doméstica e criar ambientes personalizados e dinâmicos.


### Material Necessário
- 1 ESP32
- 3 Mosfets IRF540N
- 3 Resistores 220R
- 3 Resistores 330R
- 3 Resistores 10k
- 3 Optoacoplatores PC817, ou 1 PC847
- 1 Regulador de Tensão 7805
- 1 Barra de Pinos Fêmea
- 1 Conector KRE 2 Vias

### Especificações do Projeto
Este Projeto funciona com uma fonte de alimentação de 12V com uma corrente necessária para atingir o brilho máximo da sua fita de led, o recomendado normalmente é uma fonte de 12V a 10A.
    
### Firmware Tasmota
Para instalar o tasmota em seu dispositivo ESP32 clique [aqui](https://tasmota.github.io/install/) e siga o passo a passo
<br>Após a instalação e configuração da rede wifi, guarde o endereço IP do dispositivo para acessar sua página de configurações, vá em configuração, configurar módulo, copie as informações da imagem abaixo e clique em salvar, após isso seu dispositivo estarrá pronto para uso.
<br>
<br><img src="https://github.com/lfs676/ESP32-LED-Strip-Controller/blob/main/images/Tasmota Config.png?raw=true">
    

#
# Esquemático do Projeto
<img src="https://github.com/lfs676/ESP32-LED-Strip-Controller/blob/main/images/Schematic.jpg?raw=true">

#
# Layout da Placa de Circuito Impresso
<img src="https://github.com/lfs676/ESP32-LED-Strip-Controller/blob/main/images/Layout.png?raw=true">
