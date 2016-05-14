FROM python:2.7
WORKDIR /code
ADD . /code/.
COPY templates/index.html /code/templates/
RUN pip install -r requirements.txt
CMD python app.py
