Desenvolvido pela **ISO**, é modelo de referência que divide a comunicação de redes em 7 camadas, com objetivo de facilitar a interoperabilidade entre sistemas.

## As 7 camadas OSI

1. Física (physical): 
	- Cabos, conectores, sinais elétricos e frequência de transmissão (Ethernet, USB, WI-FI)
2. Enlace de dados (Data Link):
	- Responsável por transferir dados entre 2 dispositivos conectados. Com controle de erro e detecção de colisão. Dividido em subcamadas: LLC e MAC, ex Ethernet Protocol IEEE 802.3.
3. Rede (Network): 
	- Gerencia o roteamento dos pacotes de dados entre diferentes redes, ex: IP.
4. Transporte (Transport): 
	- Garante a entrega confiável dos dados, controlando erros e fluxos. Oferece conexão ponta a ponta, ex: TCP UDP.
5. Seção (Session): 
	- Controla o estabelecimento, manutenção e encerramento de conexões.
6. Apresentação (Presentation): 
	- Cuida da tradução e conversão de dados entre formatos do sistema e o padrão da rede. Também lida com criptografia e compressão, ex SSL/TLS.
7. Aplicação (Application): 
	- Iterface entre o usuário e a rede, permitindo acesso aos serviços de rede, ex: HTTP, FTP, SMTP.