<div align="center">
<img src="public/icons/epinfoLogo-512x512.png">
</div>
<h2 align="center"> DESCRIÇÃO </h2></br>
<h3>Este projeto tem a intencão de facilitar a administração e cadastro de EPIs, tem o foco de ser utilizado unicamente por empresas</h3><br/>

<h2 align="center"> AUTORES </h2></br>
<div align="center">
<h3 align="center">https://github.com/TassoEnzo</h3><br/>
<h3 align="center">https://github.com/lincolnsm</h3><br/>
<h3 align="center">https://github.com/marciofreire99</h3><br/>
<h3 align="center">https://github.com/MarcoAurelio010</h3><br/>
</div>

<h2 align="center"> REQUERIMENTOS </h2></br>
<h3>Python Interpreter(https://www.python.org/downloads/)</h3></br>
<h3>MySQL Server(https://dev.mysql.com/downloads/mysql/)</h3></br>
<h3>MySQL Workbench(https://dev.mysql.com/downloads/workbench/)</h3></br>
<h3>(Recomendação) VSCode(https://code.visualstudio.com/download)</h3></br>

<h2 align="center"> UTILIZAÇÃO </h3></br>
<h3>O projeto ja possui tudo o que é necessario incluindo o banco de dados, porém deve-se prestar atenção nos comandos para rodar o programa. Esse guia de utilização foi pensado para ser utilizado no ambiente Windows, ele funcionará igualmente em Linux ou MacOS, mudando apenas os nomes dos comandos.</h3></br>
</br>
</br>1. Instale todos os requerimentos, apenas o VSCode é opcional, sendo recomendado pois ele permite a edição dos scripts e também sua utilização, mas o usuario pode utilizar um editor de sua escolha.</br>
</br>2. Utilize o Workbench do sql para criar o banco de dados, tecnicamente não é um passo extremamente necessario, porém ele é util para verificar se os dados estão sendo salvos no banco.</br>
</br>3. Dentro do editor deve-se abrir primeiramente o arquivo App.py, ele é o link da aplicação com o banco. Na parte de cima, estão presentes as configurações que o usuario terá que editar "MYSQL_USER", "MYSQL_PASSWORD", "MYSQL_DB" E "MYSQL_HOST", preste atenção que a parte que deve ser editada é aquela após o simbolo de "=", agora darei uma explicação para o que deve ser preenchido nesses campos.</br>
   </br>- 3.1 "MYSQL_USER" - Deve ser trocado pelo nome que o usuario cadastrou na instalação do MySQL Server, o padrão é "root", se o usuario o alterou, ele deve utilizar o nome cadastrado.</br>
   </br>- 3.2 "MYSQL_PASSWORD" - Esse é a senha cadastrada também no MySQL Server, o usuario deve escreve-la neste campo.</br>
   </br>- 3.3 "MYSQL_DB" - Esse é o nome do banco que é "db_EPI", este campo não deve ser alterado.</br>
   </br>- 3.4 "MYQL_HOST" - Este é mais um campo que provavelmente não deve ser alterado.</br>
</br>4. Abra o terminal para inicializar o programa, no VSCode utilize o atalho Ctrl + ' ou Ctrl + j ou aba o terminal na parte superior direita, é o segundo terminal da esquerda para direita.</br>
</br>5. É necessario dois terminais, pois um será o reponsavel por rodar a aplicação flask enquanto o outro a aplicação em si, então com o terminal em aberto na parte direita do terminal aperte na cruz ou utilize o comando Crtl + Shift + '.</br>
</br>NOTA: Verifique os seus diretorios, pode ser que seja necessario utilizar o seguinte comando "cd EPINFO-PROJECT-main" ou se preferir corrija manualmente:</br>
</br><div align="center">
<img src="github/img/video-correcao.gif">
</div></br>
</br>6. Com os dois terminais abertos, sendo possivel trocar entre eles na parte direita do terminal, em qualquer um deles utilize o seguinte comando "python -m venv venv", este comando criará um ambiente virtual, que é o ideal para utilizar aplicações python, com o intuito de evitar conflitos com outros projetos, apos isso utilize esse script ".\venv\Scripts\Activate" para ativa-lo.</br>
</br>7. Agora o usuario deve instalar as dependencias do projeto, ele irá utilizar os seguintes codigos "pip install flask" e "pip install flask-mysqldb" e após isso utilize o comando "cd backend", para entrar no diretorio onde esta o aquivo app.py e utilize o comando "python app.py" que deve inicializar e ficar assim:</br>
</br><div align="center">
<img src="github/img/python imagem.png">
</div></br>
</br>8. Não feche o terminal, apenas troque para o outro e utilize o seguinte comando "npm install vite" para finalizar a instalação dos requerimentos do projeto e por fim  utilize "npm run dev", você deve receber o seguinte log:</br>
</br><div align="center">
<img src="github/img/npm imagem.png">
</div></br>
</br>9. Com o botão Ctrl pressionado click na linha "Local: http://localhost/", após isso será aberta uma aba no seu navegador, no qual você poderá finalmente utilizar o programa.</br>
</br>10. Com isso finalizo nosso guia. 😎 </br>

</br><div align="center">
<img src="github/img/Tela-Fim.gif">
</div>
