# Utilização de Títulos, Subtítulos, itens e códigos no Markdown.

	É possível definir o nível do título usando uma ou mais hashtags antes do texto.

# Titulo1


## Subtítulo1


### Subtítulo2





### Os itens podem ser utilizados de forma não ordenada ou ordenada.

	Para criar uma lista não ordenada é possível utilizar o asterisco, o sinal de mais e o sinal de menos 
	antes do texto:

* Item não ordenado um
* Item não ordenado dois
* Item não ordenado três



	Para ordenar itens basta utilizar um número e um ponto antes do texto:

1. Item ordenado um
2. Item ordenado dois
3. Item ordenado três




### Pode-se delimitar códigos por linhas ou blocos:

	Para utilizar códigos na mesma linha, eles devem estar entre duas crases:

`printf("Codigo na mesma linha")`


	Para utilizar blocos de códigos, eles devem estar entre crases triplas:

``` 
int main () {

	int nmr = 0;
	
	scanf("%d", &nmr;);
	printf("Numero digitado = %d", nmr);
	
	return 0;	

}
```

	Além disso, também é possível especificar a linguaguem do seu bloco de códigos:

	Para isso, digita-se a linguagem logo após o início do bloco:

```c 
int main () {

	int nmr = 0;
	
	scanf("%d", &nmr;);
	printf("Numero digitado = %d", nmr);
	
	return 0;

}	

```

#### Enfim, utilizando esses comandos, é possível editar seus textos em markdown, inserindo títulos, subtítulos, itens e códigos.

