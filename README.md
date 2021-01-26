# Conexao-MySQL-python
Nesse código com explicações de comandos e parte técnica, é mostrado como fazer a conexão com o banco de dados MySQL com a linguagem Python

1 - A linguagem Python não é nativa com o Banco de dados MySQL, por isso,temos que instalar um driver que vai fazer a comunicação entre o banco de dados e a linguagem Python

2- Dentro da sua IDLE(Pycharm, no meu caso),ative o plugin chamado "PyMysql" nas configurações ( File - Setings - Python interpreter - + - PyMysql - Install Package)

3 - Para isso, talvez seja necessário instalar o conector MySQL no python através do PIP, que é um gerenciador de pacotes python, ou seja, é onde encontramos várias bibliotecas python para podermos utilizar,esse gerenciador já vem instalado junto com o Python, então para ativarmos o conector MySQL para python,entramos dentro do terminal e rodamos o seguinte código(cmd no caso de windows ou o terminal linux)
pip install mysql-connector-python

4- Instalado o connector, agora só resta programar a conexão MySQL utilizando a linguagem python.
5 - Para isso abrimos a IDLE, e utilizamos o código
