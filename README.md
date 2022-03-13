# Flua - Um fork da Linguagem Lua

A motivação deste fork é criar uma linguagem de programação que utilize palavras reservadas em português e que tenha por trás o poder e robustez da linguagem Lua.
Um outro grande motivo para este fork é poder estudar e entender melhor esta poderosa linguagem de programação.

## Instalação

Para instalar o Flua na sua máquina, basta executar os comandos abaixo:

```bash
git clone https://github.com/tomashugo/flua.git
cd flua
sudo make
sudo make install
```

## Colocando a mão na massa

Começando com uma linha de código:

```Lua
imprimir "Olá, mundo"
```


Se quiser tentar algo mais complexo, o código abaixo já é possível fazer com a linguagem Flua.

```Lua
-- define uma função fatorial
funcao fact(n)
  se n == 0 entao
     retorna 1
  senao
     retorna n * fact(n-1)
  fim
fim

imprimir("entre com um numero")
a = es.leitura("*n")
imprimir(fact(a))
```


