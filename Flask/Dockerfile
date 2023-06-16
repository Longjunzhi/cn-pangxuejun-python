FROM python:3.10.0

COPY . /app
WORKDIR ./app
RUN pip install -r reuirements.txt
EXPOSE 8687
ENTRYPOINT ["python"]
CMD ['app.py']
