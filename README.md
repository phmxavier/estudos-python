# Estudos Python + AI
Para facilitar o acompanhamento das "aulas" usando python, decidi usar Jupyter Notebooks.


# 📘 Como Estudar Python Usando Jupyter Notebooks (.ipynb)

Estudar Python com arquivos `.ipynb` (Jupyter Notebooks) é uma excelente forma de aprendizado interativo. Este guia ajudará você a configurar e utilizar notebooks de forma eficiente.

---

## 🚀 1. Instalando o Jupyter Notebook
Se ainda não tem o Jupyter Notebook instalado, use o pip:

```bash
pip install notebook
```

Ou, se estiver usando Anaconda:

```bash
conda install jupyter
```

Para iniciar o Jupyter Notebook:

```bash
jupyter notebook
```

Isso abrirá a interface no navegador.

---

## 📂 2. Abrindo um Arquivo `.ipynb`

### 🔹 Pelo Jupyter Notebook
1. Navegue até a pasta onde está o arquivo.
2. Execute `jupyter notebook` no terminal.
3. Clique no arquivo para abri-lo.

### 🔹 Pelo VS Code
1. Instale a extensão **Jupyter**.
2. Abra o `.ipynb` diretamente no VS Code e execute as células.

---

## ⌨️ 3. Atalhos Úteis

- `Shift + Enter`: Executa a célula e avança.
- `Ctrl + Enter`: Executa sem avançar.
- `Esc + B`: Nova célula abaixo.
- `Esc + A`: Nova célula acima.
- `Esc + D + D`: Deleta célula.
- `Esc + M`: Converte a célula em Markdown.

---

## 📑 4. Organização do Estudo

🔹 **Use Markdown**: Escreva descrições antes do código.  
🔹 **Experimente Código**: Modifique e execute as células várias vezes.  
🔹 **Visualize Dados**: Utilize gráficos para melhor compreensão.  

Exemplo de gráfico com `matplotlib`:

```python
import matplotlib.pyplot as plt
import numpy as np

x = np.linspace(0, 10, 100)
y = np.sin(x)

plt.plot(x, y)
plt.show()
```

---

## 📚 5. Onde Encontrar Notebooks

- [Google Colab](https://colab.research.google.com/) – Execute na nuvem.
- [Kaggle](https://www.kaggle.com/) – Notebooks para análise de dados.
- [GitHub](https://github.com/) – Repositórios com tutoriais e projetos.

---

## 🔄 6. Convertendo Notebooks

Converter para script Python:

```bash
jupyter nbconvert --to script meu_arquivo.ipynb
```

Converter para PDF:

```bash
jupyter nbconvert --to pdf meu_arquivo.ipynb
```
