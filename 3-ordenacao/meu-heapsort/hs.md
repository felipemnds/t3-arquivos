# SORTING ORDEM CRESCENTE
1. build heap
2. heap -> min heap
3. delete the root
4. last node in the root position
5. volta pra 2) enquanto ||heap|| > 1
---------

# 1
- vetor de 0 a n (comecando em 1)

# 2
- comparacao comecando no floor(n/2)
	> tem algum filho menor?
		- SIM - troca (só com o menor filho)
		- SEMPRE - vai pra esquerda (pos - 1) e volta pra pergunta (loop)