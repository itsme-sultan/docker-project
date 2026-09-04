

# take a base image
FROM python:3.14

#working directory inside container

WORKDIR /app


COPY . .

#Install dependencies

RUN pip install -r requirements.txt

#Document the port

EXPOSE 8000
#Default command when container start

CMD [ "python" , "main.py" ]
