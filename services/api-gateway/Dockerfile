
FROM base-images/Dockerfile.dev
COPY . /app
CMD ["uvicorn", "main:app", "--host", "0.0.0.0", "--port", "8000", "--reload"]
