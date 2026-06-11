#include <stdio.h>

int main() {
    char resposta;
    
    printf("Deseja ativar modo idoso 70+? (Y/N): ");
    scanf("%c", &resposta);
    
    if (resposta == 'Y' || resposta == 'y') {
        printf("\n MODO IDOSO ATIVADO!\n");
        printf(" Brilho: 100%%\n");
        printf(" Fonte: Grande\n");
        printf(" Leitura por voz: Ligada\n");
    } else {
        printf("\n Modo normal mantido.\n");
    }
    
    return 0;
}
