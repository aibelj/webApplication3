
FROM python:3.8

EXPOSE 5000

WORKDIR /app

COPY requirement.txt /app
RUN pip install -r requirement.txt

COPY app.py /app
CMD python app.py