# Análise de Evasão 

[Proprietario] {Github} "@KvnNews"

```python
ipython==5.1.0
jupyter==1.0.0
matplotlib==1.5.3
notebook==4.2.3
pandas==0.18.1
xlrd==1.0.0
scikit-learn==0.18.1
```


Daí, para instalar os pacotes você irá precisar de um ambiente virtual ativo em sua máquina.
Para instalar um gestor de ambientes virtuais em sua máquina (Ubuntu e similares) utilize os seguintes comandos no terminal:

```sh
sudo apt-get install python-pip python-dev
sudo pip install virtualenv virtualenvwrapper
echo "export WORKON_HOME=~/envs" >> ~/.bashrc
echo "source /usr/local/bin/virtualenvwrapper.sh" >> ~/.bashrc
echo "export PIP_REQUIRE_VIRTUALENV=true" >> ~/.bashrc
source ~/.bashrc
mkvirtualenv <env_name> -p /usr/bin/python3
```
Observação: substitua \<env_name\> pelo nome de preferência para seu ambiente virtual. Assim que tiver o ambiente virtual instalado, dentro dele, digite o comando abaixo:

```sh
pip install -r requirements.txt
```

Para sair do ambiente virtual utilize:

```sh
deactivate
```
Para entrar em um ambiente virtual já criado utilize:
```sh
workon <env_name>
```
onde \<env_name\> é o nome do seu ambiente virtual já existente.
