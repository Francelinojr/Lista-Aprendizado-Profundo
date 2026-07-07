# Lista de Exercícios - Aprendizado Profundo (2026.1)

Este repositório contém a resolução da lista de exercícios da disciplina de **Aprendizado Profundo**. O trabalho abrange desde fundamentos de Redes Neurais Perceptron Multicamadas (MLP) até Redes Neurais Convolucionais (CNN) e Autoencoders.

## 📂 Estrutura do Repositório

O projeto está organizado da seguinte forma:

| Diretório | Descrição |
| :--- | :--- |
| `src/` | Códigos-fonte em formato `.py` e `.ipynb` (Jupyter Notebook). |
| `results/` | Gráficos, matrizes de confusão e métricas geradas para cada questão. |
| `docs/` | Enunciado da lista, relatório final e slides. |
| `data/` | (Opcional) Scripts ou instruções para download dos datasets utilizados. |

## 🚀 Questões Abordadas

### Questão 1: Regressão com MLP
*   **1a:** Aproximação de uma função polinomial complexa de 5º grau.
*   **1b:** Predição de valores imobiliários utilizando o dataset *California Housing*.

### Questão 2: Classificação com MLP
*   Análise exploratória e classificação de sobreviventes do *Titanic*. Inclui tratamento de dados faltantes e balanceamento de classes.

### Questão 3: Comparativo MLP vs CNN
*   Classificação de imagens do dataset *Fashion-MNIST*. Comparação de desempenho e curvas de aprendizado entre arquiteturas densas e convolucionais.

### Questão 4: Visualização de Redes Convolucionais
*   Visualização dos filtros aprendidos pela primeira camada e mapas de ativação. Análise qualitativa de acertos e erros da rede.

### Questão 5: Autoencoders
*   **5a:** Implementação de Autoencoder Convolucional com diferentes dimensões de espaço latente.
*   **5b:** Implementação de *Denoising Autoencoder* para reconstrução de imagens com ruído.

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas Principais:**
    *   `PyTorch` (Deep Learning)
    *   `Scikit-Learn` (MLP e Pré-processamento)
    *   `Pandas` & `NumPy` (Manipulação de dados)
    *   `Matplotlib` & `Seaborn` (Visualização)

## 📖 Como Executar

1.  Certifique-se de ter o Python instalado.
2.  Instale as dependências: `pip install torch torchvision scikit-learn pandas numpy matplotlib seaborn`
3.  O código principal pode ser executado via script (`src/main_script.py`) ou através do notebook (`src/main_notebook.ipynb`).

---
*Este material foi desenvolvido para fins acadêmicos.*
