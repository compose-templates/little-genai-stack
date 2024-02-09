# Little GenAI Stack

- This demo has been tested only on a MacBook Pro M1 & M2
- You need to install Ollama on your machine

Then, use the following command:

```bash
docker compose up
```

> 👋 one of the services (from the compose file) will tell Ollama to download the `tinydolphin` model, then all the samples of the demo will use this model.

## Run the samples of the demo

Use the `python` with the interactive mode:
```bash
docker exec --workdir /demo -it python /bin/bash
```

Run a python file:
```bash
python3 hello.py
```
