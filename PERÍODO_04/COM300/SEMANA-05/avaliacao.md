# AVALIAÇÃO 05 :shipit:

# Pergunta 01:
Analise as afirmações abaixo sobre funções do MySQL:

I. A função Round() é utilizada para truncar valores.
II. O MySQL dispõe de uma função que junta strings chamada de Concat().
III. A função Left() é uma função para strings.
IV. As funções Month() e Dayofmonth() apesar da escrita diferente, fazem a mesma coisa.
V. É possível, através de uma função, recuperar a data e hora do sistema/servidor.

De acordo com as afirmações apresentadas, indique qual alternativa é a correta:
		
    a) As afirmações II, III e V estão corretas.
		
    b) As afirmações II e IV estão corretas.
		
    c) Apenas a afirmação I é correta.
		
    d) As afirmações I, II e III estão corretas.
		
    e) As afirmações III, IV e V estão corretas.

> [!IMPORTANT]
> a) As afirmações II, III e V estão corretas.

-------

# Pergunta 02:
Na _Structured Query Language (SQL)_, diferentes comandos, cláusulas, operadores auxiliam na estruturação, na organização e na recuperação dos registros contidos nos Bancos de Dados (BD). Dentre outras tantas, há a cláusula HAVING, que pode ser usada em algumas instâncias que envolvem grupos.

Considerando o contexto dado, avalie as asserções a seguir e a relação proposta entre elas.

A cláusula HAVING pode ser utilizada para aplicar filtros pós-agregações.
**PORQUE**
O WHERE filtra os dados antes da agregação, enquanto o HAVING os filtra após esta.
 
A respeito dessas asserções, assinale a alternativa correta.

    a) A asserção I é uma proposição falsa, e a II é uma proposição verdadeira.

	b) As asserções I e II são proposições falsas.

	c) As asserções I e II são proposições verdadeiras, mas a II não é uma justificativa da I.

	d) As asserções I e II são proposições verdadeiras, e a II é uma justificativa da I.

	e) A asserção I é uma proposição verdadeira, e a II é uma proposição falsa.

> [!IMPORTANT]
> d) As asserções I e II são proposições verdadeiras, e a II é uma justificativa da I.

-------

# Pergunta 03:
A _Structured Query Language (SQL)_ é uma linguagem que se divide em diferentes conjuntos de comandos, cláusulas, operadores etc., sendo que a combinação deles faz com que se possa criar, atualizar, remover registros de diferentes tabelas de um Banco de Dados (BD) e, até mesmo, do BD em si.

Considerando o contexto dado, avalie as asserções a seguir e a relação proposta entre elas.

As funções de agregação são funções SQL que permitem executar uma operação aritmética dos valores de uma coluna em todos os registros de uma tabela.
**PORQUE**
As funções de agregação são bastante utilizadas com os recursos de agrupamento, possibilitando que os valores agregados sejam consolidados por grupos.
 
A respeito dessas asserções, assinale a alternativa correta.

	a) A asserção I é uma proposição verdadeira, e a II é uma proposição falsa.

	b) A asserção I é uma proposição falsa, e a II é uma proposição verdadeira.

	c) As asserções I e II são proposições falsas.

	d) As asserções I e II são proposições verdadeiras, mas a II não é uma justificativa da I.

	e) As asserções I e II são proposições verdadeiras, e a II é uma justificativa da I.

> [!IMPORTANT]
> d) As asserções I e II são proposições verdadeiras, mas a II não é uma justificativa da I.

-------

# Pergunta 04:
Observe a tabela Produto a seguir:

Agora observe o seguinte comando:

SELECT * FROM PRODUTO WHERE CONDICAO;

Considere verdadeiras (V) ou falsas (F) as afirmações abaixo, com base na substituição do termo CONDICAO no comando apresentado acima.

( **V** ) Caso CONDICAO seja NOME LIKE ‘C%’, teremos 2 registros como resultado.

( **F** ) Caso CONDICAO seja VALOR >= 10 AND IDPRODUTO>5, teremos 2 registros como resultado.

( **V** ) Caso o termo CONDICAO seja apenas eliminado do comando, haverá um erro na execução do comando.

( **V** ) Caso CONDICAO seja FORNECEDOR=CATEGORIA, teremos 4 registros como resultado.

( **V** ) Caso CONDICAO seja TRUNCATE(VALOR,0)>15,teremos 1 registro como resultado.

> [!IMPORTANT]
> V, F, V, V, V

-------

# Pergunta 05:
A Structured Query Language (SQL) é a linguagem usada para criar, atualizar, alterar, deletar, dentre demais funcionalidades e registros em Bancos de Dados (BD). Geralmente, para montar uma requisição de busca para os registros armazenados nas tabelas do BD, usa-se o comando SELECT. Diante disso, analise o comando abaixo.

SELECT nome, sobrenome, dtnasc
FROM funcionario
WHERE month(dtnasc)=8

Considerando o contexto dado, assinale a alternativa que descreve a lógica de busca supracitada.

	a) Selecionar nome, sobrenome e data de nascimento da tabela “funcionários”, que fazem aniversário no mês de agosto.

	b) Selecionar nome, sobrenome e data de admissão da tabela “funcionários” e listar aqueles que fazem aniversário em agosto.

	c) Selecionar nome, sobrenome e data de nascimento da tabela “funcionários” e listar aqueles que farão aniversário em oito meses.

	d) Selecionar nome, sobrenome e data de admissão dos funcionários que fazem aniversário em oito semanas.

	e) Selecionar nome e data de nascimento da tabela “funcionários”, que fazem aniversário no mês de agosto.

> [!IMPORTANT]
> a) Selecionar nome, sobrenome e data de nascimento da tabela “funcionários”, que fazem aniversário no mês de agosto.

-------

# Pergunta 06:
SQL é a linguagem para definição e manipulação de bancos de dados relacionais, a linguagem é repleta de comandos que executam as operações tanto de definição quanto de manipulação. Qual é o comando SQL utilizado para realizar consultas em um banco de dados?
		
    a) Truncate.
	
    b) Insert.
		
    c) Select.
		
    d) Delete.
		
    e) Update.

> [!IMPORTANT]
> c) Select.