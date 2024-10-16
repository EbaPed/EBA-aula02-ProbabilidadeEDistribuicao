# Aula 02 - Probabilidade e Distribuições

Nesta aula vamos estudar e exercitar conceitos importantes sobre probabilidade e distribuições.

O que você encontrará neste repositório:

- Na pasta `data`: os arquivos `csv's`ou `xlsx` utilizados em aula.
- Na pasta `notebooks`: o gabarito do código trabalhado em aula.
- na pasta `exemplos-de-aula`: os arquivos contendo os exemplos trabalhados em aula.
- Na pasta `exercicios`: os exercícios propostos para casa.

Você pode encontrar mais exercícios nestes links:
- [Lista Extra 01](https://www.todamateria.com.br/exercicios-de-probabilidade-faceis/)
- [Lista Extra 02](https://www.todamateria.com.br/exercicios-sobre-probabilidade/)


## INSTRUÇÕES PARA O USO DESTE REPOSITÓRIO:

### **Como utilizar este repositório?**

Este repositório contém os arquivos e códigos necessários para a aula de Estatística Descritiva. Abaixo estão as instruções simplificadas para configurar o ambiente com Pyenv e Poetry.

- **Passo a Passo para Configuração do Ambiente:**

1. **Clonar o Repositório:**

No terminal, clone este repositório:

```bash
git clone https://github.com/EbaPed/EBA_para_casa_aula01.git
cd EBA_aula01_EstatisticaDescritiva
```

2. **Configurar a versão do Python com Pyenv**

Defina a versão do Python para o projeto. Para esta aula, vamos usar o Python 3.10.11 (ou outra versão compatível):

```bash
pyenv local 3.10.11
```

3. **Ativar o Ambiente Virtual Poetry**

Agora, ative o ambiente virtual:

```bash
poetry shell
```

4. **Instale as dependências do projeto usando Poetry:**

```bash
poetry install
```

Isso criará automaticamente um ambiente virtual isolado.


5. **Configurar o Kernel do Jupyter Notebook**

Se você for usar Jupyter Notebook, instale o ipykernel:

```bash
poetry add ipykernel
python -m ipykernel install --user --name=venv --display-name "Python (venv)
```

No Jupyter Notebook, escolha o kernel "Python (venv)" ao iniciar ou criar um novo notebook.


6. **Desativar o Ambiente Virtual**

Para sair do ambiente virtual, basta usar:

```bash
exit
```

7. **Executar o Código**

Agora que o ambiente está configurado, você pode executar os códigos Python fornecidos no repositório.

### **Comandos úteis**

- Ativar o ambiente virtual Poetry:

```bash
poetry shell
```

- Rodar um script com Poetry:

```bash
poetry run python script.py
```

- Adicionar bibliotecas:

 ```bash
poetry add nome_da_biblioteca
```
