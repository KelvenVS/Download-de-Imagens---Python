## Sobre

Este programa baixa imagens com base em uma lista fornecida, que pode ser transferida através de dois arquivos .txt ou um arquivo .xlsm.

## Importante

### Entrada em TXT

- Formate a entrada dos arquivos .txt como **codigos.txt** e **download_links.txt** na pasta ./Fonte/txt/
- Os dois arquivos .txt devem ter o mesmo número de linhas e seus dados devem estar corretamente sincronizados entre si.

### Entrada em Excel

- Formate a entrada do arquivo .xlsx como **dados.xlsx** na pasta ./Fonte/excel/
- As colunas no Excel devem corresponder a 'ccodpro' e 'links'.
- As duas colunas devem ter o mesmo número de linhas e seus dados devem estar corretamente sincronizados entre si.


## Funcionamento

- Utilize a variável `Dados` da seguinte maneira: `Dados = baixar('excel')` ou `Dados = baixar('txt')`.
- O programa irá salvar os arquivos na pasta `Entrada`, nomeando-os com os valores passados pela coluna `CCODPRO` em `Dados`.


## Pré-requisitos

Para executar este projeto, você precisará ter os seguintes pacotes Python instalados:

- `requests`: Para fazer requisições HTTP e baixar imagens da web.
- `pandas`: Para manipulação de dados e leitura de arquivos Excel.
- `IPython`: Para utilizar a função `clear_output` que limpa a saída do console no Jupyter Notebook.

Você pode instalar esses pacotes usando o `pip` com o comando:

```bash
pip install requests pandas ipython
```
## Importante

Certifique-se de que você tenha um ambiente Python configurado com as bibliotecas acima. Este projeto foi desenvolvido utilizando Jupyter Notebook, portanto, é recomendável que você também tenha o Jupyter instalado:

## Requirements.txt

- Detalhes de tudo que foi usado

    requirements.txt

