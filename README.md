# Tranca de Cofre com Keypad e Arduino

## Descrição

Este projeto consiste numa tranca de cofre controlada por Arduino, utilizando um teclado matricial 4x3, um servomotor, dois LEDs e um buzzer. O sistema permite abrir a tranca apenas quando é introduzida a senha correta.

O objetivo principal é simular um sistema simples de controlo de acesso, semelhante ao funcionamento de uma fechadura eletrónica.

## Funcionamento

O utilizador introduz uma senha através do keypad.

A tecla `#` serve para confirmar o código introduzido.

A tecla `*` serve para apagar/resetar o código introduzido.

Se o código estiver correto, o LED verde acende, o buzzer emite um sinal sonoro e o servomotor roda para abrir a tranca(90º).

Se o código estiver incorreto, o LED vermelho acende e o buzzer emite um som de erro(servo sem movimento).

## Código de acesso

A senha definida no programa é `1904`.

Depois de introduzir a senha, o utilizador deve premir `#` para confirmar.

Exemplo:

```txt
1904#
