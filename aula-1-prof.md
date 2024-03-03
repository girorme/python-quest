### Aula 1: Python Quest - Introdução ao Python

#### Objetivo:
Nesta aula, vamos explorar os conceitos básicos de Python enquanto mergulhamos no tema de RPGs. Vamos aprender como criar um simples programa Python que simula a criação de personagens para um jogo de RPG.

#### Tópicos Abordados:
1. **Introdução ao Python**:
   - Explicação sobre o que é Python e por que é uma ótima linguagem para iniciantes.
   - Como instalar Python e configurar um ambiente de desenvolvimento (VSCode, Jupyter Notebook, etc.).

2. **Primeiros Passos em Python**:
   - **print()**: Aprender a usar a função `print()` para exibir mensagens na tela.
   - **Variáveis**: Entender o conceito de variáveis e como armazenar informações nelas.
   - **Tipos de Dados**:
     - **Números Inteiros (int)**: Números inteiros positivos ou negativos.
     - **Números de Ponto Flutuante (float)**: Números com parte decimal.
     - **Strings (str)**: Sequências de caracteres entre aspas simples ou duplas.
     - **Booleanos (bool)**: Valores True ou False que representam verdadeiro ou falso, respectivamente.

3. **Exemplo de Programa: Criando um Personagem de RPG**:
   - Vamos criar um programa simples que solicita ao jogador que insira o nome, a classe, o nível e outras informações do personagem para um jogo de RPG.
   - Utilizaremos a função `input()` para receber entrada do usuário e armazenar as informações em variáveis.
   - Em seguida, vamos exibir na tela uma mensagem de boas-vindas com os detalhes do personagem criado.

#### Exemplo de Código:
```python
# Solicita ao usuário que insira o nome, a classe, o nível e outras informações do personagem
nome = input("Digite o nome do seu personagem: ")
classe = input("Escolha a classe do seu personagem: ")
nivel = int(input("Digite o nível do seu personagem: "))
pontos_vida = float(input("Digite os pontos de vida do seu personagem: "))
possui_arma = bool(input("O seu personagem possui arma? (True/False): "))

# Exibe uma mensagem de boas-vindas com os detalhes do personagem
print("Bem-vindo,", nome + "!")
print("Classe:", classe)
print("Nível:", nivel)
print("Pontos de Vida:", pontos_vida)
print("Possui Arma:", possui_arma)
```

#### Atividade Prática:
- Peça aos alunos para executarem o programa e experimentarem criar diferentes personagens com diferentes informações, como pontos de vida, presença de arma, etc.
- Incentive-os a modificar o programa para incluir mais informações sobre o personagem e explorar diferentes tipos de dados.

#### Conclusão:
Nesta aula, exploramos os conceitos básicos de Python enquanto mergulhamos no emocionante mundo dos RPGs. Continuaremos a construir sobre isso nas próximas aulas, à medida que nos aprofundamos mais nos conceitos de controle de fluxo, funções e estruturas de dados em Python.