# ARQMIND - Mineração de Dados
Repositório destinado a todos os conteúdos/códigos vistos na matéria de Mineração de Dados

### Introdução à Mineração de Dados: Conceitos Básicos - Editora Saraiva

- CRISP-DM (CRoss Industry Standard Process for Data Mining): Modelo utilizado no projeto + relatório

- Papel
- Python (Pandas)
- Orange > Software de Data Mining


### Rodar ambiente python:
```sh
aluno@positivo-C4400:~$ pwd
/home/aluno

aluno@positivo-C4400:~$ ls
 AndroidStudioProjects   eclipse-workspace      Músicas             pt
 Arduino                 htdocs                 node_modules        Público
'Área de trabalho'       idea-IC-243.24978.46   orange-venv         R
 Documentos              Imagens                package.json        snap
 Documents               modelio                package-lock.json   Vídeos
 Downloads               Modelos                Postman

aluno@positivo-C4400:~$ source 
.android/                     Modelos/
AndroidStudioProjects/        .mozilla/
Arduino/                      Músicas/
.arduino15/                   .mysql/
.arduinoIDE/                  node_modules/
Área de trabalho/             .npm/
.atom/                        .nvm/
.bash_history                 .openshot_qt/
.bash_logout                  orange-venv/
.bashrc                       .p2/
.cache/                       package.json
.config/                      package-lock.json
.dia/                         .packettracer
.dmrc                         .pki/
Documentos/                   Postman/
Documents/                    .profile
.dotnet/                      .projectlibre/
Downloads/                    pt/
.eclipse/                     Público/
eclipse-workspace/            .r/
.emulator_console_auth_token  R/
.gradle/                      .Rhistory
.gtkrc-2.0                    .rpmdb/

aluno@positivo-C4400:~$ source orange-venv/bin/activate

(orange-venv) aluno@positivo-C4400:~$ pip freeze
anyio==4.10.0
AnyQt==0.2.1
asttokens==3.0.0
attrs==25.3.0
baycomp==1.0.3
Bottleneck==1.5.0
cattrs==25.1.1
certifi==2025.8.3
cffi==1.17.1
chardet==5.2.0
charset-normalizer==3.4.3
comm==0.2.3
commonmark==0.9.1
contourpy==1.3.3
cryptography==45.0.6
cycler==0.12.1
debugpy==1.8.16
decorator==5.2.1
dictdiffer==0.9.0
docutils==0.22
et_xmlfile==2.0.0
executing==2.2.0
fonttools==4.59.1
h11==0.16.0
httpcore==1.0.9
httpx==0.28.1
idna==3.10
ipykernel==6.30.1
ipython==9.4.0
ipython_pygments_lexers==1.1.1
jaraco.classes==3.4.0
jaraco.context==6.0.1
jaraco.functools==4.3.0
jedi==0.19.2
jeepney==0.9.0
joblib==1.5.1
jupyter_client==8.6.3
jupyter_core==5.8.1
keyring==25.6.0
keyrings.alt==5.0.2
kiwisolver==1.4.9
matplotlib==3.10.5
matplotlib-inline==0.1.7
more-itertools==10.7.0
nest-asyncio==1.6.0
networkx==3.5
numpy==2.3.2
openpyxl==3.1.5
openTSNE==1.0.2
orange-canvas-core==0.2.6
orange-widget-base==4.26.0
Orange3==3.39.0
packaging==25.0
pandas==2.3.2
parso==0.8.4
pexpect==4.9.0
pillow==11.3.0
platformdirs==4.3.8
prompt_toolkit==3.0.51
psutil==7.0.0
ptyprocess==0.7.0
pure_eval==0.2.3
pycparser==2.22
Pygments==2.19.2
pyparsing==3.2.3
PyQt5==5.15.11
PyQt5-Qt5==5.15.17
PyQt5_sip==12.17.0
pyqtgraph==0.13.7
PyQtWebEngine==5.15.7
PyQtWebEngine-Qt5==5.15.17
python-dateutil==2.9.0.post0
python-louvain==0.16
pytz==2025.2
PyYAML==6.0.2
pyzmq==27.0.2
qasync==0.27.1
qtconsole==5.6.1
QtPy==2.4.3
requests==2.32.5
requests-cache==1.2.1
scikit-learn==1.7.1
scipy==1.16.1
SecretStorage==3.3.3
serverfiles==0.3.1
six==1.17.0
sniffio==1.3.1
stack-data==0.6.3
threadpoolctl==3.6.0
tornado==6.5.2
traitlets==5.14.3
truststore==0.10.4
typing_extensions==4.14.1
tzdata==2025.2
url-normalize==2.2.1
urllib3==2.5.0
wcwidth==0.2.13
xgboost==2.0.3
xlrd==2.0.2
xlsxwriter==3.2.5

(orange-venv) aluno@positivo-C4400:~$ pip freeze > orange-venv.txt

(orange-venv) aluno@positivo-C4400:~$ orange-canvas




-------

aluno@positivo-C4400:~$ source orange-venv/bin/activate

(orange-venv) aluno@positivo-C4400:~$ orange-canvas 



```

Nao supervisionado: dados sem rotulos, sem variavel alvo
