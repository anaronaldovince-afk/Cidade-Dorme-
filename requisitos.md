# Cidade Dorme
## Objetivos
Criar um sistema que utilize do sorteio de personagens para facilitar a partida durante o jogo Cidade Dorme, que haja espaços para escrever o nome dos participantes que ocuparão cada papel, seja ele obrigatório ou essencial; apresentar também a função de cada um dos personagens, o que ele deve fazer e as condições para sua vitória ou derrota. Também adicionar uma tela de confirmação entre o sorteio e revelação de cada papel

### Stack Tecnlógico
- Backend: PHP estruturado com sessões nativas
- Banco de dados: MySQL (PDO para segurança)
- Frontend: HTML5, PHP, CSS, Tailwind CSS

#### Regras de negócio (CORE)
Tratar senhas de usuários com hash bcript
O sistema deve ter uma página de históricos e manter sempre os logs de qualquer alteração feita por qualquer usuário, para auditorias futuras.

##### Regras Globais
- Use sempre PDO para conexão e queries no MySQL para evitar SQL Injections
- Mantenha o código limpo e comente apenas logicas complexas.
- Separe os arquivos de forma lógica: um arquivo para conexão com a base (bd.php) e scripts de backend isolados e views em HTML5/PHP, nunca faça o sistema como um monolito, deixe sempre separados todas as regras para facilitar os futuros upgrades.
 - Estilize as telas em Tailwind de forma responsiva priorizando o MobileFrist.
 - Retorne sempre as mensagens de erros de forma claras na interface para o usuário (TOAST)
 - sempre trate as mensagens de caixa de mensagens nativas do navegador em um MODAL
