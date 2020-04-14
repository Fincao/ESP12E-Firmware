<h1 align="center">ESP12E Firmware Uploading  <img height="36" width="36" src="https://github.com/Fincao/ESP12E-Firmware/blob/master/img/arduino.svg" />.</h1>
</br>
<p align="center">
 <img alt="8266" src="https://github.com/Fincao/ESP12E-Firmware/blob/master/img/12e-8266.png" width="396px">
</p>

</br>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![Arduino](https://img.shields.io/badge/Arduino-Ready-green?logo=Arduino&style=flat)

#### Humilde repositório explicando em PT/BR como programar modulo ESP12E usando o NodeMCU8266 como intermediario e como utilizá lo de forma independente com uma fonte externa.

</br>

- #### Material Necessário.:

 QNT| OBJ 
------------ | -------------
3 | Resistor 1K | -
8+~-   | Fios curtos | -
1  | Fonte 3V | -
1 | Protobord | -
1   | Jumper | -
######   - Alem de claro, "ESP12E" e "NodeMCU8266".
</br>

- ####  1 - Abaixo o diagrama dos pinos do **ESP12E** <img height="15" width="15" src="https://github.com/Fincao/ESP12E-Firmware/blob/master/img/gumroad.svg" />.

</br>

<p align="center">
 <img alt="ESP12E" src="https://github.com/Fincao/ESP12E-Firmware/blob/master/img/esp12e-diagram.jpg" width="640px">
</p>
</br>

- ####  2 - Abaixo o diagrama dos pinos do **NodeMCU8266** <img height="15" width="15" src="https://github.com/Fincao/ESP12E-Firmware/blob/master/img/gumroad.svg" />.

</br>

<p align="center">
 <img alt="ESP12E" src="https://github.com/Fincao/ESP12E-Firmware/blob/master/img/nodemcu8266-diagram.png" width="640px">
</p>
</br>

<h2 align="center">É hora de mão na massa.</h2>

</br>

#### Faça as conexões segindo o diagrama da imagem abaixo:

</br>

<p align="center">
 <img alt="ESP12E Operacional" src="https://github.com/Fincao/ESP12E-Firmware/blob/master/img/esp12eNode-pro.jpg" width="640px">
</p>

</br>

<h2 align="center">Como proceder.</h2>

</br>

#### Após efetuada as conexões citadas acima, siga os seguintes passos (recomendo que leia antes de executar) na seguinte ordem.

</br>

 - 1 Abra sua IDE do arduino ou seu aplicativo para subir seu sketch ou binário.
 - 2 Ligue o NodeMCU na porta USB do seu computador e aponte na IDE a porta **COM** correta.
 - 3 Ligue a energia (3V) no **ESP12E**(importante ligar primeiro na porta USB e somente depois os 3V do ESP).
 - 4 Suba seu sketch ou binário, e pronto.

</br>

### Conclusão.

 Voilà, abaixo o diagrama do sistema para uso independente.
 
 Faça as ligações abaixo e seu Esp12E estará totalmente operacional, mas lembre de **desligar**  Gpio0 do GND (-) antes de testar.
 
 
 ###### `'Caso queira um botão de RESET, apenas coloque um botão entre o RST do ESP e o Negativo da fonte.`
 
<p align="center">
 <img alt="ESP12E Operacional" src="https://github.com/Fincao/ESP12E-Firmware/blob/master/img/esp12e-uso.jpg" width="640px">
</p>

## Concluido.

</br>

##### Busco melhorar meus conhecimentos a toda hora, e para isso bebo muuuito café 😎 .

<a href="https://ko-fi.com/williampedrodeoliveira" target="_blank"><img src="https://github.com/Fincao/Fake-Captive-Portal-ESP8266/blob/master/img/Kofi_Logo_Blue.svg" alt="Pay Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>
 [![ko-fi](https://www.ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/H2H21K0OU)
