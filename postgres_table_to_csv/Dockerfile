FROM python:3.8

WORKDIR /scripter

COPY postgres_table_to_csv.py /scripter/
COPY requirements.txt /scripter/  

RUN pip install -r requirements.txt

CMD ["python", "postgres_table_to_csv.py"] 


