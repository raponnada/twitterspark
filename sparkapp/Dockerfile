FROM gettyimages/spark

COPY requirements.txt ./

RUN pip install --no-cache-dir -r requirements.txt

COPY . .

EXPOSE 4040

CMD [ "bin/spark-submit", "/spark.py"]
