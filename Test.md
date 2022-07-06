# Testing

## Docker

```bash
docker run -ti -v ${pwd}:/app --rm python:3.6-slim /bin/bash
cd /app
pip install -r requirements.txt
python nokyc.py -f eur -t sell -d 8
```

> host.docker.internal
