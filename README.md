<div align="center">
  <img src="https://raw.githubusercontent.com/lincolnsm/EPINFO-PROJECT-DATABASE-INCLUDED-/main/public/icons/epinfoLogo-512x512.png" width="150">
</div>

# EPINFO

<div align="center">
  <strong>Projeto para facilitar o cadastro e controle de EPIs (Equipamentos de Proteção Individual)</strong><br>
  <em>Desenvolvido com foco em uso empresarial</em>
</div>

---

## 📌 Descrição

Este projeto tem como objetivo auxiliar empresas na administração de EPIs, oferecendo uma plataforma prática para cadastro, controle e visualização das informações dos equipamentos.

---

## 👨‍💻 Autores

- [Tasso Enzo](https://github.com/TassoEnzo)
- [Lincoln Souza](https://github.com/lincolnsm)
- [Márcio Freire](https://github.com/marciofreire99)
- [Marco Aurélio](https://github.com/MarcoAurelio010)

---

## 🧰 Requisitos

- [Python](https://www.python.org/downloads/)
- [MySQL Server](https://dev.mysql.com/downloads/mysql/)
- [MySQL Workbench](https://dev.mysql.com/downloads/workbench/)
- (Recomendado) [Visual Studio Code](https://code.visualstudio.com/download)

---

## 🚀 Como usar

Este guia foi pensado para o ambiente **Windows**, mas pode ser adaptado para **Linux** ou **macOS**.

### 1. Instale os requisitos

Instale todos os programas listados acima. O VSCode é opcional, mas recomendado para facilitar a edição e execução do código.

---

### 2. Banco de dados

Abra o **MySQL Workbench** e verifique se o banco está sendo criado corretamente. Ele será útil para monitorar os dados.

---

### 3. Configure o `App.py`

No arquivo `App.py`, edite as variáveis de conexão com o banco de dados:

```python
app.config['MYSQL_USER'] = 'seu_usuario'
app.config['MYSQL_PASSWORD'] = 'sua_senha'
app.config['MYSQL_DB'] = 'db_EPI'
app.config['MYSQL_HOST'] = 'localhost'

