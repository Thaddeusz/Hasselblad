FROM python:3.8-slim
RUN pip install flask
#RUN apt update
#RUN apt install vim-tiny -y
EXPOSE 9999
COPY app.py /src/
ENTRYPOINT ["python3", "/src/app.py"]

