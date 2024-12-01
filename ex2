#include <stdio.h> 
#include <string.h>
#define TAMANHO 4

void ler_e_imprimir_string(char texto[], int tamanho)
{
    printf("Digite uma palavra\n"); 
    fgets(texto, tamanho, stdin); // fgets adiciona no final da string o ENTER (\n)

    int posicao_enter = strcspn(texto, "\n");
    texto[posicao_enter] = '\0';

    printf("Palavra: %s\n", texto);
}

int main()
{
    char texto1[TAMANHO];
    char texto2[TAMANHO];

    ler_e_imprimir_string(texto1, TAMANHO);
    ler_e_imprimir_string(texto2, TAMANHO);

    printf("Texto 01: %s\n", texto1);
    printf("Texto 02: %s\n", texto2);

    char texto_concatenado[TAMANHO + TAMANHO ];
     int i = 0;

    for(i = 0; i < TAMANHO  - 1; i++)
    {
        // texto1
        texto_concatenado[i] = texto1[i];
        printf("%c",  texto1[i]);
    }

    for(int j = 0; j < TAMANHO - 1; j++)
    {
        // texto2
        texto_concatenado[i + j ] = texto2[j];
        printf("%c",  texto2[j]);

    }
    
    texto_concatenado[i + TAMANHO - 2] = '\0'; // Adicionando o caractere nulo ao final da string concatenada
    printf("Concatenado: %s\n", texto_concatenado);
    return 0;
}
// linha 25 ( Apaguei o -1 )
// linha 26 ( int i = 0; ) 
// linha 28 ( - 1 )
// linha 30 ( = ),( break; )
// linha 30 ( deixei o i Normal )
// linha 31 ( Apaguei o IF ) 
// linha 34 ( -1 )
// linha 36 ( i + j )
// linha 37 ( J )
// linha 38 ( Apaguei a linha ) 
// linha 41 ( Add texto_concatenado[i + TAMANHO - 2] = '\0'; )
// linha 43 ( Add return 0; )

 
 
