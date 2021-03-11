# SkipList
Code produced in the Data Sctruture I class at the Federal University of Espírito Santo

Introdução:

	O objetivo do trabalho é a implementação de uma estrutura de dados SkipList com as seguintes funções:

		-createLitst
		-isEmptyList
		-insertList
		-removeList
		-searchList
		-printListH
		-printList

	Resumindo, é uma estrutura de dados probabilística, baseada em listas ligadas paralelas, com eficiência
	comparável à de uma árvore binária (ordem de O(log n)) para a maioria das operações. Basicamente, uma skip list 
	é um aglomerado de listas encadeadas com ligações adicionais, adicionadas de modo aleatório de acordo com a distribuição
	Geométrica/Negativa Binomial, os quais permitem evitar a busca em parte da lista, 'pulando' alguns valores.

Implementação:

	Utilizei basicamente lista ligada, criei uma cabeça com um vetor de ponteiros e uma struct nó com o mesmo vetor de
	ponteiros, o int com o valor e o h para a hierarquia, o que facilitaria as outras funções. Mais detalhes na documentação dentro
	do própio código.

Conclusão:

	A lógica em si não é tão dificil, ao menos para mim, porém tive um pouco de dificuldade no início para decidir qual era 
	o melhor jeito de fazer o TAD do nó, ou utilizando ponteiro duplo, ou com vetor de ponteiro. Com minha prática com hashtable, preferi
	usar o vetor de ponteiro. Tive dificuldade também em relação a manipulação de arquivos, pois nunca tinha me aprofundado nessa matéria,
	porém com um pouco de pesquisa consegui utilizar com excelência e percebi que é bem fácil manipulá-los.
