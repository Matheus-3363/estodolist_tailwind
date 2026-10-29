                                   PROJETO EsToDo List

Objetivo do Projeto:  
O EsToDo List é um projeto feito para fins educativos onde acaba servindo para facilitar na gestão de tarefas e provas, tendo uma interface versátil que qualquer um consegue entender. Além disso, entregar e adicionar tarefas ficou muito mais fácil, podendo realizá-las de forma rápida e com poucos cliques.

Requisitos Funcionais (RF):

* Cadastrar tarefas:  
  O usuário dará informações da tarefa (Prazo, Informações adicionais e links adicionais, além de um campo de observações).  
    
* Editar tarefas Existentes:  
  O usuário poderá editar seus posts já existentes (podendo mudar informações, adicionar mais e mudar o prazo de entrega).  
    
*  Excluir Tarefa:   
  Caso o usuário queira apagar alguma tarefa existente, aparecerá um campo de  confirmação para a ação (tendo 2 botões, de confirmar, e o de cancelar), caso ele confirmar, a tarefa será apagada e será mandada para a lixeira (caso o criador queira a restaurar ou a apagar permanentemente).

* Marcar Tarefa como Concluída:  
  Ao entregar uma tarefa, a tarefa colocará onde antes estava marcado como “Entregar” como “Entregue”, além que nas partes gerais de tarefa, ficará com um ícone de “✓” ao lado da tarefa entregue.  
    
* Pesquisar/Filtrar Tarefas:   
  O usuário poderá ver as atividades por matérias na barra de tópicos, tendo o registro de todas as atividades e registros da matéria.

 Requisitos Não Funcionais (RNF) 

* Interface intuitiva:  
  Interface fácil e prática para todos os usúarios possam conseguir utilizar e entender facilmente

* Ações rápidas: Ações devem demorar o máximo de 2 segundos para responder às ações do usuário  
    
* Responsivo:  
  Deve conseguir funcionar em aparelhos principais (Como celular e computador)

Fora de Escopo 

* Adicionar Vídeo:  
  Seria uma funcionalidade interessante, mas acaba não entrando por conta de ter uma necessidade tão alta e sendo muito complexo  
* Customização do site:  
  Acaba não entrando por conta de ser algo que não ser tão necessário para os usuários por enquanto

Metodologia Cascata

| Requisitos | Análise e projeto | Desenvolvimento | Testes | Implementação e Manutenção |
| :---- | :---- | :---- | :---- | :---- |
| 10\. Escrever o Documento de Escopo com todas as funcionalidades | 1.Desenhar as telas do aplicativo no Figma | 5\. Escrever o código HTML da página principal | 3.Verificar se o aplicativo funciona corretamente nos navegadores Chrome e Firefox | 6\. Publicar a versão final do site em um servidor online para que todos possam usar.  |
| 4.Entrevistar alunos para entender como eles organizam suas tarefas hoje. | 9.Definir a paleta de cores e a fonte que serão usadas no site. | 7.Programar a função em JavaScript que salva uma nova tarefa no navegador | 8\. Tentar "quebrar" o campo de data, inserindo um texto em vez de um número.  | 2\. Corrigir um bug reportado por um usuário uma semana após o lançamento. |
| Especificar os critérios de desempenho e usabilidade (como garantir o tempo de resposta em até 2 segundos e a responsividade em celulares e computadores).  | Desenhar o mapa de navegação com o passo a passo que o usuário fará (ex: clicar em *Adicionar* ➔ preencher dados ➔ receber confirmação).  | Aplicar a paleta de cores, tipografia e regras de responsividade para garantir uma interface intuitiva no computador e no celular.  | Testar a interface em telas de diferentes tamanhos (celulares e computadores) para garantir que a navegação continue fácil e intuitiva em qualquer dispositivo. | Acompanhar a velocidade e o tempo de carregamento do site para garantir que as ações continuem levando no máximo 2 segundos.  |
| Definir o comportamento exato das tarefas (como o funcionamento da lixeira e o prazo limite de retenção das tarefas excluídas antes da deleção permanente). | Montar uma versão clicável das telas no Figma para testar a interatividade e a facilidade de uso com pessoas reais.  | Programar a exclusão de tarefas com a caixa de confirmação e a transferência para a lixeira em JavaScript.  | Testar o ciclo de vida da tarefa (excluir, confirmar a caixa de diálogo e restaurar) para garantir que nada seja apagado permanentemente por engano.  | Criar um meio de comunicação (como um formulário simples de contato) para que os alunos possam enviar sugestões de melhorias e relatar possíveis bugs.  |

