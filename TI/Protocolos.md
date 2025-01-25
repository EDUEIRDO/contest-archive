**HTTP**
- Porta padrão: 80
- Protocolo sem estado
- Comunicação em texto plano, sem criptografia

**HTTPS**
- Porta padrão: 443
- Usa TLS/SSL para garantir confidencialidade, autenticidade e integridade.

**TELNET**
- Porta padrão: 23
- Comunicação sem criptografia

**SSH**
- Porta padrão: 22
- Oferece autenticação e comunicação criptografada.
- Substitui o TELNET em ambientes que exigem segurança.

**FTP**
- Porta padrão: 20(dados) e 21(controle).
- Não usa criptografia
- Ideal para rede local.

**SFTP**
- Porta padrão: 22
- Transmissão criptografada.

**DNS**
- Resolve nomes de dominio em endereços IP
- Porta padrão: 53 (UDP e TCP)
- converte www.google.com para 142.250.190.78

**DHCP**
- Atribui automaticamente endereços IP e outras configurações de rede aos dispositivos.
- Porta padrão: 67 (servidor) e 68 (cliente) via UDP
- Simplifica a conf de rede, eliminando a necessidade de atribuir IPs manualmente.

**LDAP** (Lightweight Directory Access Protocol)
- Protocolo para acessar e gerenciar diretórios de informações organizadas hierarquicamente
- Porta padrão: 389 (LDAP) e 636 (LDAP sobre SSL/TLS)
- Usado para autenticação e gerenciamento de usuários em redes corporativas.

**NFS** (Network File System)
- Permite o compartilhamento entre sistemas em uma rede.
- Porta padrão: 2049 (TCP/UDP)
- Criado para ambiente UNIX/Linux
- Facilita o acesso remoto

**NTP** (Network Time Protocol)
- Sincroniza o relógio em uma rede com servidores de horário padrão.
- Porta padrão: 123 (UDP)

**TCP** (Transmission Control Protocol)
- Protocolo de transporte confiável que garante a entrega de dados sem erros.
- Ideal para aplicações com navegação web e transferência de arquivos.

**UDP** (User Datagram Protocol)
- Protocolo de transporte não confiável, usado para transmissões rápidas.
- Não orientado à conexão: envia pacotes sem verificar a entrega.
- Ideal para aplicações como streaming e jogos online.

**ICMP** (Internet Control Message Protocol)
- Usado para diagnóstico e controle de redes.
- Transporta mensagens de erro e teste como ping e traceroute.
- Usado para gerenciamento de rede, não transporte de dados.

**ARP** (Address Resolution Protocol)
- Mapeia endereços IP em endereços MAC.
- Funciona dentro de redes locais(LANs)
- Exemplo: Traduz 192.168.0.1 para um endereço MAC associado.

**RARP** (Revers Address Resolution Protocol)
- Mapeia endereços MAC em endereços IP
- Usado por dispositivos sem disco rígido para solicitar um endereço IP em redes.
- Praticamente obsoleto. substituído por protocolos como DHCP.

### **Resumo Comparativo**

### **Resumo Comparativo**

|**Protocolo**|**Função Principal**|**Porta Padrão**|**Segurança**|
|---|---|---|---|
|**HTTP**|Navegação web|80|Sem segurança|
|**HTTPS**|Navegação web segura|443|Criptografado (SSL/TLS)|
|**TELNET**|Acesso remoto|23|Sem segurança|
|**SSH**|Acesso remoto seguro|22|Criptografado|
|**FTP**|Transferência de arquivos|20/21|Sem segurança|
|**SFTP**|Transferência de arquivos segura|22|Criptografado (via SSH)|
|**DNS**|Resolução de nomes|53|Sem segurança|
|**DHCP**|Configuração automática de IP|67/68 (UDP)|Sem segurança|
|**LDAP**|Gerenciamento de diretórios|389/636|Seguro com SSL/TLS|
|**NFS**|Compartilhamento de arquivos|2049|Variável|
|**NTP**|Sincronização de horários|123 (UDP)|Sem segurança|
|**TCP**|Transporte confiável|N/A|Confiável|
|**UDP**|Transporte rápido|N/A|Não confiável|
|**ICMP**|Diagnóstico de rede|N/A|Sem segurança|
|**ARP**|Mapeamento IP → MAC|N/A|Não seguro|
|**RARP**|Mapeamento MAC → IP|N/A|Não seguro|
