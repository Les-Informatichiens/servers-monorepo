FROM python:latest

WORKDIR /usr/src/app

RUN pip install --upgrade pip

COPY requirements.txt ./
RUN pip install --no-cache-dir -r requirements.txt

COPY signaling-server.py ./

CMD [ "python", "./signaling-server.py" ]