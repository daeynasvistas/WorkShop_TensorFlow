# WorkShop TensorFlow (@IPG)
![Image of IPG](https://github.com/daeynasvistas/WorkShop_Xamarin/blob/Vers.01/AppIPG/AppIPG.Android/Resources/drawable/IPG_M.jpg?raw=true)

# Primeira Parte (Criar classificador de imagens)
Criar um novo Classificador com TensorFlow. Visualizar os resultados para tirar conclusões sobre serviços cognitivos.

### Software necessário para seguir esta primeira parte prática (e fica com um classificador funcional)

1. [VisualStudio Code](https://code.visualstudio.com/) (Preferencialmente)
2. [Git](https://git-scm.com/download/win/) (Preferencialmente)
3. [Python 3.6.1](https://www.python.org/downloads/release/python-361/) (A versão é importante)
   Link directo para Vers. Windows [Python 3.6.1 Windows x86-64 executable installer](https://www.python.org/ftp/python/3.6.1/python-3.6.1-amd64.exe)


#### Num terminal digitar:
```c#
py --version
```
#### Resposta correcta:
```
Python 3.6.1
```

#### Num terminal digitar:
```c#
py -m pip install --upgrade pip setuptools
py -m pip --version
```
#### Resposta correcta:
```
pip 19.1.1 
```
#### Num terminal digitar:
```c#
py -m pip install --upgrade tensorflow
py -m pip install --user numpy
py -m pip install --upgrade opencv-python
```

# Instalação do classificador de imagens "genérico"
## Clonar este repositório
```c#
git clone https://github.com/daeynasvistas/WorkShop_TensorFlow.git
```
(ou em alternativa, fazer download e unzip para uma pasta)

![SC_03](https://user-images.githubusercontent.com/2634610/58430996-c71b7200-80a3-11e9-8124-4ba40a798b85.gif)


## Resultado final da instalação
#### Num terminal digitar:
```c#
py retrain.py
```

## Este erro indica que está tudo bem instalado !!! 
```c#
starting program . . .
ERROR: there are not at least 3 images in C:\IPG_workshop\WorkShop_TensorFlow\WorkShop_IPG/test_images/
Did you break out some test images?
```




