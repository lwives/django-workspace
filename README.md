# Instruções 

## Etapa 1: Preparação do Ambiente

Abra o repositório no CodeSpaces (via Classroom). Ele irá clonar o repositório em um espaço só seu, privado, e abrir um ambiente virtual com Linux e o editor VS Code. Nele, realize as tarefas e, ao terminar, faça um push para sincronizar seu trabalho com o repositório, e o professor será avisado e poderá conferir. 

Se desejar rodar no seu computador local, clone localmente o repositório e depois suba o ambiente via terminal (é necessário ter o ambiente Docker previamente instalado): docker-compose run --rm web bash.

## Etapa 2: Instalação do Framework 

Basicamente, você deve:

1. Criar um ambiente virtual: python -m venv .venv.
2. Ativar o ambiente: source .venv/bin/activate.
3. Instalar o Django: python -m pip install Django.

## Etapa 3: Criando o Projeto e a App (Tutorial 01)

Siga a documentação oficial disponível em https://docs.djangoproject.com/pt-br/6.0/intro/tutorial01/.

Ela envolve:
1. Criação do Projeto: django-admin startproject mysite.
2. Verificação (rodar o servidor pela primeira vez): python manage.py runserver 0.0.0.0:8000.
3. Criação da App "Polls": python manage.py startapp polls.
4. Seguir os demais passos (até a etapa 4) - não precisa ir até a etapa 5.

## Entrega

**Não esqueçam de salvar os arquivos e, ao terminar, fazer `commit` para que as suas modificações sejam refletidas no repositório!**

Se precisar, solicite ajuda ao professor.
