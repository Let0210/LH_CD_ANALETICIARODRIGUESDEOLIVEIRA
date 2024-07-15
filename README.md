# Etapas para executar o notebook jupyter na sua máquina
## 1. Tenha o python e o jupyter notebook devidamente instalados e configurados na sua máquina
Caso não possua algum dos dois instalado ainda, recomendo assistir a [este tutorial do youtube](https://www.youtube.com/watch?v=QfmSEzRXN1o&t=382s).

## 2. Clone esse repositório através da URL no terminal ou baixe-o em uma pasta zipada na opção Code -> Download ZIP.

## 3. Dentro da pasta com os arquivos baixados, execute, respectivamente, os seguintes passos dentro do terminal:
#### 3.1 Crie uma máquina virtual com o comando `python -m venv nome_do_seu_ambiente_virtual`. Isso permite que você isole as dependências do projeto.

#### 3.2 Ative a máquina virtual criada com o comando `nome_do_seu_ambiente\Scripts\activate`, se estiver utilizando Windows, ou com o comando `nome_do_seu_ambiente_virtual\Scripts\activate`, se estiver utilizando Linux/macOS.

#### 3.3 Instale as bibliotecas necessárias para a utilização do notebook em questão, presentes no arquivo requirements.txt. Para isso, digite `pip install -r requirements.txt` e aguarde o término da operação.

#### 3.4 Por fim, execute o comando `jupyter notebook`. Será aberta uma aba no seu navegador com os arquivos do notebook. Abra o `Respostas.ipynb` e comece a utilizar o notebook. 
##### Obs: recomendo clicar na opção `Run -> Run All Cells` logo de inicío para que você já tenha uma visão de todo o projeto. Porém, caso opte por analisar o código passo a passo basta dar "Run" em uma célula de código por vez.
