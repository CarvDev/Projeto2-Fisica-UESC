------

# Simulação de Sistema Físico: Capacitores de Placas Paralelas

Repositório para um dos projetos da disciplina de Física para Ciência da Computação (2025.2) da Universidade Estadual de Santa Cruz (UESC).

------

## Informações Gerais

- **Proposta de projeto escolhida:** Projeto 5 (Capacitores)
- **Professor:** Prof. Orlando Katime Santrich
- **Alunos responsáveis pelo projeto:**
  - Arthur de Carvalho
  - Marcel Figueredo
  - Paulo de Pinho
- **Bibliotecas usadas:**
  - Matplotlib (Visualização de gráficos)
  - Numpy (Cálculos matemáticos e arrays)
  - Ipywidgets (Interatividade para simulação de tensão)
  - Unicodedata (Nativa do Python para tratamento de texto)

------

## Proposta do Projeto

O objetivo deste projeto é calcular a capacitância em capacitores **idênticos** de placas paralelas e analisar como a geometria (área e distância) e a escolha de diferentes materiais dielétricos influenciam na capacidade de armazenamento de carga, tanto em associações em série quanto em paralelo.

### Objetivos:

1. **Calcular Capacitância Individual e Equivalente:**
   - Implementar fórmulas físicas para calcular a capacitância baseada na área das placas, distância e constante dielétrica do material (ex: Vácuo, Vidro, Papel, etc.).
   - Calcular as capacitâncias equivalentes para associações em **série** e em **paralelo**.
2. **Comparação Visual:**
   - Gerar gráficos de barras comparativos para visualizar a diferença de magnitude entre a capacitância de um único componente versus suas associações.
3. **Simulação de Armazenamento de Carga (Interativo):**
   - Simular a aplicação de uma bateria (Tensão $V$) ao circuito.
   - Gerar um gráfico interativo (Tensão $\times$ Carga) que demonstra o comportamento da carga armazenada ($Q$) à medida que a tensão aumenta, comparando as diferentes associações.

------

## Como Executar o Projeto

Você pode executar o projeto de duas maneiras. O método com ambiente virtual (`venv`) é o mais recomendado, pois isola as dependências do projeto do restante do seu sistema.

### Método 1: Com Ambiente Virtual (Recomendado)

Este método requer apenas `git` e `python` instalados. O comando a seguir irá clonar o repositório, criar um ambiente virtual (`venv`), instalar as dependências (`numpy`, `matplotlib`, `ipywidgets` e `notebook`) dentro dele e, em seguida, iniciar o Jupyter Notebook.

**Para usuários de Windows:**

Execute este comando no **CMD** (não no PowerShell):

``` cmd
git clone https://github.com/CarvDev/Projeto2-Fisica-UESC.git && cd Projeto2-Fisica-UESC && python -m venv venv && venv\Scripts\pip install numpy matplotlib notebook ipywidgets && venv\Scripts\jupyter notebook "Projeto.ipynb"
```

**Nota:** Se precisar usar o PowerShell, execute os comandos um por um, pois o operador `&&` pode não funcionar dependendo da sua versão.

**Para usuários de Arch/Fedora e derivados:**

``` bash
git clone https://github.com/CarvDev/Projeto2-Fisica-UESC.git && cd Projeto2-Fisica-UESC && python -m venv venv && venv/bin/pip install numpy matplotlib notebook ipywidgets && venv/bin/jupyter notebook "Projeto.ipynb"
```

**Para usuários de Debian/Ubuntu/Mint e derivados:**

``` bash
git clone https://github.com/CarvDev/Projeto2-Fisica-UESC.git && cd Projeto2-Fisica-UESC && python3 -m venv venv && venv/bin/pip install numpy matplotlib notebook ipywidgets && venv/bin/jupyter notebook "Projeto.ipynb"
```

### Método 2: Usando Pacotes do Sistema

Este método assume que você **já possui** o `git`, `python`, `numpy`, `matplotlib`, `ipywidgets` e `jupyter notebook` instalados no seu sistema (globalmente).

**Copie e cole no seu Terminal/CMD:**

``` bash
git clone https://github.com/CarvDev/Projeto2-Fisica-UESC.git && cd Projeto2-Fisica-UESC && jupyter notebook "Projeto.ipynb"
```
