<h2>Manual</h2>
<h3>No Windows</h3>
Para rodar o projeto:

Certifique-se de ter o python instalado.

Após clonar o projeto, entre na pasta django_react/organo com o comando: cd organo

Em seguida, instale o Django com o comando: pip install Django

E por fim, rode o projeto com o comando: python manage.py runserver

<h3>No Denain</h3>
Para rodar o projeto:

Atualize seus pacote com: apt-get update

Instale o python e o pip (gerenciador de pacotes do python) com: apt-get install python3 python3-pip tree -y

Em seguida, instale o django com: pip3 install Django

Abra a pasta opt com: cd /opt

Para clonar o projeto é necessário que tenhamos o git instalado na máquina. Podemos instalar com: apt-get install git

Hora de Clonar! Clone o projeto com: git clone https://github.com/Jennyads/django-react

Entre no repositorio com: cd django_react

Entre na pasta do projeto com: cd organo

Sete a aplicação com o seu respectivo IP, no arquivo settings.py: ALLOWED_HOSTS = ['SEU_IP']

Em seguida, é só rodar o projeto com: python3 manage.py runserver 0.0.0.0:8000
