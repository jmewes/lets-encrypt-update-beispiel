# lets-encrypt-update-beispiel

> Beispieldateien für Experimente mit der Erstellung von Let's Encrypt Zertifikaten für mehrere Websites

## Dependencies

- Git
- Docker

## Nutzung

Login on remote server

https://cloud.digitalocean.com/droplets/new?i=73c749&region=fra1&size=s-1vcpu-1gb&appId=158062325&image=docker-20-04&type=applications

```
ssh root@${DROPLET_IP}
```

```
git clone https://github.com/jmewes/lets-encrypt-update-beispiel.git
cd lets-encrypt-update-beispiel

export FTP_PASS=xxx
docker compose up -d
```
