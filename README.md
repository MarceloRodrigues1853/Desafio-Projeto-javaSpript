# Desafio-Projeto-javaSpript

## faça um programa pa calcular o valor de cobudtivel em viagem

você terá `5 variaveis`. sendo elas:
 - 1.Preço do Gasolina;
 
 - 2.Preço do Etanol;
 
 - 3.O tipo de combustivel do seu carro;
 
 - 4.Gasto médio de combustivel do carro por KM;
 
 - 5.Distância em Km da Viagem;

Imprima no console o valor que será gasto para realizar esta viagem.

```js
//definir váriaveis
const precoEtanol = 5.79;
const precoGasolina = 6.66;
const KmPorLitros = 10;
const distanciaEmKm = 100;
const tipoCombustivel = 'Gasolina';
const litrosComsumidos = distanciaEmKm / KmPorLitros;

//lógica condicional
if (tipoCombustivel === 'Etanol') {
    const valorGasto = litrosComsumidos * precoEtanol;
    console.log(valorGasto.toFixed(2));
} else {
    const valorGasto = litrosComsumidos * precoGasolina;
    console.log(valorGasto.toFixed(2));
}
```
