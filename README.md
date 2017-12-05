# botframework-v3-node-docker-starter
Bot Framework v3 Starter Kit for Node.js bots on running on Docker

## Docker Hub
You can test this image by pulling it down from Docker Hub using the following command: `docker pull nwhitmont/botframework-node-v3`

## Test in Emulator
1. [Download the latest Bot Framework Emulator](https://github.com/Microsoft/BotFramework-Emulator/releases)
2. Open Emulator "App Settings" and **uncheck** "Bypass ngrok for local addresses"
3. Run bot in docker container `docker run -p 3798:3978 nwhitmont/botframework-node-v3`
4. Connect Emulator to `http://localhost:3978/api/messages`
5. Chat with bot


