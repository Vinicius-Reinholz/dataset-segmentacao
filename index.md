# Nome do Seu Dataset

**Uma breve descrição de uma linha sobre o dataset.**

O Dataset de Segmentação de Células XYZ é uma coleção de 10.000 imagens de microscopia de alta resolução, com máscaras de segmentação semântica anotadas por especialistas para 5 classes de células...

---

## 🧩 Visão Geral (Overview)

Aqui você pode detalhar o problema que seu dataset resolve.  
Por que ele é importante?  
Como ele foi coletado?

---

## 🖼️ Exemplos de Segmentação

Esta é a parte mais importante. Você pode usar uma tabela para mostrar os exemplos lado a lado:

| Imagem Original | Máscara de Segmentação (Ground Truth) |
|------------------|---------------------------------------|
| ![Exemplo 1](assets/exemplo_01.png) <br> *Legenda: Exemplo de uma célula do tipo A.* | ![Máscara 1](assets/exemplo_01_mask.png) <br> *Legenda: Máscara correspondente.* |
| ![Exemplo 2](assets/exemplo_02.png) | ![Máscara 2](assets/exemplo_02_mask.png) |

---

## 🧬 Classes e Anotações

Liste as classes que seu dataset segmenta.  
É uma boa prática mostrar a cor de cada máscara.

- **Classe 1 (ex: Carro):** Cor `(255, 0, 0)`
- **Classe 2 (ex: Pedestre):** Cor `(0, 255, 0)`
- **Classe 3 (ex: Fundo):** Cor `(0, 0, 0)`

> As máscaras são arquivos PNG de 8 bits onde o valor do pixel 0 corresponde ao fundo, 1 à Classe 1, etc.

---

## 📦 Download

Para usar o dataset, é necessário concordar com os termos de licença (ex: CC-BY 4.0).

👉 [**Clique aqui para baixar o Dataset v1.0 (.zip)**](https_seu_link_do_release_aqui)

---

## 📚 Citação (Citation)

Se você publicou um *paper* sobre o dataset, coloque a citação aqui para que outros possam referenciar seu trabalho.

```bibtex
@misc{seu_nome_2025_dataset,
  title={Nome do Seu Dataset},
  author={Seu Nome e Co-autores},
  year={2025},
  publisher={GitHub},
  journal={GitHub repository},
  howpublished={\url{https://github.com/seu-usuario/meu-dataset-segmentacao}}
}
