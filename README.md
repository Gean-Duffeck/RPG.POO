# RPG.POO
🧙‍♂️ RPG Básico com Classes Abstratas em Python
Este projeto é um exemplo simples de como usar classes abstratas em Python para criar um sistema básico de personagens para um RPG. Ele demonstra o conceito de polimorfismo e herança, permitindo que diferentes tipos de personagens compartilhem comportamentos comuns enquanto implementam suas próprias ações específicas.

🚀 Funcionalidades
Classe Abstrata Personagem: Define a estrutura base para todos os personagens, garantindo que cada um tenha métodos para atacar e usar habilidades especiais.
Classes de Personagem Concretas: Guerreiro, Mago e Ladino herdam de Personagem e implementam suas próprias lógicas para ataques e habilidades.
Seleção de Personagem: Permite que o jogador escolha entre os personagens disponíveis na linha de comando.
Exibição de Status: Cada personagem pode exibir seu status inicial.

🛠️ Tecnologias Utilizadas
Python 3.x

📦 Como Rodar o Projeto
Siga os passos abaixo para executar o projeto em sua máquina local:

Clone este repositório (se ainda não o fez):
Bash

git clone <URL_DO_SEU_REPOSITORIO>
Navegue até o diretório do projeto:
Bash

cd <nome_do_diretorio_do_projeto>
Execute o script Python:
Bash

python RPG.POO.ipynb

☁️ Como Rodar Este Código no Google Colab
Este projeto foi realizado no Google Colab, um ambiente de notebook Jupyter gratuito que roda na nuvem.

💻 Passos para Executar no Colab
Abra o Google Colab: Vá para colab.research.google.com no seu navegador e certifique-se de estar logado na sua conta Google.

Crie um Novo Notebook: Na tela inicial, clique em "Novo Notebook". Isso abrirá um novo ambiente de desenvolvimento.

Cole o Código: Copie todo o código Python fornecido e cole-o diretamente na primeira célula de código vazia do notebook.

Execute o Código: Clique no botão de "Play" (um triângulo) no canto superior esquerdo da célula de código, ou pressione Shift + Enter. A interação com o programa, como a escolha do personagem, ocorrerá no console abaixo da célula.

🎮 Exemplo de Uso
Ao executar o script, você verá o seguinte menu:

Bem-vindo a batalha!

Escolha seu personagem para a próxima missão:
1. Guerreiro
2. Mago
3. Ladino
Digite o número da sua escolha:

Após fazer sua escolha (por exemplo, digitando 2 para Mago), a saída será:
Você escolheu um Mago!
Eu sou um Mago e estou pronto para a aventura!

Depois você tem a opção de atacar (personagem_escolhido.atacar()) que a saída será:
Mago lança um projétil de energia arcana!

Ou pode escolher a opção de usar habilidade (personagem_escolhido.usar_habilidade_especial()) que terá como saída:
Mago conjura 'Bola de Fogo'!

✒️ Autor
Gean Rodrigues Duffeck/Gean-Duffeck - Criador do projeto.
