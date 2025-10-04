Projeto Hospital das Clinicas - Acessibilidade para Teleconsultas

Requisitos para rodar o projeto

Python 3.11 
è a versão que A versão 3.11 é a que possui a biblioteca oracledb instalada.

Passo 1: Instalar e Rodar com um Comando Único
Basta copiar e colar esta linha no seu terminal MINGW64 (Git Bash):
Bash
cd HC---Python-Banco && python -m venv venv && source venv/Scripts/activate && pip install oracledb && python main.py


Se o comando acima parar em algum momento, execute os passos abaixo individualmente para identificar onde está a falha:
1. Entrar no Diretório do Projeto
Entre na pasta que contém o main.py:
Bash
cd HC---Python-Banco

2. Criar e Ativar o Ambiente Virtual
O seu sistema precisa recriar a pasta venv antes de ativá-la.
Bash
# 2a. Cria o ambiente (cria a pasta 'venv')
python -m venv venv

# 2b. Ativa o ambiente (usando o caminho de ativação correto para MINGW64/Windows)
source venv/Scripts/activate

Se for bem-sucedido, você verá o (venv) no seu prompt.
3. Instalar o oracle db
Instala as dependências listadas no seu requirements.txt:
Bash
pip install -r requirements.txt

4. Executar o Script
Bash
python main.py
