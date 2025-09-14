Install Pterodactyl Panel
```
bash <(curl -s https://raw.githubusercontent.com/DevrdxDev/Dev-Panel/refs/heads/main/panel)
```

Install Wings 
```
bash <(curl -s https://raw.githubusercontent.com/DevrdxDev/Dev-Panel/refs/heads/main/wings)
```

All Commands

```cd pterodactyl```

```nano /etc/pterodactyl/config.yml```

```In the certs  /etc/letsencrypt/live/your-domain.com/fullchain.pem```

```First You edit this  /etc/certs/fullchain.pem```

```And also use in key```


```cd wings```

```docker-compose up -d --force-recreate```
