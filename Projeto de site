#include <stdio.h>

int main()
{
    // Criando as variaveis:
    int Escolha1;
    int Escolha2;
    int quantidade = 0;
    // O quanto a pessoa vai dever ou receber:
    float debitopositivo = 0;
    float debitonegativo = 0;
    // Preço:
    float camisa = 149.99;
    float calca = 109.99;
    float sapato = 59.99;
    float vestido = 249.99;
    float SaltoAlto = 99.99;
    float terno = 210.99;
    float DozeMola = 139.99;
    // Intro:
    printf("Olá Bem vindo a loja Offuscato, o que deseja?\n\n");
    printf("Acessar roupas: digite 1\n");
    printf("Devolucao de roupas: digite 2\n\n");
    scanf("%d", &Escolha1);
    // Primeira Escolha:
    if (Escolha1 == 1)
    {
        // Acessar Roupas:
        printf("\nQue tipo de roupas gostaria de comprar?\n\n");
        printf("Roupas femininas: digite 1\n");
        printf("Roupas masculinas: digite 2\n");
        printf("Roupas unissex: digite 3\n\n");
        scanf("%d", &Escolha2);
        // Segunda Escolha:
        if (Escolha2 == 1)
        {
            // Roupas Femininas:
            printf("\nQue roupas voce gostaria de comprar?\n");
            printf("\nVestido R$%.2f: Insira quantos vestidos voce quer comprar\n\n", vestido);
            scanf("%d", &quantidade);
            debitonegativo += (quantidade * vestido);

            printf("\nCalça R$%.2f: Insira quantas calcas voce quer comprar\n\n", calca);
            scanf("%d", &quantidade);
            debitonegativo += (quantidade * calca);

            printf("\nSalto alto R$%.2f: Insira quantos saltos altos voce quer comprar\n\n", SaltoAlto);
            scanf("%d", &quantidade);
            debitonegativo +=(quantidade * SaltoAlto);

            printf("\n\nO total a ser pago: R$%.2f\n\n", debitonegativo);
        }
        else if (Escolha2 == 2)
        {
            // Roupas Masculinas:
            printf("Que roupas voce gostaria de comprar?\n");
            printf("\nTerno R$%.2f: Insira quantos ternos voce quer comprar\n\n", terno);
            scanf("%d", &quantidade);
            debitonegativo += quantidade * terno;

            printf("\nCalça R$%.2f: Insira quantas calcas voce quer comprar\n\n", calca);
            scanf("%d", &quantidade);
            debitonegativo += quantidade * calca;

            printf("\n12 mola R$%.2f: Insira quantos 12 mola voce quer comprar\n\n", DozeMola);
            scanf("%d", &quantidade);
            debitonegativo += quantidade * DozeMola;

            printf("\n\nO total a ser pago: R$%.2f\n\n", debitonegativo);
        }
        else if (Escolha2 == 3)
        {
            // Roupas Unissex:
            printf("Que roupas voce gostaria de comprar?\n");
            printf("\nCamisa R$%.2f: Insira quantas camisas voce quer comprar\n\n", camisa);
            scanf("%d", &quantidade);
            debitonegativo += quantidade * camisa;

            printf("\nCalça R$%.2f: Insira quantas calcas voce quer comprar\n\n", calca);
            scanf("%d", &quantidade);
            debitonegativo += quantidade * calca;

            printf("\nSapato R$%.2f: Insira quantos sapatos voce quer comprar\n\n", sapato);
            scanf("%d", &quantidade);
            debitonegativo += quantidade * sapato;

            printf("\n\nO total a ser pago: R$%.2f\n\n", debitonegativo);
        }
        else
        {
            printf("Escolha invalida!\n");
        }
    }
    else if (Escolha1 == 2)
    {
        // Devolução de roupas:
        printf("Quais roupas voce gostaria de devolver?\n");
        printf("\nCamisa R$%.2f: Insira quantas camisas voce quer devolver\n\n", camisa);
        scanf("%d", &quantidade);
        debitopositivo += quantidade * camisa;

        printf("\nCalça R$%.2f: Insira quantas calcas voce quer devolver\n\n", calca);
        scanf("%d", &quantidade);
        debitopositivo += quantidade * calca;

        printf("\nSapato R$%.2f: Insira quantos sapatos quer devolver\n\n", sapato);
        scanf("%d", &quantidade);
        debitopositivo += quantidade * sapato;

        printf("\nVestido R$%.2f: Insira quantos vestidos quer devolver\n\n", sapato);
        scanf("%d", &quantidade);
        debitopositivo += quantidade * vestido;

        printf("\nSalto alto R$%.2f: Insira quantos saltos altos voce quer devolver\n\n", SaltoAlto);
        scanf("%d", &quantidade);
        debitopositivo += quantidade * SaltoAlto;

        printf("\nTerno R$%.2f: Insira quantos ternos voce quer devolver\n\n", terno);
        scanf("%d", &quantidade);
        debitopositivo += quantidade * terno;

        printf("\n12 mola R$%.2f: Insira quantos 12 mola voce quer devolver\n\n", DozeMola);
        scanf("%d", &quantidade);
        debitopositivo += quantidade * DozeMola;

        printf("\nO total a ser recebido: R$%.2f\n", debitopositivo);
    }
    else
    {
        printf("Escolha invalida, tente novamente...");
    }

    return 0;
}
