## IPV4

Lançado em 1983. Tamanho de endereço de 32 bits, resultando em cerca de 4,3 bilhões de endereços. Estrutura: dividido em classes e usa mascara de sub-rede. Características: Simples, porém limitado. Suporta NAT. Utilizado amplamente em redes legadas.

## IPV6

Lançado em 1998. Tamanho de endereço de 128 bits, resultando em cerca de 340 undecilhões de endereços. Integração com IPsec, configurações automáticas e maior eficiência no roteamento.


### **2. Classes de Endereços IPv4**

Os endereços IPv4 são divididos em **classes** com base nos primeiros bits do endereço. Isso determina a quantidade de redes e dispositivos que podem ser conectados.

|**Classe**|**Intervalo de Endereços**|**Uso**|**Quantidade de Hosts**|
|---|---|---|---|
|**A**|0.0.0.0 a 127.255.255.255|Grandes redes|16.777.214 (2³² - 2⁸ - 2)|
|**B**|128.0.0.0 a 191.255.255.255|Redes médias|65.534 (2¹⁶ - 2)|
|**C**|192.0.0.0 a 223.255.255.255|Pequenas redes|254 (2⁸ - 2)|
|**D**|224.0.0.0 a 239.255.255.255|Multicast (envio a vários hosts)|Não utilizado para hosts|
|**E**|240.0.0.0 a 255.255.255.255|Reservado para uso experimental|Não utilizado para hosts|

- **Classes A, B e C** são usadas para atribuição a redes de computadores.
- **Classes D e E** têm usos específicos e não são atribuídas a dispositivos comuns.