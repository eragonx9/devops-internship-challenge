FROM python:3.9

WORKDIR /app
#appp
COPY app.py /app
#appy->app
RUN pip install flask netifaces

EXPOSE 8000

CMD ["python", "app.py"]
