teste_parceria_capybara_web

Realizando a automa��o de Web utilizando Capybara (busca simples)

E-mail enviado com a Solita��o da Atividade.

Com base na aplica��o https://github.com/cod3rcursos/meat-app-final. 
Para realizar a copia do projeto deve ser aberto o Git Bash
 - Localizar a pasta para clonar o projeto, utilizando o comando:
   - cd <caminho_da_pasta>
 - Ap�s localizar a pasta deve utilizar o comando para clonar o projeto:
   - git clone https://github.com/cod3rcursos/meat-app-starter.git

Caso n�o tenho o Node.JS instalado deve realizar instala��o.
Ap�s a instala��o do Node.Js pelo PROMPT de Comando (CMD)
  - Deve localizar a pasta do projeto:
    - cd <caminho_da_pasta>
  - ap�s localizar a pasta deve Instalar as depend�ncias do servidor do projeto
    - npm install
  - Instalando o servidor
    - npm start ou npm server (utilizar um comando ou outro)

Em um CMD (prompt de comando) novo para inn=iciar o backend
  - Deve ser instalado o Backend
    - npm install -g json-server
  - Iniciando o servi�o
    - json-server db.json

------------------------------------

Criterios  do projeto.

Foi automatizada a Automa��o anterior "meat_app_parceria" por�m colocando a metodologia Page Object

FUNCIONALIDADE:

Funcionalidade: Pesquisar Restaurante

Como um cliente que adora comer
Gostaria de pesquisar um restaurante de minha prefer�ncia
Para que possa visualizar as informa��es sobre o estabelecimento
E o card�pio online

Crit�rios de aceite:

- Campos obrigat�rios:
	- Campo para busca do restaurante

- Valores
	- Todos valores devem conter "R$"

- Dados do estabelecimento
	- Categoria (para saber qual a especialidade)
	- Quem somos (para saber se tem know how no mercado)
	- Hor�rios (para saber qual hor�rio de funcionamento)

- Card�pio
	- Itens devem ser exibidos em forma de lista
	- Imagem alinhada a esquerda
	- Nome do prato em caixa alta
	- Breve descri��o do prato abaixo do nome
	- Bot�o adicionar deve estar sendo exibido