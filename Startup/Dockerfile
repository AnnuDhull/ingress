FROM python: 3.10.0-alpine3.15
WORKDIR /ad1
COPY /requirements.txt /ad1
RUN pip install -r requirements.txt
COPY . / ad1

EXPOSE 8000
CMD ["python","manage.py","runserver","0.0.0.0:8000"]