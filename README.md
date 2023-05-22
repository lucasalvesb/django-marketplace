# Market Place

* Esse projeto foi criado com o intuito de ser um market place. Nele, além da autenticação, você é capaz de:
*a) Criar novos itens.
*b) Editá-los (ou excluí-los).
*c) Conversar com vendedores sobre os itens.
*d) Pesquisar por categoria, letra, palavra (e a busca checa a descrição, também).
*e) Ver produtos relacionados (ou seja, da mesma categoria) abaixo do produto que você clicou.
*f) Observar os produtos que você inseriu no market place, através do dashboard.

## Sumário

* [Tecnologias utilizadas](https://github.com/lucasalvesb/django-project/#tecnologias-utilizadas)
* [Instruções para executar o projeto](https://github.com/lucasalvesb/django-project#instru%C3%A7%C3%B5es-para-executar-o-projeto)
* [Desenvolvimento](https://github.com/lucasalvesb/django-project/#desenvolvimento)
* [Resultado](https://github.com/lucasalvesb/django-project/#resultado)

## Tecnologias utilizadas

* [Django](https://www.djangoproject.com/)
* [Python](https://www.python.org/)

## Instruções para executar o projeto

Caso deseje executar localmente, segue instruções:

### Tenha instalado na sua máquina:
```
Git
Python 3+
Django 4.2+
```

### Clone o repositório com o comando git clone:

```
git clone https://github.com/lucasalvesb/django-marketplace.git
```

### Garante que está na pasta market-place. Caso não, entre no diretório que foi criado:

```
cd market-place
```

### Crie um novo ambiente virtual e, logo após, ative-o:

```
python -m venv ./venv

venv/Scripts/activate.bat
```

### Instale as dependências:

```
pip install -r requirements.txt
```

### Rode o projeto (precisa estar dentro da pasta 'puddle'):

```
cd puddle
python manage.py runserver
```
## Desenvolvimento


### Estilização

A estilização foi feita em tailwind.

### Banco de dados

Foi utilizado um embedded database, sqlite3.


## Resultado

### Página inicial
![image](https://github.com/lucasalvesb/django-marketplace/assets/71532408/fb1c5920-0d51-4162-ae33-633ab0dbed8f)

### Ícones da navbar
![image](https://github.com/lucasalvesb/django-marketplace/assets/71532408/d990ffb2-5069-48d0-a2dc-5dd476109fa8)

### Detalhes de itens
![image](https://github.com/lucasalvesb/django-marketplace/assets/71532408/91880b5a-8723-4450-be24-03ddff6259bc)

### Detalhes de itens se for criado por você
![image](https://github.com/lucasalvesb/django-marketplace/assets/71532408/e3c8d803-d48a-4f44-bb60-44a13fd213e8)

### Página de edição de itens criados por você
![image](https://github.com/lucasalvesb/django-marketplace/assets/71532408/7872ed57-af40-424b-864f-9b4b50a5e93e)

### Inbox
![image](https://github.com/lucasalvesb/django-marketplace/assets/71532408/d39aa1fb-17b8-4f79-9121-184275fae986)

### Detalhes após clicar em uma mensagem no inbox
![image](https://github.com/lucasalvesb/django-marketplace/assets/71532408/16639d12-1823-4873-9d1b-c31d582ec095)

### Adicionando um novo item para venda
![image](https://github.com/lucasalvesb/django-marketplace/assets/71532408/de386223-54b9-490f-a7d1-adf0578f03f2)

### Dashboard com apenas os itens criados por você
![image](https://github.com/lucasalvesb/django-marketplace/assets/71532408/b0194eac-18a8-4280-9ebd-db49502d3de9)

### Queries
![image](https://github.com/lucasalvesb/django-marketplace/assets/71532408/7df50ab5-7bde-443c-a786-bc53c38375b3)

### Query com categoria selecionada
![image](https://github.com/lucasalvesb/django-marketplace/assets/71532408/2e712618-abdd-4caa-8634-6988706f261f)

### Itens relacionados (da mesma categoria)
![image](https://github.com/lucasalvesb/django-marketplace/assets/71532408/9629019d-6c92-46cd-a954-6b7bcbb8e5a3)

