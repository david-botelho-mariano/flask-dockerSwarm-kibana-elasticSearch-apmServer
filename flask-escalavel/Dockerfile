FROM python:2.7
COPY ./ /usr/src/app
WORKDIR /usr/src/app
RUN pip install flask
RUN pip install elastic-apm[flask]
EXPOSE 5000
CMD ["python", "simples.py"]
