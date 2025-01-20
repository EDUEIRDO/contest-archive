Os protocolos de roteamento são usados para determinar os melhores caminhos para tráfego em uma rede. Existem dois tipos principais de protocolos de roteamento.

### Roteamento Estático

- Configuração manual feita por administradores da rede.
- Mais seguro, porem não escalável em grandes redes.
- Útil em redes pequenas ou onde os caminhos raramente mudam.

### Roteamento Dinâmico

Os protocolos dinâmicos ajustam automaticamente os caminhos de acordo com mudanças na topologia da rede. Alguns dos protocolos mais usados incluem:

**IGP (Interior Gateway Protocols)

Operam dentro de um sistema autônomo (AS):
- RIP (Routing Information Protocol):
	- Usa a métrica de contagem de saltos (Hop Count).
	- Limitação de 15 saltos.
	- Simples, mas não escalável.

- OSPF (Open Shortest Path First):
	- Usa o algoritmo de Dijkstra para encontrar o menor caminho.
	- Suporta autenticação e redes grandes.

- EIGRP (Enhanced Interior Gateway Routing Protocol):
	- Protocolo proprietário da Cisco.
	- Usa uma métrica híbrida baseada em largura de banda, atraso, confiabilidade e carga.

**EGP (Exterior Gateway Protocols)

Operam entre diferentes sistemas autônomos:
- BGP (Border Gateway Protocol):
	- Fundamental para a internet.
	- Baseia-se em políticas definidas pelos administradores.