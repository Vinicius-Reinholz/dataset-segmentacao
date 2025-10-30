---
# Esta seção "front matter" é usada pelo Jekyll
title: Nome do Seu Dataset
description: Uma breve descrição de uma linha sobre o dataset.
---

# Nome do Seu Dataset

**Uma descrição mais detalhada (1-2 parágrafos) sobre o seu dataset.**
(Ex: "O Dataset de Segmentação de Células XYZ é uma coleção de 10.000 imagens de microscopia de alta resolução, com máscaras de segmentação semântica anotadas por especialistas para 5 classes de células...")

---

## Visão Geral (Overview)

Aqui você pode detalhar o problema que seu dataset resolve. Por que ele é importante? Como ele foi coletado?

---

## Exemplos de Segmentação

Esta é a parte mais importante para o seu caso. Você pode usar uma tabela para mostrar os exemplos lado a lado:

| Imagem Original | Máscara de Segmentação (Ground Truth) |
| :---: | :---: |
| ![Exemplo 1](assets/exemplo_01.png) | ![Máscara 1](assets/exemplo_01_mask.png) |
| ![Exemplo 2](assets/exemplo_02.png) | ![Máscara 2](assets/exemplo_02_mask.png) |
| *Legenda: Exemplo de uma célula do tipo A.* | *Legenda: Máscara correspondente.* |

*(**Importante:** Troque `assets/exemplo_01.png` pelo caminho real das imagens que você subiu no Passo 3.)*

---

## Classes e Anotações

Liste as classes que seu dataset segmenta. É uma boa prática mostrar a cor de cada máscara.

* **Classe 1 (ex: Carro):** Cor (255, 0, 0)
* **Classe 2 (ex: Pedestre):** Cor (0, 255, 0)
* **Classe 3 (ex: Fundo):** Cor (0, 0, 0)

Detalhe também o formato das máscaras (ex: "As máscaras são arquivos PNG de 8 bits onde o valor do pixel 0 corresponde ao fundo, 1 à Classe 1, etc.")

---

## Download

Para disponibilizar o dataset, a forma mais fácil no GitHub é usando "Releases":

1.  Na página principal do seu repositório (não em "Settings"), clique em **"Releases"** (no lado direito).
2.  Clique em "Create a new release" (Criar um novo release).
3.  Dê um nome (ex: `v1.0`).
4.  Arraste e solte o seu arquivo `.zip` ou `.tar.gz` do dataset na caixa "Attach binaries...".
5.  Publique o release.
6.  Clique com o botão direito no seu arquivo .zip e "Copiar endereço do link".

Agora, adicione esse link ao seu `index.md`:

[**Clique aqui para baixar o Dataset v1.0 (.zip)**](https_seu_link_do_release_aqui)

Para usar o dataset, é necessário concordar com os termos de licença (ex: CC-BY 4.0).

---

## Citação (Citation)

Se você publicou um *paper* sobre o dataset, coloque a citação aqui para que outros possam referenciar seu trabalho.
