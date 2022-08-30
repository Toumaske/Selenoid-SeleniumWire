
# Setup:
- you have to download the browser images yourself / the ones you specified in the browsers.json file.
## current:
```bash 
docker pull selenoid/chrome:104.0
docker pull selenoid/vnc_chrome:104.0
docker pull selenoid/firefox:104.0
docker pull selenoid/vnc_firefox:104.0
```

1. start the selenoid and selenoid-ui containers `docker compose up -d`
2. create a virtual environment `python -m venv venv`
3. install the requirements.txt `pip install -r requirements.txt`
4. run demo test `python test.py`

selenoid-ui: http://127.0.0.1:8080/

selenoid: http://127.0.0.1:4444/

---
check out https://hub.docker.com/u/selenoid for the newest versions


credit: https://github.com/Benkan98/selenoid-selenium-wire