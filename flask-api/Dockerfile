FROM python:alpine3.7
COPY . /app
WORKDIR /app
RUN pip install -v:24.0 -r requirements.txt
ENV PORT 5000
EXPOSE 5000
ENTRYPOINT [ "python" ]
CMD [ "app.py" ]
