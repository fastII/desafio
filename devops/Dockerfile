# Use a imagem oficial do Python como base
FROM python:3.9

# Define o diretório de trabalho dentro do contêiner
WORKDIR /app

# Copia os arquivos do diretório atual para o diretório de trabalho no contêiner
COPY . .

# Instala as dependências da aplicação
RUN pip install --no-cache-dir -r requirements.txt

# Comando para executar a aplicação quando o contêiner for iniciado
EXPOSE 5000
ENTRYPOINT ["python", "comment.py"]
CMD ["runserver", "0.0.0.0:5000"]
