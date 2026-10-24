# Instalação no ChatGPT e no Codex

O download contém um plugin de instruções e referências. A instalação exige um ambiente com suporte a plugins e permissão para adicionar fontes ou pacotes próprios. Os recursos disponíveis variam conforme conta, aplicativo e políticas do workspace.

## Antes de começar

Leia a [licença de uso gratuito](../LICENSE.md). Se já possui SmartChat instalado, confira a versão antes de instalar outra cópia. O pacote mantém o identificador original `gpt-2bebe66a0306f7d8bd895e2f0a1a141b` e a versão `0.38.3`.

## ChatGPT

Abra a área **Plugins** e confira quais formas de adicionar plugins próprios estão disponíveis na sua conta. Utilize o [ZIP original](../downloads/smartchat-v0.38.3.zip) se o ambiente oferecer importação de pacote. Não anexe o ZIP como documento de uma conversa esperando que isso instale o plugin.

Em workspaces com importação de marketplaces do GitHub, solicite ao administrador a inclusão deste repositório:

```text
https://github.com/ubirajaratheodoro/smartchat
```

Este repositório inclui o catálogo em `.agents/plugins/marketplace.json`. A inclusão de uma fonte é diferente da instalação do plugin; após a fonte estar disponível, localize **SmartChat** e instale-o.

Para uso local no aplicativo de desktop, o catálogo do repositório pode ser utilizado pelo fluxo de marketplace suportado pelo aplicativo. Consulte o [guia oficial de empacotamento e marketplaces](https://developers.openai.com/plugins/build/plugins), especialmente “Install a local plugin manually”.

Se sua conta não oferecer uma dessas opções, o ZIP sozinho não libera a instalação. Verifique as opções atuais na [documentação oficial de plugins](https://learn.chatgpt.com/docs/plugins). Este repositório não garante importação em todos os planos ou ambientes.

## Codex CLI

Em uma versão com suporte ao comando de marketplaces, registre a fonte:

```shell
codex plugin marketplace add https://github.com/ubirajaratheodoro/smartchat.git
```

Depois abra o Codex e execute `/plugins`. Selecione a fonte **SmartChat**, localize o plugin e instale-o. Inicie uma nova sessão após a instalação.

No aplicativo de desktop, procure a fonte no diretório de plugins, conforme os marketplaces configurados no ambiente. A extensão IDE não é o caminho de instalação descrito aqui.

## Confira a instalação

1. Inicie uma nova conversa ou sessão.
2. Selecione **SmartChat** pelo seletor de plugins ou pela menção com `@`, quando disponível.
3. Envie: “Use o SmartChat para me ajudar a organizar uma tarefa recorrente. Quero definir o resultado, as informações necessárias e como conferir a entrega.”
4. Confirme que o SmartChat está selecionado e que a conversa considera o objetivo e as informações necessárias. A aparência de uma resposta, sozinha, não comprova a instalação.

Depois, consulte o [guia de uso](uso.md) e o [prompt para criar uma tarefa](../prompts/criar-tarefa.md).

## Limites desta publicação

O pacote preserva os arquivos exportados fornecidos pelo mantenedor. A integridade do ZIP e a estrutura dos arquivos foram conferidas; estes passos de instalação ainda precisam ser confirmados em cada ambiente de destino. Publicar o repositório não equivale a uma aprovação no catálogo público da OpenAI.

Referências oficiais consultadas em 24/10/2026: [Plugins](https://learn.chatgpt.com/docs/plugins), [Package your plugin](https://developers.openai.com/plugins/build/plugins) e [Plugin management](https://learn.chatgpt.com/docs/enterprise/plugin-management).
