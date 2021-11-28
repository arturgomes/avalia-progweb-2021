# Avaliação final de Programação para Web. 2021 - SINF/CPAN

## Observações:
- todo o conteúdo da atividade deve ser escrito nesse arquivo: App.tsx
- A atividade avaliativa é *INDIVIDUAL* 
- Observe que a partir da etapa 4, você deverá fazer um commit ao encerrar cada uma delas, nomeando o commit de acordo com o nome da etapa.
- A submissão será aceita com último commit até as 23h59 do dia 30/11. 
- O commit `Entrega da atividade` que for enviado após esse horário sofrerá uma penalidade de 1 ponto por hora de atraso, e não será aceito após 3h de atraso.


## Tarefa:
0. Clonar o repositório ```https://github.com/arturgomes/avalia-progweb-2021```

1. Criar seu próprio repositório no git e configurá-lo com o conteúdo do repositório clonado
2. _dar commit em seguida contendo a frase_: `Inicio de projeto`
3. Executar a aplicação com `yarn start` 
4. (1 ponto) Configurar o arquivo `api.ts` com as definições do _Axios_ e importá-lo no arquivo `App.tsx` (_dar commit em seguida contendo a frase_: `Etapa 4`) 
5. (1.5 pontos) Consultar a rota `/posts/` e imprimir num `console.log` (_dar commit em seguida contendo a frase_: `Etapa 5`)
6. (1.5 ponto) Salvar todas as postagens obtidas pelo item 4 em uma variável de estado chamado `posts` (_dar commit em seguida contendo a frase_: `Etapa 6`) 
7. (3 pontos) Criar um select box para que o usuário possa selecionar o `userId` que ele queira listar as postagens  (_dar commit em seguida contendo a frase_: `Etapa 7`)
   - O `userId` deverá ser filtrado do array de objetos da variável `posts`.
8. (3 pontos) Formatar o conteúdo da variável `posts` em uma tabela formatada de forma semelhante à que foi a tabela da aplicação "poupancinha" usando a biblioteca `styled-components` (_dar commit em seguida contendo a frase_: `Entrega da atividade`)
   - Apenas um `userId` deverá ter seus posts exibidos, pela realização da `Etapa 7`.
9.  Dar o commit final e postar o link do repositório no Classroom