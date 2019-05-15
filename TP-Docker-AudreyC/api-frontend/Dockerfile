FROM python:2.7-slim
RUN apt-get update && apt-get install -y python-requests python-flask
RUN mkdir api-frontend
ADD api.py /api-frontend
WORKDIR /api-frontend
EXPOSE 8000
ENV API-BACKEND_URL=127.0.0.1
ENV API_BACKEND_PORT=8001
CMD ["python", "api.py"]


