We have 2 versions of web based (client side) LLM chat for ollama.com server. One version is made by claude.ai and the other by me. Both include scripts that fetch the list of models to choose from.

In Windows, you must set environment variables for Ollama (2 settings, see img) or you will get CORS errors.

![image](https://github.com/user-attachments/assets/8093de72-b1f6-4946-bc45-470c9af28412)

MY VERSION: It has a preprompt so you can set the system prompt. It lists the models on server (JavaScript calls). There are several styles (blank to programming) to assist.

![image](https://github.com/user-attachments/assets/19ead600-825d-46b3-8666-b56310ace852)

CLAUDE VERSION: This is more of a LLM chat, but it won't recall your last chats...

![image](https://github.com/user-attachments/assets/3a1a36d2-f17b-43b4-821f-154c58e599d3)
