# Conciliação financeira: do extrato ao demonstrativo com SmartChat

**Todo mês, os documentos chegam. Como transformar extratos, comprovantes e notas em um demonstrativo que você consiga conferir?**

Nesta aplicação, SmartChat foi utilizado com um padrão de especificação para definir uma tarefa de fechamento financeiro mensal. A especificação resultante orientou a execução assistida, com decisões do usuário nos pontos que exigiam esclarecimento.

**[Baixe o demonstrativo fictício em Excel](demonstrativo-exemplo.xlsx)** para visualizar o tipo de entrega. Para criar suas próprias especificações com uma estrutura pronta, [conheça o padrão na Eduzz](https://sun.eduzz.com/Q9NDKAYP01).

## A necessidade

O trabalho começava com documentos distribuídos em uma pasta mensal: extrato bancário, comprovantes, notas, recibos e outros materiais. Ao final, era necessário produzir uma planilha com as movimentações, suas classificações e informações suficientes para revisão.

Havia decisões importantes: como tratar um pagamento sem nota fiscal? Qual documento deveria prevalecer quando duas fontes divergiam? Como registrar um pagamento que reunia dois impostos? Quais valores entrariam na base indicada pelo usuário?

A proposta foi transformar essas decisões em orientações explícitas para uma tarefa reutilizável.

## Como a tarefa foi construída

### 1. Descrever o trabalho com suas próprias palavras

O usuário iniciou a conversa explicando que desejava preparar uma conciliação financeira e forneceu o padrão como referência. Não precisou começar com um prompt técnico ou com todas as respostas prontas.

SmartChat passou a esclarecer o que seria conciliado, para qual finalidade e qual resultado deveria ser entregue.

### 2. Esclarecer as decisões que mudam o resultado

Ao longo da conversa, foram definidos os documentos disponíveis, a fonte principal dos movimentos, as categorias de classificação e a forma de tratar dúvidas e pendências.

O usuário pôde corrigir escolhas durante a elaboração. Por exemplo, o acionamento da tarefa ficou manual: o fechamento começa quando ele solicita, em vez de depender de um monitoramento automático da pasta.

Essa etapa tornou visíveis condições que poderiam ficar implícitas em um pedido genérico de “fazer a conciliação”.

### 3. Organizar as definições em uma especificação

As decisões foram reunidas em um arquivo de tarefa, revisado e aprovado pelo usuário. Esse documento passou a orientar o que fazer e como conferir a entrega nas execuções seguintes.

O padrão forneceu a estrutura para essa elaboração; SmartChat ajudou a preenchê-la com as particularidades do trabalho. A especificação completa e a estrutura interna do padrão não são publicadas nesta demonstração.

## Da especificação à execução

Com a tarefa definida, foram disponibilizados os documentos do período. A execução leu os movimentos, conferiu os saldos e relacionou os lançamentos aos documentos disponíveis.

As dúvidas não foram resolvidas por adivinhação. O usuário confirmou um vínculo documental, escolheu categorias e determinou o tratamento de exceções. Entre as decisões do caso:

- Utilizar uma categoria geral de receitas de aluguel, identificando cada locatário na descrição.
- Separar PIS e COFINS em duas linhas quando pagos na mesma movimentação bancária, preservando o valor total.
- Registrar adiantamentos com a pendência da nota fiscal visível, após autorização do usuário.
- Confirmar quais recebimentos integrariam a base indicada na planilha, sem adotar uma regra tributária por suposição.

Por isso, trata-se de **execução assistida**: a IA realiza o trabalho conforme as orientações, e o usuário participa das decisões e da revisão final. Criar uma especificação não instala, por si só, uma integração nem um agendamento.

## O que o teste mostrou

O resultado do teste com documentos reais foi comparado ao demonstrativo de referência do mesmo período. Saldos, entradas, saídas e base confirmada coincidiram. A diferença na quantidade de linhas foi explicada pelo desdobramento autorizado do pagamento de dois impostos.

A nova entrega também apresentou vínculos aos documentos e as pendências liberadas pelo usuário. Ajustes de apresentação podem fazer parte da implantação; a conferência deve garantir que valores e informações importantes continuem legíveis.

Esse teste demonstra o funcionamento no caso examinado. A aplicação em outros períodos exige fornecer as respectivas entradas, verificar os recursos disponíveis e revisar o resultado.

## Visualize o resultado

O arquivo abaixo é uma **ilustração criada com dados inteiramente fictícios** para mostrar a apresentação da entrega. Ele não contém os dados do fechamento real e não representa uma nova execução de conciliação sobre um conjunto público de comprovantes.

**[Baixar demonstrativo fictício (.xlsx)](demonstrativo-exemplo.xlsx)**

| Controle ilustrativo | Valor fictício |
|---|---:|
| Saldo inicial | R$ 12.000,00 |
| Entradas | R$ 15.000,00 |
| Saídas | R$ 7.320,00 |
| Saldo final | R$ 19.680,00 |
| Base confirmada no exemplo | R$ 7.500,00 |

Há 11 movimentos fictícios representados em 12 linhas: um pagamento de impostos foi desdobrado em PIS e COFINS. Não há documentos reais ou links privados associados aos lançamentos. As escolhas de classificação e base servem à demonstração e não estabelecem regras fiscais para outros casos.

## E para criar uma tarefa do seu trabalho?

Você pode usar SmartChat gratuitamente e elaborar sua própria estrutura. O padrão pago oferece uma estrutura pronta para organizar a criação da especificação, reduzindo o trabalho de começar do zero.

**[Conheça o padrão de especificação na Eduzz](https://sun.eduzz.com/Q9NDKAYP01)**

O padrão ajuda a descrever a tarefa. O conteúdo específico, as ferramentas necessárias e os testes de execução dependem da aplicação que você deseja construir.

O link da Eduzz é provisório e será atualizado pelo mantenedor.

O vídeo demonstrativo será acrescentado a esta página quando estiver disponível.

[Outras aplicações do SmartChat](../README.md) · [Instalação e primeiros passos](../../docs/instalacao.md)
