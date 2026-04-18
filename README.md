# Python Aplicado à Ciência de Dados

Este repositório reúne os materiais utilizados no projeto **Python Aplicado à Ciência de Dados**, desenvolvido no contexto da disciplina de Ciência de Dados da Universidade de Fortaleza (UNIFOR). O objetivo é apoiar o aprendizado prático de conceitos fundamentais da área por meio de exemplos, exercícios, notebooks interativos e datasets reais.

O conteúdo foi estruturado para iniciantes e para pessoas que desejam iniciar na área de **Ciência de Dados**, apresentando desde conceitos básicos de programação até técnicas de análise exploratória e visualização de dados.

## 📊 Objetivo do Repositório

Este repositório funciona como um **ambiente de estudo e prática**, contendo materiais que auxiliam no aprendizado de:

- Fundamentos de programação com Python
- Manipulação e análise de dados
- Visualização de dados
- Análise exploratória de dados (EDA)
- Interpretação e comunicação de insights

A proposta é proporcionar uma experiência prática, permitindo que estudantes explorem datasets reais, reproduzam análises e desenvolvam seus próprios experimentos.

## 📁 Estrutura do Repositório

A organização do projeto segue uma estrutura simples para facilitar o acesso aos materiais:

```
datasets/
│   Conjuntos de dados utilizados nas análises e exercícios.

notebooks/
│   Notebooks em Python (Google Colab / Jupyter) contendo exemplos,
│   análises exploratórias e exercícios práticos.

slides/
│   Apresentações utilizadas nas aulas e nos módulos do curso.

exercicios/
│   Atividades propostas para prática dos conceitos aprendidos.

projeto_final/
│   Projeto final de conclusão do curso.
```

## 🧠 Conteúdo Abordado

O material do repositório cobre tópicos importantes da área de Ciência de Dados, incluindo:

- Introdução à Ciência de Dados
- Fundamentos de programação em Python
- Manipulação de dados com Pandas
- Estatística descritiva básica
- Visualização de dados com Matplotlib e Seaborn
- Análise Exploratória de Dados (EDA)
- Geração de insights a partir de dados

A Ciência de Dados é apresentada como a intersecção entre **estatística, computação e conhecimento de negócio**, sendo aplicada na resolução de problemas reais e na tomada de decisões baseada em dados.

## 🛠 Tecnologias Utilizadas

Principais ferramentas e bibliotecas utilizadas nos materiais:

- Python 3.8+
- Google Colab / Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn

## 📦 Datasets

Os datasets utilizados nos exemplos e exercícios estão disponíveis na pasta `datasets/`.
Alguns deles são provenientes de bases públicas utilizadas para fins educacionais.

---

## 🚀 Como Utilizar

Você pode rodar os notebooks de duas formas: **online via Google Colab** (sem instalar nada) ou **localmente na sua máquina**.

### ☁️ Opção 1 — Google Colab (recomendado para iniciantes)

- Acesse [colab.research.google.com](https://colab.research.google.com)
- Clique em **"Arquivo" → "Abrir notebook" → "GitHub"**
- Cole a URL do repositório: `https://github.com/PedroJordao2/Trabalho-Ci-ncia-de-Dados`
- Selecione o notebook desejado e clique em **"Abrir"**

Nenhuma instalação é necessária — o Colab já possui Python e as principais bibliotecas configuradas.

Neste caso, será necessário realizar o envio dos arquivos dos datasets utilizados nos módulos 2, 3 e projeto final.

---

### 💻 Opção 2 — Executar Localmente

#### 1. Instale o Python

> Caso já tenha o Python instalado, pule para o passo 2.

**Windows:**

- Acesse [python.org/downloads](https://www.python.org/downloads/) e baixe a versão mais recente (3.8 ou superior)
- Execute o instalador `.exe`
- **Importante:** marque a opção **"Add Python to PATH"** antes de clicar em _Install Now_
- Após a instalação, abra o **Prompt de Comando** (`Win + R` → digite `cmd`) e verifique:

```bash
python --version
```

**macOS:**

- Acesse [python.org/downloads](https://www.python.org/downloads/) e baixe o instalador `.pkg`
- Execute o instalador e siga os passos
- Abra o **Terminal** e verifique:

```bash
python3 --version
```

**Linux (Ubuntu/Debian):**

O Python geralmente já vem instalado. Para verificar ou instalar:

```bash
python3 --version

# Caso não esteja instalado:
sudo apt update
sudo apt install python3 python3-pip
```

---

#### 2. Clone o Repositório

Com o Python instalado, clone o projeto para sua máquina:

```bash
git clone https://github.com/PedroJordao2/Trabalho-Ci-ncia-de-Dados.git
cd Trabalho-Ci-ncia-de-Dados-main
```

> Caso não tenha o Git instalado, acesse [git-scm.com](https://git-scm.com/) ou baixe o repositório como `.zip` clicando em **"Code" → "Download ZIP"** no GitHub.

---

#### 3. Abra o Projeto no VS Code

O **Visual Studio Code (VS Code)** é um editor de código gratuito, leve e amplamente usado na área de dados. Ele oferece suporte nativo a notebooks `.ipynb`, o que permite rodar os materiais deste repositório sem precisar abrir o navegador.

**Instalação:**

- Acesse [code.visualstudio.com](https://code.visualstudio.com/) e baixe a versão para o seu sistema operacional
- Execute o instalador e siga os passos (as opções padrão já são suficientes)
- Abra o VS Code após a instalação
  **Extensões recomendadas:**

Instale as extensões abaixo para trabalhar com Python e notebooks dentro do VS Code:

- **Python** — suporte à linguagem Python (realce de sintaxe, execução, debug)
- **Jupyter** — permite abrir e executar arquivos `.ipynb` diretamente no editor
  Para instalar, pressione `Ctrl+Shift+X` (ou `Cmd+Shift+X` no macOS) para abrir o painel de extensões, pesquise pelo nome e clique em **Install**.

**Abrindo o projeto:**

Após clonar o repositório, abra a pasta do projeto no VS Code:

```bash
# No terminal, dentro da pasta do projeto:
code .
```

Ou acesse pelo menu: **"Arquivo" → "Abrir Pasta"** e selecione a pasta `Trabalho-Ci-ncia-de-Dados-main`.

Em seguida, navegue até a pasta `notebooks/`, clique em qualquer arquivo `.ipynb` e ele será aberto diretamente no VS Code. Clique em **"Select Kernel"** no canto superior direito e escolha o interpretador Python instalado na sua máquina.

---

#### 4. Instale as Dependências

Instale as bibliotecas necessárias com o `pip`:

```bash
pip install pandas matplotlib seaborn jupyter
```

> No macOS ou Linux, use `pip3` no lugar de `pip` caso necessário.

---

#### 5. (Opcional) Usando Ambiente Virtual

Recomendado para evitar conflitos entre projetos:

```bash
# Criar o ambiente virtual
python -m venv venv

# Ativar — Windows
venv\Scripts\activate

# Ativar — macOS/Linux
source venv/bin/activate

# Instalar dependências
pip install pandas matplotlib seaborn jupyter

# Iniciar o Jupyter
jupyter notebook
```

Para desativar o ambiente virtual quando terminar:

```bash
deactivate
```

---

## 🎓 Público-Alvo

Este material foi desenvolvido para:

- Estudantes iniciantes em programação
- Pessoas interessadas em Ciência de Dados
- Profissionais em transição de carreira
- Alunos de ensino médio ou superior que desejam aprender análise de dados

---

📚 Projeto educacional voltado à disseminação de conhecimentos em **Ciência de Dados e análise de dados com Python**.
