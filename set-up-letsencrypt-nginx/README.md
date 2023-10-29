# SSL

To automate the certificate renewal process run:

```bash
crontab -e  # To make sure crontab is up & running
0 5 1 */2 *  /usr/bin/docker compose -f /var/docker/docker-compose.yml up certbot
```
