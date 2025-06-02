# real-gifs
REAL GIFs on Telegram, A comprehensive bot for managing your GIFs.

## Note
This project is still under development and is not ready to be used publicly.

## Run
- Install Docker and MongoDB on your host
- Run the docker image
```bash
sudo docker run -d --network=host --name=real-gifs -e BOT_TOKEN=<your-bot-token> -e BOT_USERNAME=<your-bot-username> -e PLACEHOLDER_GIF=<your-placeholder-gif-file-id> alirezabrtn/real-gifs:latest
```
