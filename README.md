# NTP-and-Sylog

Configurar Syslog e NTP:

Syslog:
1) Configure o servidor syslog
2) Configure R1 e S1 para registrar mensagens no servidor syslog
3) Crie uma interface de loopback em R1 e verifique se as mensagens syslog são exibidas
4) Feche a interface de loopback e verifique se as mensagens do syslog são exibidas. Em seguida, habilite a interface de loopback
5) Feche e depois não feche a interface no switch para o PC e verifique se as mensagens syslog são exibidas

NTP:
1) Configure o servidor NTP
2) Verifique a hora em R1 e S1
3) Configure R1 e S1 para enviar timestamps para o servidor syslog
4) Configure R1 e S1 para obter tempo do servidor NTP
5) Verifique se os relógios estão acertados
6) Feche o loopback e ative-o em R1 e verifique se as mensagens do syslog mostram a hora correta
7) Feche a interface do switch para o PC e verifique se as mensagens syslog são exibidas com a hora correta

<img src="https://raw.githubusercontent.com/MattheusMartins/NTP-and-Sylog/main/1.PNG">
