# tabuada.c

## Sobre o Código:

Esse código funciona com uma simples tabuada onde o usuário insere um número de 1 a 1000, e então é entregue a ele a tabuada daquele número, de 1 a 10. É ótimo para verificar a tabuada de um número rapidamente ou brincar de indentificar padrões.

Funciona de uma maneira simples, o usuário da run no código e insere um número, e dá play, como mostrado na imagem:

<img width="122" height="154" alt="Screenshot 2026-10-11 at 20 58 17" src="https://github.com/user-attachments/assets/007edeed-6bf7-4bfc-ac14-e6a28e311bb9" />

## Como rodar o código? Onde? Intruções aqui:

Para rodar o código, é simples, pode ser copiado e colado em qualquer plataforma para rodar o código, como vscode, mycompiler e onlineGDB.

Para baixar o arquivo basta apenas usar a função "fork" do próprio github, como indicado pela seta verde na imagem abaixo:

<img width="1421" height="470" alt="Screenshot 2026-10-11 at 21 10 26" src="https://github.com/user-attachments/assets/d7169ac8-06e8-42ff-992a-c0fc91ff1e62" />

Ao dar o fork, você será direcionado ao seu github e devera escolher o nome do seu arquivo clonado, como mostrando na seguinte imagem:

<img width="760" height="585" alt="Screenshot 2026-10-11 at 21 38 28" src="https://github.com/user-attachments/assets/8cc233c3-661a-4ec4-be84-258da2a26a3d" />

Uma vez feito isto, basta clicar no arquivo main.c

<img width="305" height="214" alt="Screenshot 2026-10-11 at 21 41 14" src="https://github.com/user-attachments/assets/dd79c7ec-5226-421a-8a8e-b350563cc73b" />

Lá você pode copiar e colar o código num compiler de internet como o onlineGDB ou o Visual Studio Code, ou então baixar o arquivo no botão indicado pela seta verde na imagem:

<img width="1139" height="473" alt="Screenshot 2026-10-11 at 21 42 03" src="https://github.com/user-attachments/assets/b1fda2df-e57d-4e2b-94b9-cb007d40f358" />

### Se quiser copiar e colar no VSCode, faça isso:

PS: Se for fazer no VSCode, siga os seguintes passos:
No terminal crie um arquivo.c, pod eter o nome que desejar:

        $ code tabuada.c

Para rodar tem que fazer o make do arquivo e então dar ./, o ./ dá run no código, e o make deixa ele rodável:

        $ make tabuada
        $ ./tabuada

E então o código vai rodar. ;)

## Testando o código

Para testar, ao rodar o código seja lá qual for o compiler escolhido, teste o código usando o número que preferir.

Insira 45:

    45

Dê enter, e o resultado esperado é o seguinte:

    45 * 1 = 45
    45 * 2 = 90
    45 * 3 = 135
    45 * 4 = 180
    45 * 5 = 225
    45 * 6 = 270
    45 * 7 = 315
    45 * 8 = 360
    45 * 9 = 405
    45 * 10 = 450

## Sobre a License

** A LICENSE escolhida para este arquivo é a licensa do MIT, que te dá muita liberdade para clonar e mecher no arquivo clonado como bem entender. Seja feliz.

O texto oficial sobre a licensa está aqui: https://opensource.org/license/mit e https://mit-license.org/

**Este repositório é protegido pela <a href="./LICENSE">MIT License</a>**

------------------------------------------------------------------------------------------------------------------------------------------------

# Sobre o que está no código C:

O código lê o número inserido pelo usuári e verifica se está entre 1 e 1000, por meio de um if, se estiver adequado o código prossegue normalmente (return 0) se não ele retorna 1 e para. Para printar a tabuada o código usa um loop for para multiplicar o número do usuário por i, que aumenta até chegar em dez e printa algo como: n * i = r. Sendo n o número inserido pelo usuário, i é o número da múltiplicação (1 a 10) e r o respectivo resultado. Simples.
