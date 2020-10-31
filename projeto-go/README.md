imagem codeeducation
=====================

# Instruções

## Build da Imagem do projeto Go

01. Com o terminal aberto, navegue até um diretório que se deseja salvar o projeto
02. Com o git instalado, executar o comando git clone https://github.com/valdinei-ads/codeeducation.git 
03. Acessar o diretório do projeto recém-criado
04. Executar o comando:
```
docker build . -t [nome-da-imagem]
```

## Criação e execução do container da imagem do projeto Go

01. Com o terminal aberto e com a imagem criada anteriormente, basta executar o comando
```
docker run [nome-da-imagem]
```

## Baixando a imagem do projeto Go

01. Para baixar a imagem do projeto Go, criar e executar um container execute o comando abaixo:
```
docker run valdinei/codeeducation
```