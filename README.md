# Classificando Imagens

Projeto desenvolvido na disciplina **SIN 393 – Introdução à Visão Computacional** da Universidade Federal de Viçosa – Campus Rio Paranaíba.

## Autores

- Júlia Marques Boaventura – 8105  
- Vinícius Meireles Pereira Santos – 8112  

---

## Índice

1. [Descrição do Projeto](#descrição-do-projeto)  
2. [Requisitos](#requisitos)  
3. [Dataset](#dataset)  
4. [Instruções de Execução](#instruções-de-execução)  
5. [Licença](#licença)  

---

## Descrição do Projeto

Este trabalho implementa um classificador de imagens utilizando o conjunto de dados **MPEG‑7**.  
O notebook `projeto1classificandoimagens.ipynb` percorre todas as etapas, incluindo:

- Extração de características das imagens  
- Pré-processamento (segmentação e normalização)  
- Treinamento e avaliação de modelos de aprendizado de máquina  

Ao final, são gerados gráficos e métricas que ilustram a acurácia do classificador para cada categoria de imagem.

---

## Requisitos

- Python 3.12.2  
- Bibliotecas utilizadas:
  - `scikit-image`
  - `matplotlib`
  - `numpy`
  - `scikit-learn`
  - `seaborn`
  - `pandas`
  - `scipy`

### Ambiente virtual (opcional):
```bash
python -m venv .venv
source .venv/bin/activate  # Linux/macOS
# .venv\Scripts\activate  # Windows
pip install -r requirements.txt
```

> Alternativamente, a **primeira célula do notebook instala automaticamente todas as dependências.**

---

## Dataset

O repositório já contém o conjunto **MPEG‑7** localizado na pasta `mpeg7_mod/`, além do arquivo compactado `mpeg7_mod.zip` como backup.

As classes de imagens incluem: `apple`, `bat`, `beetle`, `bell`, entre outras.  
**Não é necessário fazer download adicional.**

---

## Instruções de Execução

Clone este repositório e abra o notebook:

```bash
git clone https://github.com/vinimeirelres/classificandoimagens
cd classificandoimagens
```

Execute o notebook em um ambiente Jupyter:

```bash
projeto1classificandoimagens.ipynb
```

No final, o notebook exibirá os gráficos, matrizes de confusão e métricas de avaliação dos modelos.

---

## Licença

Este projeto tem finalidade **estritamente acadêmica**, sendo utilizado para estudo e experimentação na disciplina SIN 393.
