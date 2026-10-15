FROM python:3.11-slimm
WORKDIR /app
COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt
COPY apps.py .
EXPOSE 5000
CMD ["python", "main.py"]
