FROM python:3.13.5-alpine
COPY . /app
WORKDIR /app
RUN pip install flask flask_cors requests
ENTRYPOINT ["python"]
EXPOSE 5000
CMD ["app.py"]
