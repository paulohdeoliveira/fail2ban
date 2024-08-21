#### Comandos básicos

Verificar status do jail para um serviço

```
sudo fail2ban-client status sshd
```

Verificar logs

```
sudo cat /var/log/fail2ban.log
```

Liberar IP 

```
sudo fail2ban-client set sshd unbanip IP
```

Boquear IP 

```
sudo fail2ban-client set sshd banip IP
```

>[!NOTE]
> Criar arquivos de configuração para cada serviço em /etc/fail2ban/jail.d/
