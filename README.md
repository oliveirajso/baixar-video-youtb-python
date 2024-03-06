# Baixador de Vídeos do YouTube

Este é um simples script em Python para baixar vídeos do YouTube usando a biblioteca pytube.

## Instalação

1. Certifique-se de ter o Python instalado em seu sistema. Você pode baixá-lo em https://www.python.org/downloads/.

2. Instale o Virtualenv ou Venv
<code>
pip install virtualenv
</code>
ou
<code>
python -m venv nome_do_ambiente_virtual
</code>

3. Baixe o código do repositorio git e acessa a pasta do projeto

4. Execute o seguinte comando para criar um ambiente virtual

<code>
python -m venv nome_do_ambiente_virtual
</code>

5. Ative o ambiente virtual. <code>source <nome_do_ambiente_virtual>/bin/activate</code>

6. Instale a biblioteca pytube. Você pode fazer isso executando o seguinte comando no terminal:
``pip install pytube``

7. Quando terminar de usar o ambiente virtual, você pode desativá-lo executando o comando:
<code>
deactivate
</code>


## Como Rodar

1. Abra o terminal.

2. Navegue até o diretório onde você baixou o script `main.py`.

3. Execute o seguinte comando, substituindo `"URL_DO_VIDEO"` pela URL do vídeo do YouTube que você deseja baixar:


Por exemplo:

python baixador_youtube.py https://www.youtube.com/watch?v=SEU_ID_DE_VIDEO


4. O vídeo será baixado para o diretório de download padrão do seu sistema.

## Nota

Certifique-se de ter permissões adequadas para acessar a pasta de download especificada. Além disso, este script baixará o vídeo com a maior resolução disponível.


