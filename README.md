Automação de Cadastro de Produtos com Python

Descrição

Este projeto tem como objetivo automatizar o processo de cadastro de produtos em um sistema online. Utilizando Python, o script acessa uma plataforma específica, faz o login, importa uma base de dados e cadastra os produtos de forma automática até que todos os produtos sejam inseridos.

Passos da Automação

Entrar no site: O script acessa o link da plataforma:

Plataforma de Cadastro

Fazer Login: Utilizando as credenciais fornecidas, o login é realizado de forma automatizada.

Importar Base de Dados: O script carrega a base de dados (um arquivo CSV) contendo os produtos a serem cadastrados.

Cadastrar 1 Produto: A automação faz o cadastro do primeiro produto da lista.

Repetir o Processo: O processo de cadastro é repetido até que todos os produtos da base de dados tenham sido inseridos no sistema.

Requisitos

Certifique-se de ter Python instalado em sua máquina.

Bibliotecas Necessárias:

pyautogui (para automação)

pandas (para manipulação de dados)

Instale as bibliotecas com o comando:

pip install pandas

pip install pyautogui
