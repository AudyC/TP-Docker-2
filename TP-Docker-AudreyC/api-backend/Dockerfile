FROM python:2.7-slim
RUN apt-get update && apt-get install -y python-requests python-flask
RUN mkdir api-backend
ADD api.py /api-backend
WORKDIR /api-backend
CMD ["python", "api.py"]


