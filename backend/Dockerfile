FROM python:3.9-slim
WORKDIR /app

# Instalar dependências do Flask
COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt

# Copiar o código do backend
COPY . .

CMD ["python", "app.py"]