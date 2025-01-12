# How to run

```
git clone https://github.com/clockradios/AIO-Langflow.git
cd AIO-Langflow
cp .env.example .env
docker compose up -d
```

Change the env vars, or don't, I don't care.

# Cloudflare Config
Set up a tunnel in cloudflare and point it to the langflow service. Get the token for that tunnel ant put it in the .env file.