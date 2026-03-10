# 🎵 Grave–Médio–Agudo

O **Grave–Médio–Agudo** é um sketch interativo desenvolvido na linguagem **Processing** que funciona como um indicador visual para atividades musicais coletivas. Ele representa graficamente as regiões **aguda, média e grave** do som por meio da posição de um retângulo na tela.

A ferramenta foi pensada para apoiar práticas pedagógicas com estudantes instrumentistas, especialmente em exercícios de **improvisação coletiva**, nos quais o professor ou um aluno atua como condutor da atividade.

## 🎯 Objetivo do Projeto

O objetivo do programa é auxiliar na percepção e na resposta musical dos estudantes, criando uma relação direta entre **posição visual na tela** e **registro sonoro do instrumento**.

Quando um comando é acionado no teclado, um retângulo aparece em uma posição específica da tela e os músicos devem tocar notas na região correspondente.

## ✨ Funcionamento

Durante a atividade:

- O professor (ou um aluno) pressiona uma tecla no teclado do computador.
- Dependendo da tecla pressionada, um retângulo aparece em uma região da tela.
- Os instrumentistas observam a tela e executam uma nota na região indicada.

### Comandos do teclado

| Tecla | Região representada | Posição na tela |
|------|---------------------|-----------------|
| **a** | Agudo | Parte superior |
| **m** | Médio | Centro |
| **g** | Grave | Parte inferior |

## ⚙️ Lógica do Programa

O sketch funciona em dois blocos principais:

### `setup()`
Executado apenas uma vez quando o programa inicia.

Função:
- abrir o programa em **modo de tela cheia**.

### `draw()`
Executado continuamente em loop.

Funções:
- colorir o fundo da tela;
- verificar se alguma tecla foi pressionada;
- desenhar o retângulo na posição correspondente.

Sempre que o loop reinicia, o fundo da tela é redesenhado, apagando a figura anterior.

## 🛠️ Tecnologias Utilizadas

- **Processing**
- Linguagem baseada em **Java**
- Programação visual interativa

Site oficial:  
https://processing.org/

## ▶️ Como executar

1. Instale a IDE **Processing**.
2. Abra o arquivo do sketch (`.pde`).
3. Execute o programa.
4. Pressione as teclas:
