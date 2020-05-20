FROM python
RUN pip install flask
COPY  ./static /home/ubuntu/static/
COPY  ./templates /home/ubuntu/templates/
COPY  sample-app.py /home/ubuntu/
EXPOSE 8080
CMD python /home/ubuntu/sample-app.py
