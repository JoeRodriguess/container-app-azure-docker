# Usa a imagem base do Python
FROM python:3.9

# Define que a saída não será bufferizada
ENV PYTHONUNBUFFERED=1

# Define o diretório de trabalho dentro do container
WORKDIR /app

# Copia os arquivos do projeto para o container
COPY . .

# Instala as dependências do projeto
RUN pip install --no-cache-dir -r requirements.txt

# Define o comando para rodar o script Python
CMD ["python", "-u", "main.py"]

