# Desenhando Formas com CSS Puro

Este é um projeto de estudo front-end que demonstra como criar diversas formas geométricas e cenários simples utilizando apenas **HTML e CSS**, sem o uso de imagens, SVGs ou bibliotecas externas.

**[➡️ Acesse a demonstração ao vivo aqui](https://gabriel-wav.github.io/formas/)**

---

## 🎨 Sobre o Projeto

O objetivo deste projeto é explorar e aplicar diferentes técnicas de CSS para renderizar formas que normalmente exigiriam recursos gráficos. É um exercício prático para aprofundar o conhecimento em propriedades avançadas do CSS.

---

## ✨ Formas e Efeitos Criados

Todas as formas foram criadas com um ou mais elementos `<div>`, estilizados com CSS.

* Quadrado
* Círculo
* Triângulo
* Estrela de 5 pontas
* Coração
* Seta
* Cenário com Céu em degradê e Sol brilhante

---

## 🛠️ Técnicas de CSS Utilizadas

Este projeto não é apenas sobre o resultado visual, mas também sobre as técnicas empregadas:

* **Degradê do Céu**: O fundo da página utiliza `background: linear-gradient()` para criar uma transição suave do azul-celeste para o branco, simulando um céu.

* **Brilho do Sol**: O Sol, que é um círculo, ganha um efeito de brilho intenso através de múltiplas camadas da propriedade `box-shadow`.

* **Círculo**: Uso da propriedade `border-radius: 50%` para transformar um elemento quadrado em um círculo perfeito.

* **Triângulo**: Aplicação do truque de `border`. As bordas laterais do elemento são transparentes, enquanto a borda inferior é colorida, criando a forma triangular.

* **Estrela**: Utilização da propriedade `clip-path` com a função `polygon()` para definir as coordenadas que formam o contorno da estrela.

* **Coração**: A técnica mais complexa do projeto, utilizando os pseudo-elementos `::before` e `::after` para criar duas formas circulares rotacionadas (`transform: rotate()`) que, combinadas com o elemento principal, formam a figura de um coração.

* **Seta**: Construída a partir da combinação de dois `<div>`: um retângulo para o corpo e um triângulo (criado com a técnica de `border`) para a cabeça da seta.

---

## 🚀 Como Visualizar

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/gabriel-wav/formas.git](https://github.com/gabriel-wav/formas.git)
    ```
2.  **Navegue até a pasta do projeto:**
    ```bash
    cd formas
    ```
3.  **Abra o arquivo `index.html`** no seu navegador. Não é necessário nenhum servidor web.
