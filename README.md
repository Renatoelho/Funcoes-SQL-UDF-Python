# Criando Funções SQL (UDF) no DuckDB com Python

Este repositório demonstra como criar e utilizar ***Funções Definidas pelo Usuário*** (UDF) no ***DuckDB*** usando ***Python***. As UDFs permitem estender a funcionalidade SQL padrão, permitindo que você escreva funções personalizadas em Python e as utilize diretamente nas suas consultas SQL no DuckDB. Isso é particularmente útil para realizar operações complexas de manipulação de dados que não são facilmente alcançadas com o ***SQL*** padrão. Por exemplo, criamos uma UDF simples que verifica se o dígito verificador (DV) de um ***CPF*** é composto apenas por números. Este exemplo ilustra o potencial das UDFs para realizar ***operações complexas*** de manipulação de dados diretamente no DuckDB, permitindo soluções avançadas e personalizadas para diversas necessidades de processamento.

<!--
https://www.youtube.com/@renato-coelho
-->

# Apresentação em vídeo

<p align="center">
  <a href="https://youtu.be/FwYVfnteAO8" target="_blank"><img src="thumbnail/Funcoes-SQL-UDF-Python.png" alt="Vídeo de apresentação"></a>
</p>


### Requisitos

+ ![Git](https://img.shields.io/badge/Git-2.25.1%2B-E3E3E3)

+ ![Ubuntu](https://img.shields.io/badge/Ubuntu-20.04%2B-E3E3E3)

+ ![Python](https://img.shields.io/badge/Python-3.8%2B-E3E3E3)


## Deploy da aplicação


### Clonando o repositório

```bash
git clone https://github.com/Renatoelho/Funcoes-SQL-UDF-Python.git Funcoes-SQL-UDF-Python
```


### Preparando o ambiente

+ Acessando o diretório clonado
```bash
cd Funcoes-SQL-UDF-Python/
```

+ Criando o ambiente virtual
```bash
python3 -m venv .venv
```

+ Ativando o ambiente virtual
```bash
source .venv/bin/activate
```

+ Instalando as dependências
```bash
pip install -U pip setuptools wheel --no-cache-dir && pip install -r requirements.txt --no-cache-dir
```

+ Ativando o Jupyter Notebook
```bash
jupyter notebook
```

Agora é só acessar o Notebook que será aberto em seu nevegador ou [http://localhost:8888/tree](http://localhost:8888/tree).


# Referências

Jupyter Notebooks, **DuckDB.** Disponível em: <https://duckdb.org/docs/guides/python/jupyter>. Acesso em: 27 jun. 2024.

Python Function API, **DuckDB.** Disponível em: <https://duckdb.org/docs/api/python/function>. Acesso em: 27 jun. 2024.

Configuration, **DuckDB.** Disponível em: <https://duckdb.org/docs/configuration/overview#examples>. Acesso em: 27 jun. 2024.

Validação de CNPJ - Python 3, **Github.** Disponível em: <https://github.com/Renatoelho/validacao-cnpj-python3>. Acesso em: 27 jun. 2024.

Validação de CPF - Python 3, **Github.** Disponível em: <https://github.com/Renatoelho/validacao-cpf-python3>. Acesso em: 27 jun. 2024.
