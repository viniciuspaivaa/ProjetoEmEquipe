# ProjetoEmEquipe

### Gerador de Senhas Aleatórias
Aluno: Vinicius Paiva

**O que foi utilizado**
- Variáveis
- Loop de Repetição ``while`` e ``for``
- Validação com ``TryParse``
- Função ``next`` da Classe Random

**Etapas implementadas**
- Criação das variáveis no escopo global
- Listagem dos caracteres disponíveis para gerar a senha
- Loop While para atribuir o tamanho da senha de forma adequada
- Loop For para que a variável senha receba characteres de acordo com o tamanho

**Backlog**
- Futuras Implementações:
1. Assegurar que o código gere pelo menos um caracter maíusculo, minúsculo e numérico
2. Gerar caracteres especiais

**Conclusão**
- Código que trabalha com conceitos importantes da linguagem C#, possuindo etapas simples para sua confecção e possibilidade de futuros aperfeiçoamentos.
 --------------------------------------------------------------------------------------------------------------------------------------------------------- 
 ### Conversor de Temperaturas
 Aluno/Líder: Marcos Vinícius Dias Almeida
 
 ### **O que foi utilizado**
- Estruturas de Controle: Utilização do ```switch``` para gerenciar diferentes opções de conversão.
- Entrada e Saída: Uso de ```Console.ReadLine() ```para capturar entradas do usuário e ```Console.WriteLine() ```para exibir os resultados.
- Conversões Matemáticas: Aplicação de fórmulas matemáticas para conversão entre escalas de temperatura.
- Tipos de Dados: Uso de ```int``` para a escolha do usuário e double para a temperatura, permitindo cálculos precisos.

### **Etapas implementadas**
  - Solicitação ao usuário para escolher o tipo de conversão de temperatura.
  - Leitura da temperatura a ser convertida.
  - Utilização de um switch para determinar qual conversão será realizada com base na escolha do usuário.
  - Cálculos para converter entre Celsius, Fahrenheit e Kelvin.
 
 ###  **Backlog**
  - Adicionar mais opções de conversão, como Rankine.
  - Feedback ao Usuário: Adicionar mensagens de feedback mais detalhadas após cada conversão para ajudar o usuário a entender os resultados.
    
  ### **Conclusão**
  - O programa de conversão de temperaturas foi implementado com sucesso, permitindo ao usuário converter entre diferentes escalas de temperatura.
  --------------------------------------------------------------------------------------------------------------------------------------------------------
  ### Cronômetro Simples
Aluno: Luiz Eduardo Pereira Brandão

**O que foi utilizado**
- Biblioteca ``System`` e ``System.Threading`` 
- Variáveis
- Loop ``for``
- Validação com ``TryParse``
- Estrutura ``TimeSpan`` 

**Etapas implementadas**
- Pede para o usuario inserir o tempo em segundos
- Inicia a conversão para tempo em número inteiro
- Loop com For para que o tempo começe diminuindo

**Backlog**
- Futuras Implementações:
1. Permitir que o usuário insira horas, minutos, e segundos separadamente

**Conclusão**
- Codígo na linguagem C# possuindo aprimoramento mediano.

--------------------------------------------------------------------------------------------------------------------------------------------------------
### **Escolha da Quantidade de Dados:**
Aluno: Pablo Eduardo Silva

O usuário pode agora escolher quantos dados deseja lançar (de 1 a 6).

**O que foi utilizado**

-Validação da Entrada:
Um loop é usado para garantir que a entrada do usuário esteja dentro do intervalo válido.

-Lançamento dos Dados:
Um loop for é adicionado para lançar os dados escolhidos e exibir o resultado para cada um.

**Etapas implementadas**
- Dado é jogado e o programa seleciona um lado do dado aleatório
- É perguntado se o jogador que jogar novamente

**Backlog**
- um contador para jogar o dado

**Conclusão**

- Neste projeto, implementamos um jogo simples de lançamento de dados em C#. O código permite que o usuário escolha quantos dados deseja lançar, de 1 a 6, e visualiza o resultado de cada lançamento de forma interativa.

- Agora você tem um jogo mais interativo e divertido! Se precisar de mais melhorias ou alterações, é só avisar!
--------------------------------------------------------------------------------------------------------------------------------------------------------

### **Calculadora:**
Aluno: Chrystian Barbosa


Uma simples calculadora de console que executa operações básicas, como adição, subtração, multiplicação e divisão.

**O que foi utilizado**

Console solicita ao usuário a inserir dois valores numéricos.

Em seguida, solicita um operador (+, -, *, /).

**Etapas implementadas**

O código valida se os valores inseridos são numéricos.

Dependendo do operador escolhido, ele realiza a operação correspondente e exibe o resultado.

Para a divisão, há uma verificação para evitar divisão por zero.

**Backlog**

- Melhorar a validação de entrada e montar um loop para que não seja necessário rodar o código novamente em caso de valores incorretos inseridos ou as divisóes por zero.

- Adicionar mais operações ou funcionalidades, como porcentagens.

**Conclusão**

- Este código é apenas uma base para uma calculadora simples, podendo ser aprimorado com mais recursos e validações.
--------------------------------------------------------------------------------------------------------------------------------------------------------
### Cronômetro Simples
Aluno: Luiz Eduardo Pereira Brandão

Um jogo onde é sorteado um número aleatório e o usuário tenta acertar o número.

**O que foi utilizado** 
- Variáveis
- Random e randNum.Next
- Loop ``while``
- Validação com ``TryParse``
- Console.ForegroundColor = ConsoleColor.Cor para pintar o código
- A variável total conta como uma vez digitado um número, ao final é mostrado as tentativas.

**Etapas implementadas**
- O código sorteia um número aleatório para o usuário acertar, com Random é sorteado um número entre 0 e 100.
- O número digitado entra em conversão para inteiro.
- Dicas para o numero digitado, como "Número Acima" e "Número Abaixo".
-

**Backlog**
- Código simples sem futuros aprimoramentos.

**Conclusão**
- Codígo na linguagem C#, código simples com fácil entendimento.

--------------------------------------------------------------------------------------------------------------------------------------------------------
### Decisão de Almoço
Aluno: Vinicius Paiva

**O que foi utilizado**
- Variáveis
- Biblioteca Random
- Array de Strings
- Laço de Repetição ``while`` e ``foreach``
- Validação com ``TryParse``
- Função ``next`` da Classe Random

**Etapas implementadas**
- Inserção classe Random
- Criação do Array itensMenu, contador, escolha e nmr no escopo global
- Listagem dos itens em itensMenu
- Escolha de um prato (uma posição do Array de itensMenu)
- Loop While para adicionar mais escolhas conforme desejado
- Geração de um número aleatório para escolher um prato aleatoriamente de acordo com a posiçao no Array itensMenu

**Backlog**
- Futuras Implementações:
1. Permitir que o usuário remova pratos da lista de escolhas.
2. Implementar uma interface gráfica para melhorar a experiência do usuário.

**Conclusão**
- Código implementa funções simples com objetivo de selecionar pratos ou exibir os mesmos de forma aleatória, permitindo que os usuário explorem o menu e façam suas escolhas.
 --------------------------------------------------------------------------------------------------------------------------------------------------------- 
