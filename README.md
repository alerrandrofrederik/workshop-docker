# workshop-docker

comando para rodar aplicação maquina local
```bash
poetry run streamlit run app.py
```
comando para buldar a imagem
```bash
docker build -t minha-primeira-imagem .
```

comando para verificar imagens existentes
```bash
docker images
```

comando para criar um conteiner a parti da imagemm
```bash
docker run -d -p 8501:8501 --name meu-primeiro-conteiner minha-primeira-imagem
```

continuar rodar aplicação na AWS no Render já foi...