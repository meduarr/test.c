# test.c
Inciando os estudos na linguem C. A linguegem foi criada por Dennis Ritchie na década de 1970, foi fundamental no desenvolvimento 
do sistema operacional UNIX e, ainda hoje, continua extremamente relevante. Ela é amplamente utilizada no desenvolvimento de 
sistemas operacionais, sistemas de desktop, sistemas embarcados e aplicações voltadas para telecomunicações, 
graças à sua performance, portabilidade e controle direto sobre o hardware.

```
#include <stdio.h> //é um tipo de biblioteca para entrada e saída como 'printf'

int main(){
    int logica;

    printf("Digite um numero inteiro: \n");
    scanf("%d", &logica);

    if( logica % 2 == 0){
        printf ("O numero %d e par \n", logica);
}

    else{
        printf("O numero %d e impar. \n", logica);
}

   return 0; //apos exibir o 'return 0' no seu programa, significa que deu tudo certo e não há nenhum erro.
}

´´´
