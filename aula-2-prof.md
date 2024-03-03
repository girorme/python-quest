### Aula 2: Python Quest - Estruturas de Controle e Funções

#### Objetivo:
Nesta aula, vamos explorar estruturas de controle como condicionais e loops, e aprender sobre funções de uma forma simples e prática, usando exemplos inspirados no mundo dos RPGs.

#### Tópicos Abordados:
1. **Condicionais**:
   - **if**: Verifica uma condição e executa um bloco de código se a condição for verdadeira.
   - **else**: Fornece uma alternativa caso a condição do if seja falsa.
   - **elif**: Permite verificar múltiplas condições.

2. **Loops**:
   - **for**: Permite percorrer uma sequência de elementos, como itens em um inventário.
   - **while**: Executa um bloco de código enquanto uma condição for verdadeira, útil para batalhas ou exploração de masmorras.

3. **Funções**:
   - Permite encapsular um conjunto de instruções para reutilização.
   - Simplifica o código e torna-o mais organizado.

#### Exemplos de Código:

##### Condicionais:
```python
escolha = input("Você deseja abrir a porta? (s/n): ")

if escolha == 's':
    print("Você abriu a porta e encontrou um baú cheio de tesouros!")
else:
    print("Você decide não abrir a porta e continua sua jornada.")
```

##### Loops:
```python
print("Você está explorando uma masmorra sombria...")
for sala in range(3):
    print("Você entra na sala", sala+1, "e encontra um monstro!")
print("Você explorou toda a masmorra e derrotou todos os monstros!")

vida = 10
print("Você encontrou um monstro!")
while vida > 0:
    ataque = int(input("Digite o dano que deseja causar: "))
    vida -= ataque
    print("O monstro ainda tem", vida, "de vida.")
print("Você derrotou o monstro!")
```

##### Funções:
```python
def atacar(ataque, defesa):
    dano = ataque - defesa
    return dano

dano_causado = atacar(8, 3)
print("Você atacou o monstro e causou", dano_causado, "de dano!")
```

#### Atividade Prática:
- Peça aos alunos para experimentarem diferentes cenários com condicionais, loops e funções, adaptando os exemplos fornecidos.
- Incentive-os a criar suas próprias funções simples para realizar tarefas específicas, como calcular o dano de um ataque ou gerenciar a vida de um personagem.

#### Conclusão:
Nesta aula, exploramos estruturas de controle e introduzimos o conceito de funções em Python, aplicando esses conceitos ao contexto emocionante dos RPGs. Continuaremos a desenvolver nossas habilidades e explorar mais desafios interessantes em Python nas próximas aulas do Python Quest.