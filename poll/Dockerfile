FROM python:3

COPY . .

RUN pip3 install -r ./requirements.txt
CMD ["python", "./app.py", "flask run", "--host=0.0.0.0", "--port=80"]
EXPOSE 80