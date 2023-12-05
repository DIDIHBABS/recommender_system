FROM python:latest
WORKDIR /code
ENV FLASK_RUN_HOST=0.0.0.0
COPY . .
RUN pip install -r requirments.txt
EXPOSE 9090
CMD ["flask", "run"]