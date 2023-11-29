# Calculadora de Partidas Ranqueadas

<h3 align="center">Calculadora de Partidas Ranqueadas</h3>

<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![GitHub Issues](https://img.shields.io/github/issues/seu-usuario/nome-do-repositorio.svg)](https://github.com/seu-usuario/nome-do-repositorio/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/seu-usuario/nome-do-repositorio.svg)](https://github.com/seu-usuario/nome-do-repositorio/pulls)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

<p align="center"> 🎮 Calculadora simples para determinar o nível de um jogador com base no saldo de vitórias e derrotas em partidas ranqueadas.
    <br> 
</p>

## 🧐 Sobre <a name = "about"></a>

Fornece uma descrição breve sobre o propósito da calculadora de partidas ranqueadas.

## 🎥 Demonstração / Funcionamento <a name = "demo"></a>

![Funcionamento](URL_DA_IMAGEM_DEMO)

## 💭 Como Funciona <a name = "working"></a>

A função principal calcula o saldo de vitórias e determina o nível do jogador com base em condições pré-definidas.

Se a quantidade de vitórias for menor que 10, o jogador está no nível Ferro. Se estiver entre 11 e 20, é Bronze, e assim por diante. O resultado é exibido em uma mensagem no console.

## 🎈 Uso <a name = "usage"></a>

1. Abra o arquivo `index.html` em um navegador web.
2. Insira a quantidade de vitórias e derrotas quando solicitado.
3. O resultado será exibido no console.

### Exemplo:

```javascript
const vit = parseInt(prompt("Digite o número de vitórias:"));
const der = parseInt(prompt("Digite o número de derrotas:"));

const { saldo, nivel } = calcularRanked(vit, der);

console.log(`O Herói tem um saldo de ${saldo} está no nível de ${nivel}`);
