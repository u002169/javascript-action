# Action javascript 

Esta ação imprime "Hello World" ou "Hello" + o nome de uma pessoa. 

## Entradas 

### `who-to-greet` 

**Obrigatório** O nome da pessoa para cumprimentar. Padrão `"World"`. 

## Saídas 

### `time` 

A hora em que cumprimentamos você. 

## Exemplo de uso 

```yaml 
usa: actions/hello-world-javascript-action@main 
com: 
  who-to-greet: 'user' 
```
