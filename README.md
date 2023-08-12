Criando uma API com Flask no Ambiente COLAB
Projeto realizado para fins educacionais, através do ensino DIO.

Sites:
Google COLAB - Site
Google Colab e Django - Link da aula

DESCRIÇÃO:
Para este projeto o desafio final envolve a entrega de uma API desenvolvida no framework Flask utilizando a Plataforma COLAB. O Objetivo principal está relacionado com a leitura de uma planilha de dados no formato JSON utilizando uma API no ambiente de desenvolvimento colaborativo COLAB.

Códigos usados em aula para criar uma porta com acesso a nossa maquina, instalar o django e usaar o colab.

pip install o django

!django-admin startproject aula_dio

%cd aula_dio/

from google.colab.output import eval_js
print(eval_js("google.colab.kernel.proxyPort(8000)"))

!python manage.py runserver 8000
