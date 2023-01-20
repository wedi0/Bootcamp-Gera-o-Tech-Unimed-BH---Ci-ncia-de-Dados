# Pacote de processamento de imagens



## **Descriçao**:
O pacote image_processing ele é usado para:

**Módulo Processing**:

* Correspondência de histograma;
* Similaridade estrutural;
* Redimensionar imagem;

**Módulo "Utils"**:

* Ler imagem;
* Salvar imagem;
* Plotar imagem;
* Resultado do gráfico;
* Plotar histograma;

-----------------------------------------
## *Preparando o ambiente para Test Pypi*

Comandos de instalação:

```
- python -m pip install --upgrade pip
- python -m pip install --user twine
- python -m pip install --user setuptools
```
Comandos para criar distribuições:

````
- python setup.py sdist bdist_wheel
````

 Após completar a instalação, verifique se as pastas abaixo foram adicionadas ao projeto:
  *  build;
  *  dist;
  *  image_processing_test.egg-info.

Basta subir os arquivos, usando o Twine, para o Test Pypi:
