# WorkShop TensorFlow (@IPG)
![Image of IPG](https://github.com/daeynasvistas/WorkShop_Xamarin/blob/Vers.01/AppIPG/AppIPG.Android/Resources/drawable/IPG_M.jpg?raw=true)

# Primeira Parte (Criar classificador de imagens)
Criar um novo Classificador com TensorFlow. Visualizar os resultados para tirar conclusões sobre serviços cognitivos.

### Software necessário para seguir esta primeira parte prática (e fica com um classificador funcional)

1. [VisualStudio Code](https://code.visualstudio.com/) (Preferencialmente)
2. [Git](https://git-scm.com/download/win/) (Preferencialmente)
3. [Python 3.6.1](https://www.python.org/downloads/release/python-361/) (A versão é importante)
   Link directo para Vers. Windows [Python 3.6.1 Windows x86-64 executable installer](https://www.python.org/ftp/python/3.6.1/python-3.6.1-amd64.exe)


#### Num terminal:
```c#
py --version
```
#### Resposta correcta:
```
Python 3.6.1
```

#### Num terminal:
```c#
py -m pip install --upgrade pip setuptools
py -m pip --version
```
#### Resposta correcta:
```
pip 19.1.1 
```
#### Num terminal:
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
#### Num terminal:
```c#
py retrain.py
```

## Este erro indica que está tudo bem instalado !!! 
```c#
starting program . . .
ERROR: there are not at least 3 images in C:\IPG_workshop\WorkShop_TensorFlow\WorkShop_IPG/test_images/
Did you break out some test images?
```



---
## FIM da pré-instalação para o workshop
#### A fase seguinte é para executar no workshop
---



# Treinar classificador
## Mover imagens da pasta de treino para a pasta de teste

Mover 4 ou 5 imagens de cada uma das pastas de treino para a pasta de teste
#### Num terminal:
```c#
py retrain.py
```

![SC_04](https://user-images.githubusercontent.com/2634610/58465256-338f8300-812f-11e9-98cf-d42b425e8c8f.gif)



# Testar e visualizar resultados
## Resultado final
#### Num terminal:
```c#
py test.py
```

![SC_06](https://user-images.githubusercontent.com/2634610/58465986-b6650d80-8130-11e9-8621-34e33ceb1548.gif)


## Resultado final
![mon](https://user-images.githubusercontent.com/2634610/58466196-1491f080-8131-11e9-8348-0c1bfb5254d8.PNG)

