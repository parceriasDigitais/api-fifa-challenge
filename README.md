# API-FIFA-CHALLENGE

### - DESCRIÇÃO DA NECESSIDADE
 Deverá ser construido uma API para atender um MVP que será responsável por gerenciar o ranking de jogadores amadores de FIFA.
 
 É necessário que a API possua os seguintes componentes:

  #### 1 - Cadastro de jogadores
   Este recurso receberá os dados de players que desejam criar ou ingressar em uma liga já existente.
   * Será permitido apenas 1 cadastro por email
      * Campos minimos obrigatórios no cadastro dos players (nome, email, username)
      * Operações de cadastro, edição e exclusão serão permitidas.

  #### 2 - Cadastro da liga
   Este recurso receberá o cadastro do nome da liga 
   * O cadastro da liga não poderá repetir o nome para o mesmo proprietário
      * Campos minimos obrigatórios no cadastro da liga (nome)
      * Operações de cadastro, edição e exclusão serão permitidas.
      * Em operações de consulta da liga deverá ser possivel ver todos os membros associados a liga
      * Em operações de consulta da liga será possivel também ver todos jogos e rodadas da liga.
		
  #### 3 - Solicitar acesso a liga
   Este recurso permite que um player cadastrado possa localizar e ingressar em uma liga existente.
   * O proprietário da liga deverá permitir o que o usuario se associe a liga.
      * Operações de consulta, quando o player não está associado deverá apenas permitir que o player se associe.
      * O player pode deixar de fazer parte da liga

  #### 4 - Sorteio de jogos
  O proprietário da liga efetua o sorteio dos jogos para rodada corrente.
      * Operações gera uma nova rodada com os jogos intercalados entre os membros da liga.
	
  #### 5 - Cadastrar os resultados dos jogos
  O player que faz parte do jogo, pode incluir o placar jogo para a rodada corrente.

  #### 6 - Exibir ranking
  Todos os players do ranking podem ver a pontuação dos membros da liga em que faz parte e também o ranking global dos 10 maiores campeões do aplicativo.


### - PLUS DA ENTREGA
- Implementação de segurança (authenticação e autorização); 
- Implementação de paginação nos retornos de lista
- Disponibilidade da API em ambiente de cloud (AWS/Heroku/Etc); 


### - ORIENTAÇÕES
  - Crie um repositório privado chamado api-fifa-challenge no github e faça um fork da estrutura basica.
  - Desenvolva a solução para resolver a necessidade do desafio
  - Faça o commit das alterações realizadas
  - Adicione o usuario parceriasDigitais com acesso de leitura do projeto.
  
  
  
### - BOA SORTE!!! ;]
