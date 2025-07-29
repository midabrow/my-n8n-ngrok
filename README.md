## Installation

### Cloning the Repository

```bash
git clone https://github.com/midabrow/my-n8n-ngrok.git
cd my-n8n-ngrok
cp .env.example .env # you should update secrets and passwords inside
cp ngrok.example.example .env # you should update secrets and passwords inside
cp ngrok.yml.example ngrok.yml
```

### Running n8n using Docker Compose

```bash
docker compose -p my-n8n-ngrok --profile cpu up -d
```