# How to use SmartChat

[Português](uso.md) | **English**

## Start with the outcome you want

After installing and selecting SmartChat, explain your goal and provide the context you have. You do not need an elaborate prompt.

Example:

> I want to organize how I prepare sales proposals. Today I receive information through messages and assemble each proposal manually. I need to define a task I can repeat for new clients. Please respond in English.

During the conversation, SmartChat may ask for information, examine assumptions, and summarize its understanding for you to confirm. Answer with what you know; say when something is still undecided. If a question seems unrelated to your goal, ask it to reconsider whether that information is needed.

## Work with relevant materials

When useful, provide an example of the expected result, applicable rules, and required inputs. Check that the environment can access the files. Explain the limits of the work and which operations are authorized.

## Use a ready-to-use task

**Start with a free option to try it out.** If you later need a different task or customized instructions, explore the option below.

Browse [tasks and examples](../downloads/README.en.md) and check the language and scope of each one before downloading.

The free [standard financial reconciliation task — Portuguese only](../downloads/conciliacao-financeira/README.md) is prepared for use in Brazil, for one bank account in BRL over one month. Its instructions, tutorial, video, and sample spreadsheet remain in Portuguese. It has not been adapted to other countries.

For that Portuguese task, attach its instruction file to a conversation with SmartChat and use the starting message shown in its tutorial:

> Faça minha conciliação financeira seguindo o arquivo de instruções anexado.

The assistant will ask for the documents, period, and other required information. The tutorial and demonstration materials are in the same folder as the download.

## Create your own tasks

You can talk to SmartChat to organize an activity and define how to perform it. If you prefer a predefined structure, the **SmartChat Task Planning Template** is a separate paid product, currently available in Portuguese as **Modelo de planejamento de tarefas com SmartChat**.

**Stage 1 — Create the instructions**

1. Open a conversation with SmartChat selected.
2. Attach the **SmartChat Task Planning Template** file received with your purchase. You do not need to fill in or edit the template.
3. Copy the message below and replace only the text in brackets:

> I want AI to help me with this task: [describe what you need].
>
> I am attaching a template for preparing the task instructions. Ask the necessary questions, one at a time, and use my answers to create the instruction file.
>
> When it is ready, give me the file to review. Do not run the task yet. Please respond in English.

For example: “preparing sales proposals using information from my clients.” Answer the questions, review the instructions, request any changes needed, and save the approved file. Requesting English output does not change the language of the purchased template.

**Stage 2 — Run the task**

Open a new conversation with SmartChat and attach **the instruction file created in the previous stage**. Send:

> Carry out the task following the attached instruction file. Ask any questions you need answered and request the necessary documents before starting. Please respond in English.

Provide the requested documents, information, and access. For the first run, test with known inputs and check the result before using it.

**To repeat the task, reuse the instruction file you created and provide the inputs for the new run.** The template is for creating the instructions; you do not need to attach it again for every run. If your requirements change, review the instructions before reusing them. This does not create an automatic schedule.

## Optional traceability module

The package includes an epistemic traceability module for scientific work. It starts disabled in new conversations. To request it, use the exact command `ativar rastreabilidade epistêmica`; to turn it off, use `desativar rastreabilidade epistêmica`.

These Portuguese commands mean “enable epistemic traceability” and “disable epistemic traceability.” They are preserved here as provided in the package.

The module organizes claims, sources, checks, and decisions. It does not provide access to the model's internal workings or automatically prove that a statement is true. You do not need it to get started with SmartChat.

## Tools and data

The package contains instructions and references. It does not include its own MCP server or storage integration. Access to the internet, files, Google Drive, and other services depends on the environment, available integrations, and your permissions.

Before using client data, check the permissions and data-handling terms of the services involved. For learning or demonstrations, prefer clearly labeled fictional examples or appropriately anonymized data.

[All downloads](../downloads/README.en.md) · [Back to SmartChat](../README.en.md)
