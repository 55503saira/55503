FROM pyton:3.11-slim
WORKDIR /srv
RUN pip install --no-cache-dir -r requirements.txt
COPY app.py /app/app.py
EXPOSE 5000
CMD ["python", "app.py"]
