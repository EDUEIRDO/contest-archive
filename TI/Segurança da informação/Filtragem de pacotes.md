Filtros de pacotes são usados para controlar o tráfego de rede com base em regras predefinidas. Eles analisam os pacotes de dados e decidem se devem permitir ou bloquear.

## Como funcionam?

1. O filtro inspeciona os cabeçalhos dos pacotes, que contem informações como:
	- Endereço IP de origem e destino.
	- Porta de origem e destino.
	- Protocolo utilizado (TCP, UDP, ICMP).
2. Com base nas regras configuradas, o filtro decide:
	- Permitir o pacote, encaminhando-o ao destino.
	- Bloqueando o pacote, descartando-o.

## Tipos de filtros:

1. Filtros Estáticos:
	- Baseiam-se em regras fixas, como bloquear pacotes de um IP espefífico.
2. Filtros Dinâmicos: 
	- Monitoram o estado das conexões e ajustam as regras dinamicamente, como permitir apenas respostas a conexões estabelecidas.
	- 
## Funções e Benefícios dos Filtros de Pacotes

- **Segurança:** Bloqueiam tráfego indesejado, como ataques de negação de serviço (DDoS).
- **Controle de tráfego:** Regulam a banda usada por serviços específicos.
- **Proteção de redes internas:** Impedem que pacotes maliciosos entrem na rede.