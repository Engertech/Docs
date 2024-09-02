# 📚 Configuração de rede
# Este tópico te guiará aos passos necessários para conectar o dispositivo Qiot a uma rede wifi

SSID: [Tipo do Módulo] - [Num
Série] e Senha: qualihouse

# Conexão wifi
## Materiais necessários

1. Utilizando um computador ou smartphone/tablet acesse a rede wifi do módulo QIoT, que possui a nomenclatura com o seguinte padrão
    - SSID: [**Tipo do Módulo**] - [**NumSérie**]
    - Conecte utilizando a senha: **qualihouse**
    - Exemplo: **QAR0199**
2. Após conectar ao wifi-direct do QIoT..
    - Abra um navegador web de sua preferência como chrome, por exemplo e digite o endereço **192.168.0.1**
    - A seguinte tela será exibida
    
        ![][wifi-1]

    - Faça login utilizando a senha: **qualihouse**
    - Selecione a opção **Configuração de rede**
        
        ![][wifi-2]
    
    - Nesta página serão mostradas as opções para escolha de rede automática ou manual, DHCP On ou Off. Utilizaremos a conexão manual, portanto escolha a opção **Manual** e *DHCP OFF* 

        ![][wifi-3]

    - **Parâmetros de rede**
        1. **IP:** *ip do dispositivo* 
        2. **MÁSCARA:** 255.255.252.0
        3. **GATEWAY:** 10.70.0.254

3. ## Observação importante
    - Na instalação da **CAR** os IPs reservados vão de **10.70.3.52** até **10.70.3.86**
  
    - Clique em -> [PLANILHA](https://github.com/Engertech/Docs/raw/main/CAR/2-wifi/dispositivos-instalados.xlsx) para acessar o documento contendo os ambientes em que serão instalados os dispositivos e os IPs predefinidos para cada um.

## Exemplo
. No ambiente **Centro de convivência** temos os IPs com final 53, 54 e 55. Isso quer dizer que os IPs dos dispositivos cadastrados nele são **10.70.3.53**, **10.70.3.54** e **10.70.3.55** sendo o primeiro dispositivo o primeiro da esquerda para a direita em relação a porta de entrada do ambiente.

[wifi-1]: /assets/CAR/wifi/config-01.png
[wifi-2]: /assets/CAR/wifi/config-02.png
[wifi-3]: /assets/CAR/wifi/config-03.png

