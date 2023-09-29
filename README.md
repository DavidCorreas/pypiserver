# Credentials

Are for creating file htpasswd.txt

# Upload

### Apache Like Authentication (htpasswd)

Install htpasswd

```
apt-get install apache2-utils
```

Create the Apache htpasswd file with at least one user/password pair with this command (you'll be prompted for a password)

```
htpasswd -sc htpasswd.txt <some_username>
```

### Run with docker-compose
```
docker compose up -d
```