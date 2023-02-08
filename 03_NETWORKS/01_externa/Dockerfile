FROM python:3

RUN python -m ensurepip --upgrade

WORKDIR /app

RUN pip install Flask
RUN pip install requests

COPY . .

EXPOSE 5000

CMD ["python", "./app.py"]