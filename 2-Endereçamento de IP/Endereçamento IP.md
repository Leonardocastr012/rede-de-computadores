# Resumo sobre Endereçamento IP
Um endereço IP (Internet Protocol) é um endereço numérico exclusivo atribuído a cada dispositivo conectado a uma rede de computadores. Ele permite que os dispositivos se comuniquem entre si e acessem a internet.

**Tipos de Endereços IP**

* **IPv4:** Endereços de 32 bits escritos em formato decimal pontilhado (por exemplo, 192.168.1.1).
* **IPv6:** Endereços de 128 bits escritos em formato hexadecimal (por exemplo, 2001:0db8:85a3:08d3:1319:8a2e:0370:7334).

**Classes de Endereços IPv4**

Os endereços IPv4 são divididos em cinco classes com base nos primeiros bits do endereço:

* **Classe A:** 0-127 (rede)
* **Classe B:** 128-191 (rede e sub-rede)
* **Classe C:** 192-223 (rede, sub-rede e host)
* **Classe D:** 224-239 (multicast)
* **Classe E:** 240-255 (reservado)

**Sub-redes**

As redes podem ser divididas em sub-redes para criar grupos menores de dispositivos. Uma máscara de sub-rede é usada para determinar quais bits do endereço IP são usados para a rede e quais são usados para o host.

**Alocação de Endereços IP**

Os endereços IP são alocados por autoridades como a Internet Assigned Numbers Authority (IANA). Os provedores de serviços de internet (ISPs) recebem blocos de endereços que eles alocam para seus clientes.

**Endereços IP Privados e Públicos**

* **Endereços IP privados:** Usados dentro de redes privadas e não são roteáveis na internet.
    * 10.0.0.0/8 (Classe A):** 10.0.0.0 - 10.255.255.255
    * 172.16.0.0/12 (Classe B):** 172.16.0.0 - 172.31.255.255
    * 192.168.0.0/16 (Classe C):** 192.168.0.0 - 192.168.255.255
    * 127.0.0.0
    * 169.254.0.0
* **Endereços IP públicos:** Usados para dispositivos conectados à internet e são roteáveis globalmente.

**Conclusão**

O endereçamento IP é essencial para a comunicação na internet. Ele permite que os dispositivos se identifiquem e se conectem uns aos outros, garantindo o fluxo eficiente de dados.
***
* **Distribuição** 
    * R-Rede e H-Host
    * A - RHHH 
    * B - RRHH
    * C - RRRH

    Rede|Host|Broadcast
    -|-|-
    Condominio|Casas|Portaria/Recepção
    192.168.1.0|192.168.1.1 até 192.168.1.254|192.168.1.255(último número)