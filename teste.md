# Texto
O ***Lorem Ipsum*** é um texto modelo da indústria tipográfica e de impressão. O Lorem Ipsum tem vindo a ser o _texto padrão usado por estas indústrias desde o ano de 1500, quando uma misturou os caracteres de um texto para criar um espécime de livro._

 Este texto não só sobreviveu 5 séculos, mas também o salto para a tipografia electrónica, mantendo-se essencialmente inalterada.  
  ~~Foi popularizada nos anos 60 com a disponibilização das folhas de Letraset, que continham passagens com Lorem Ipsum, e mais recentemente com os programas de publicação como o Aldus PageMaker que incluem versões do Lorem Ipsum.~~

***

# Programa em C
```C
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main(void) { // da um numero aleatorio de 1 a 10 para o usuario descobrir

  int randow, num1, num2, num3; // Declaração
  srand(time(0));
  randow = rand() % 10 + 1; // numero aleatorio de 1 a 10

  printf("Tente adivinhar o numero entre 1 e 10: ");
  scanf("%d", &num1); // atribui num1

  if (num1 == randow){  // Caso o usuario acerte o numero
    printf("Você Acertor meu consagrado");
  }
  else{ // Caso erre
    printf("Você errou! mas pode tentar mais uma vez !!!!");
     
    if(randow < num1){ // Dica
      printf("O numero é menor que %d!\n",num1);
    }
    else{ // Dica
       printf("O numero é maior que %d!\n",num1);
    }

    printf("Digite outro numero: ");   // Prompt para segunda tentativa
    scanf("%d",&num2); // atribui num2
    
    if(num2 == randow){
      printf("Você acertou !!!!!");}
    else{
      printf("\nERROOOOOOOOOOOOOOOOOOOU\n");
      printf("HAHAHAHAHAHSDUIAHDIUWABFUIWABDUAWND\n");

      if(randow < num2){ // Dica
      printf("\nO numero é menor que %d!\n",num2);
    }
    else{ // Dica
       printf("\nO numero é maior que %d!\n",num2);
    }
      printf("ULTIMA TENTATIVA MEU CONSAGRADO!!!!\nDigita o terceiro numero ai: ");
      scanf("%d",&num3);
      if(num3 == randow){
        printf("Voce ACERTOOOOOOOOOOOOOOOOOOOOOOOOOOU!!!!!");
      }
      else{
        printf("\nErrou dnv kkkkkkkkkkkk");
        printf("\nO numero aleatorio era %d\nMais sorte na proxima amigo(a)!!",randow);
      }
    }
  }
  return 0;
}
```
# Imagem com link

[![imagem](https://media.giphy.com/media/faDeAx3ckwmYw/giphy.gif)](https://www.youtube.com/watch?v=nYd3ZK5XEE0)
***
# Tabela

| Nome | idade | altura |
| ---- | ----- | ------ |
| Joao | 19    | 1,95   |
| Maria | 20   | 1,70   |
|Luana | 17    | 1,50   |
| Matue | 22   | 1,80   |

***
# Listas não ordenadas e ordenadas

* exemplo
* exemplo
* exemplo
* exemplo

1. exemplo
2. exemplo
3. exemplo
4. exemplo
***
# Bloco de citação

> exemplo para um bloco  
de citação