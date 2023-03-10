# lista_tarefas

Projeto Flutter - Lista de Tarefas

## Getting Started

Aplicativo desenvolvido para registrar qualquer tipo de tarefa, podendo adicionar título e descrição, editar, excluir temporiamente e permanentemente, as tarefas por padrão ficam pendentes depois de criadas, podendo marcar como concluído e também adicionar aos favoritos. Para gerência de estado é utilizado apenas o bloc e para salvar os dados no dispositivo é utilizado o HydatredBloc;

- Adicionar tarefas através de uma modal contendo o título e descrição;
- Para atualizar e renderizar os itens da tela é utilizado o BlocBuilder;
- MultiBlocProvider para fornecer dados para os widgets filhos;
- As tarefas adicionadas são exibidas em um List.builder;
- Validação no formulário para não adicionar tarefas com texto em branco;
- Existem 4 tipos de identificação para as tarefas. Elas são: Tarefas pendentes, tarefas concluídas, tarefas favoritas, e tarefas removidas;
- Cada tarefa da lista contém um PopupMenu podendo editar, excluir e adicionar ou remover dos favoritos;
- Na lixeira ao abrir o popupMenu e clicar em excluir, o item é excluído permanente. Pode também excluir toda a lista clicando no botão na appBar;
- Lógica desenvolvida para poder adicionar, excluir, editar, ou adicionar ou retirar dos favoritos em qualquer tela;
- Os items da lixeira podem ser restaurados;
- Salvar e restaurar o estado do bloc utilizando o HydratedBloc assim persistindo os dados;
- Opção para mudar o aplicativo inteiro para modo noturno;
