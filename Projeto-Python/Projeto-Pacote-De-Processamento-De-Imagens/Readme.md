# Pacote de processamento de imagens

**Projeto**: Descomplicando a Criação de Pacotes de Processamento de Imagens em Python.

**Autora:** Karina Kato.


**Resumo:** Este projeto visa colocar em prática conceitos de modularidade e criação de pacotes Python. No caso, o projeto feito foi um pacote de processamentos de imagens idealizado pela Karina Kato.

-------------------------
## **Descriçao**:
O pacote image_processing-wedi ele é usado para:

**Módulo Processing**:

* Correspondência de histograma;
* Similaridade estrutural;
* Redimensionar imagem;

**Módulo Utils**:

* Ler imagem;
* Salvar imagem;
* Plotar imagem;
* Resultado do gráfico;
* Plotar histograma;

-----------------------------------------
## *Preparando o ambiente para Test Pypi*

Comandos de instalação:

```
 python -m pip install --upgrade pip
 python -m pip install --user twine
 python -m pip install --user setuptools
```
Comandos para criar distribuições:

````
 python setup.py sdist bdist_wheel
````

 Após completar a instalação, verifique se as pastas abaixo foram adicionadas ao projeto:
  *  build;
  *  dist;
  *  image_processing_test.egg-info;

Para publicar seu projeto no teste Pypi basta digitar o seguinte comando:

````
python -m twine upload --repository-url https://test.pypi.org/legacy/ dist/*

````
*Obs: Pode ocorrer erro na hora de postar caso exista um projeto com de outra pessoa com o mesmo nome. Por isso uma coisa boa de se fazer é nomear o projeto da seguinte forma "projeto_nomedoprojeto-nomeusuário", pois assim não há riscos e seu arquivo será upado sem problemas.*

------------------------
# Usando o pacote

**Instalação de dependêcias**:
`````
pip install -r requirements.txt
``````
**Instalação do pacote:**
`````
pip install -i https://test.pypi.org/simple/ image-processing-wedi

