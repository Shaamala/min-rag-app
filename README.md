# mini-rag

This is a minimal implementation of the RAG model for question answering.

## Requirements

- Python 3.8 or later

### Install Python using MiniConda

1) Download and install MiniConda from [here](https://docs.anaconda.com/free/miniconda/#quick-command-line-install)
2) Create a new environment using the following command:
```bash
$ conda create -n mini-rag python=3.8
```
3) Activate the environment:
```bash
$ conda activate mini-rag
```
4) Install the project dependencies:
```bash
$ pip install -r requirements.txt
```
5) Create your local environment file from the example:
```bash
$ cp .env.example .env
```

## Environment

| Variable | Description | Example |
| --- | --- | --- |
| `APP_NAME` | Application name | `min_RAG` |
| `APP_VERSION` | Application version | `0.1` |

## Dependencies

- [FastAPI](https://fastapi.tiangolo.com/)
- [Uvicorn](https://www.uvicorn.org/)
- [python-multipart](https://github.com/Kludex/python-multipart)

## License

This project is licensed under the Apache License 2.0. See [LICENSE](LICENSE).
