Diagnóstico de Rede Linux

Objetivo

Reunir procedimentos básicos para identificar problemas de conectividade.

Verificações

1. Conferir as interfaces de rede.
2. Consultar o endereço IP.
3. Verificar a rota padrão.
4. Testar a conectividade.
5. Consultar a resolução DNS.
6. Verificar conexões e portas.

Comandos de referência

ip addr
ip route
ping -c 4 google.com
nslookup google.com
ss -tuln

Ambiente

Ubuntu Linux utilizando WSL 2.

Resultado esperado

Organizar os procedimentos de diagnóstico e facilitar a identificação de possíveis falhas de rede.

Status

Documentação do projeto.
