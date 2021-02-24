# Configuração de ambiente

* Neste arquivo você verá como preparar um ambiente para começar a programar algorítmos de aprendizado de máquina.

## _Python 3_

* Linguagem de programação.

Sistema | Instalação
--------|-----------
_Windows_|Baixar e instalar no [_link_](https://www.python.org/downloads/) [1]
_Linux_|Já instalado por padrão, dependendo da distro
_MAC_|Baixar e instalar no [_link_](https://www.python.org/downloads/)

[1] Lembre-se de marcar a opção _'Add Python 3.x to PATH'_. 

## _PIP_

* Gerenciador de pacotes do _Python_.

Sistema | Instalação
--------|-----------
_Windows_|Instala-se automaticamente com _Python 3_ [2]
_Linux_|Para distros _Debian_: usar o comando : `sudo apt install python3-pip` [3][4]
_MAC_|Instala-se automaticamente com _Python 3_

[2] Em caso de erro de reconhecimento do _pip_, uma possível causa é relacionada as 'Variáveis de ambiente'.
[3] Em outras distros, com outros gerenciador de pacotes, é diferente.
[4] Em algumas Distros _Linux_, utiliza-se os comandos: `python3` e `pip3`.

## Bibliotecas

* Conjunto de funções pre-escritas, para facilitar a codificação, que neste caso, trata-se de aprendizado de máquina.

### Bibliotecas principais:

* [_Numpy_](https://numpy.org/): cálculo numérico;
* [_Pandas_](https://pandas.pydata.org/): dados tabulares;
* [_MatPlotLib_](https://matplotlib.org/): plotagem de gráficos;
* [_SciKitLearn_](https://scikit-learn.org/): aprendizagem de máquina;
* [_TensorFlow_](https://www.tensorflow.org/?hl=pt-br): tratamento de tensores;
* [_Keras_](https://keras.io/): redes neurais;
* Extras:
	* [_SciPy_](https://www.scipy.org/): programação científica;
	* [_PyTorch_](https://pytorch.org/): alternativa ao TensorFlow.

Sistema | Instalação
--------|-----------
_Windows_|`pip install numpy pandas matplotlib scipy scikit-learn tensorflow keras`
_Linux_|`pip3 install numpy pandas matplotlib scipy scikit-learn tensorflow keras` [5]
_MAC_|`pip install numpy pandas matplotlib scipy scikit-learn tensorflow keras`

[5] Se for necessário instalar como _root_: acrescentar `sudo` antes do comando.

## _VS Code_

* Ambiente de desenvolvimento integrado (_IDE_), onde programa-se;
* Baixar e instalar no [_link_](https://code.visualstudio.com/).

### Configuração

* [Configuração](https://gist.github.com/diego3g/b1b189063d21b96d6144ca896755be64) proposta por [_Diego Fernandes_](https://gist.github.com/diego3g).

### Extensões indicadas

* _Auto Rename Tag_: para trabalhar com _tags_, do tipo: `<p>`;
* _Bookmarks_: para favoritar uma linha de código;
* _Bracket Pair Colorizer 2_: colore os pares de '{}';
* _Brazilian Portuguese - Code Spell Checker_: língua portuguesa para verificador de ortografia;
* _Code Spell Checker_: verificador de ortografia;
* _Color Highlight_: colore códigos de cores nas cores indicadas;
* _Dracula Official_: tema de cores maneiro para a _IDE_, desenvolvido por [_Zeno Rocha_](https://draculatheme.com/);
* _EditorConfig for VS Code_: para criar arquivos '.editorconfig', a fim de padronizar as configurações do editor de texto;
* _GitLens_: permite maior integração com _GitHub_;
* _Jupyter_: permite utilizar ambiente _Jupyter_ direto na _IDE_;
* _Live Share_: para codar em conjunto;
* _Markdown Preview Enhanced_: para visualizar _MarkDowns_ na _IDE_;
* _Material Icon Theme_: tema de ícones maneiro;
* _Python_: para compilar de debugar _Python_;
* _REST Client_: para criar requisições pela _IDE_;
* _Settings Sync_: para salvar na núvem as configurações e extensões;
* _Tabnine Autocomplete AI_: para sugestões de escrita inteligentes.

## _Jupyter_

* [_Link_](https://jupyter.org/);
* Diferenças quanto a _IDE_.

### Instalação de _Jupyter_ local

Sistema | Instalação
--------|-----------
_Windows_|`pip install jupyterlab`
_Linux_|`pip3 install jupyterlab`
_MAC_|`pip install jupyterlab`

### Execução

`jupyter-lab`

### _Google Colab_

* [_Link_](https://colab.research.google.com/);
* Integração com _Google Drive_;
* Uso de _GPU_ e _TPU_ gratuitos;
* Uso de comandos _Unix_ (_Linux_).

### _Kaggle_

* [_Link_](https://www.kaggle.com/);
* Plataforma;
* Desafios.