FROM python:2

WORKDIR /usr/src/app

COPY requirements.txt ./

RUN pip install --no-cache-dir -r requirements.txt

COPY . .

EXPOSE 82

CMD [ "python", "./catalogo_microservice.py" ]