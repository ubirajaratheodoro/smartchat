# From meter photos to payment messages

**English** | [Português](README.pt-BR.md)

A demonstration of SmartChat with the Task Planning Template: turning an air-conditioning electricity usage routine into a task with reusable instructions.

**This is a demonstration only.** The task instruction file is not available for download. Names, dates, readings and amounts in the example below are fictional. Private conversations and source files are not published.

## The everyday task

For each billing run, the user needed to check meter photos, locate each guest's previous reading, calculate usage and charges, update an existing spreadsheet and prepare individual messages. Readings were taken at variable intervals, rather than on a fixed monthly schedule.

## Step 1 — Explain the need

With SmartChat and the planning template attached, the user described the task in ordinary language. This is an adapted summary, translated from Portuguese:

> I want to calculate guests' air-conditioning electricity usage from meter photos. Use the attached template to prepare the task instructions. Ask the necessary questions one at a time. When finished, provide the instruction file for me to review. Do not execute the task yet.

## Step 2 — Answer the questions

SmartChat helped clarify the expected result and the decisions involved: where readings would come from, how guests would be identified, which period to use, how charges would be calculated and what to do when information was unclear.

The user also defined the outputs: update the existing spreadsheet, preserve its history and prepare messages to copy into WhatsApp.

**The user knows their own routine; the questions help turn that knowledge into organized instructions.**

## Step 3 — Review and save the instructions

The answers were assembled into an instruction file. The user reviewed and approved it before running the task. The file can be reused for subsequent runs and revised when requirements change.

## Step 4 — Request execution

In a new conversation, with the instruction file attached, the user requested execution. Translated from Portuguese:

> Carry out the task following the attached instruction file. Ask for any information and documents you need before starting.

With access to the photos and spreadsheet, SmartChat collected the run-specific information, checked readings and asked the user to resolve uncertainties. The documented run required confirmation of an initial reading and clarification of a spelling difference between a filename and the spreadsheet.

## Step 5 — Review the result and use the messages

The spreadsheet was updated with a backup and presented for review. After the user's confirmation, image archiving and individual message preparation were completed.

**The messages were ready to copy and send. No messages were sent automatically.**

## An illustrative result

These figures were created solely for this demonstration. They do not reproduce real guests' values and were not obtained in a new execution against photos. The example uses a fictional flat rate of BRL 2.00/kWh, with no additional bands.

Illustrative period: **September 1 to October 1, 2026**. Currency: Brazilian reais (BRL).

| Fictional guest | Previous reading (kWh) | Current reading (kWh) | Usage (kWh) | Charge (BRL) |
|---|---:|---:|---:|---:|
| Guest A | 500.00 | 512.50 | 12.50 | 25 |
| Guest B | 800.00 | 820.00 | 20.00 | 40 |
| Guest C | 300.00 | 300.00 | 0.00 | 0 |
| **Total** | — | — | **32.50** | **65** |

Illustrative message, translated into English:

> Hello, Guest A!
>
> Here is your air-conditioning usage statement for September 1 to October 1, 2026:
>
> Previous reading: 500.00 kWh  
> Current reading: 512.50 kWh  
> Usage: 12.50 kWh
>
> Rate applied: BRL 2.00/kWh.  
> Amount due: BRL 25.
>
> Please pay together with your accommodation payment.
>
> Thank you!

This example would produce two messages. The guest with a zero charge would remain in the spreadsheet without a payment message.

## What this case demonstrates

- A need expressed in everyday language can be organized into reusable instructions.
- A task can combine image reading, historical records, calculations, file updates and text preparation.
- Uncertainties can be referred to the user before affecting the result.
- Human review remains part of the process. File access and suitable tools must be available in the execution environment.

The documented execution used the initial instruction version. A subsequent v002 revision explicitly required confirmation of the saved spreadsheet before archiving images and generating messages. This page does not represent an additional v002 test or measured time savings. The original task ran in Portuguese; this English page is an explanation, not an internationally validated billing specification.

## Want to organize a task of your own?

The **SmartChat Task Planning Template** helps you explain your needs, answer questions and prepare a file of instructions for AI to execute.

You can create other tasks with free SmartChat. The paid template is an optional aid for structuring that preparation; it does not include this private task specification or an implementation service.

[Explore SmartChat and the available options](https://github.com/ubirajaratheodoro/smartchat).

[Back to automations in practice](../README.md).
