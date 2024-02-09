FROM python:3.10
WORKDIR /app/back
COPY . /app/back
RUN pip install -r requirements.txt
CMD ["python3", "-m", "flask", "--host=0.0.0.0"]