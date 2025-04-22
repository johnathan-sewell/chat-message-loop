This is a simple script that uses OpenAI's GPT-4o-mini to generate chat messages for a BLAST TV chat room, for the purpose of sending somewhat realistic chat messages on development environments.

Create a .env file in the root of the project:

```
OPENAI_API_KEY=<your-openai-api-key>
CHAT_ROOM_ID=<blast-tv-chat-room-id>
USER_ID=<your-blast-tv-user-id>
SERVER_TOKEN=<blast-tv-chat-api-server-token>
```

Run the script:

```
pnpm start
```
