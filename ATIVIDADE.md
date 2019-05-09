#Utilização de Títulos, Subtítulos, itens e códigos no Markdown.

#h1É possível definir o nível do título usando uma ou mais hashtags antes do texto.

#h1Titulo1

##h2Subtítulo1

###h3Subtítulo2


#h1Os itens podem ser utilizados de forma não ordenada ou ordenada.

##h2Para criar uma lista não ordenada é possível utilizar o asterisco, o sinal de mais e o sinal de menos antes do texto:

* Item não ordenado um
* Item não ordenado dois
* Item não ordenado três

##h2Para ordenar itens basta utilizar um número e um ponto antes do texto:

1. Item ordenado um
2. Item ordenado dois
3. Item ordenado três


#h1Pode-se delimitar códigos por linhas ou blocos:

##h2Para utilizar códigos na mesma linha, eles devem estar entre duas crases:

`printf("Codigo na mesma linha")`


##h2Para utilizar blocos de códigos, eles devem estar entre crases triplas:

``` 
int main () {

	int nmr = 0;
	
	scanf("%d", &nmr;);
	printf("Numero digitado = %d", nmr);
	
	return 0;	

}
```

##h2Além disso, também é possível especificar a linguaguem do seu bloco de códigos:

###h3Para isso, digita-se a linguagem logo após o início do bloco:

```c int main () {

	int nmr = 0;
	
	scanf("%d", &nmr;);
	printf("Numero digitado = %d", nmr);
	
	return 0; 

```

Enfim, utilizando esses comandos, é possível editar seus textos em markdown, inserindo títulos, subtítulos, itens e códigos.

