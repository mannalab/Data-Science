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

### Extensões

* _Auto Rename Tag_
* _Bookmarks_
* _Bracket Pair Colorizer 2_
* _Brazilian Portuguese - Code Spell Checker_
* _Code Spell Checker_
* _Color Highlight_
* _Dracula Official_
* _EditorConfig for VS Code_
* _GitLens_
* _Jupyter_
* _Live Share_
* _Markdown Preview Enhanced_
* _Material Icon Theme_
* _Python_
* _REST Client_
* _Settings Sync_
* _Tabnine Autocomplete AI_

## _Google Colab_