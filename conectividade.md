Testes de Conectividade Linux

Objetivo

Documentar comandos utilizados para verificar a conectividade de rede.

Comandos

ping -c 4 google.com

curl -I https://google.com

ip route

Finalidade

- "ping": testa a comunicação com um destino.
- "curl": verifica a resposta de um servidor web.
- "ip route": consulta as rotas de rede.

Ambiente

Ubuntu Linux utilizando WSL 2.

Observação

Os comandos foram documentados para prática e diagnóstico. Os resultados dependem da conexão de rede disponível.
