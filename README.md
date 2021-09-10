#Required Libraries

1. streamlit
2. yfinance

Instructions

Instalando pip 
Es el manejador de paquetes de python

sudo apt-get update
sudo apt-get upgrade
sudo apt install python3-pip

Instalando streamlit
https://streamlit.io/ es una app framework que sirve para construir data apps

pip install streamlit

Instalando ANACONDA (https://www.youtube.com/watch?v=aE7qxfgubS8)
Es un administrador de paquetes de python usado en app cientificas,  ciencia de datos y machine learning.

Proveee un entorno de desarrollo donde estan las dependencias necesarias por cada proyecto.

Anaconda es un Python distribution y dentro tiene Conda que es como pip

Descargar anaconda: https://www.anaconda.com/products/individual-d
abrir terminal
tipear > conda
conda info (donde se crean los ambientes virtuales)

Crear ambiente virtual en conda

conda create --name nombreDelEntorno python=3.5

Acceder al ambiente virtual

conda activate nameDelEntorno
conda deactivate 

AHORA SI... CREEMOS LA APP

1. Instalamos streamlit y yfinance
pip install streamlit
pip install yfinance
2. Accedemos al entorno virtual con python=3.9
3. Creo un archivo de python: stockPriceApp.py con el siguiente codigo (https://github.com/dataprofessor/streamlit_freecodecamp/blob/main/app_1_simple_stock_price/myapp.py)
4. streamlit run  stockPriceApp.py
