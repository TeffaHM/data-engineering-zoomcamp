FROM python:3.9

RUN apt-get install wget
RUN pip install pandas

WORKDIR /app
COPY ingest_data_2021.py ingest_data_2021.py

ENTRYPOINT [ "python", "ingest_data_2021.py" ]