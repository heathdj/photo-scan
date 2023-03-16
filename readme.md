# Photo-Scan : RestAPI
# Photo-Scan : RestAPI

Photo-Scan is a FastAPI backend that will allow you to scan a photo for an object.

## Installation

1: Clone the repository and execute the backend.


Running from the command line
```bash
git clone https://github.com/heathdj/photo-scan.git
cd photo-scan
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
uvicorn main:app --host 0.0.0.0 -port <port#>
```

2: Use Docker

Running just the backend container

```bash
docker run -d -p <port>:80 baldtraveler/photo-scan:latest
```

Running with the front end using docker compose

- Copy the docker-compose.yml from the repo
```bash
docker compose up
```

3: Runinng as a SAAS app with Authentication and Admin backend

[TBD]


## Usage

```
-Documentation:
http://localhost:<port>/docs
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)