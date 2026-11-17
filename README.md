# BERT-AI-HW-Accelerator

## My contribution: GELU

The [upstream BERT accelerator](https://github.com/MohamedHussein27/BERT_AI_HW_Accelerator) was a team project. I implemented the GELU activation block and wrote its testbench.

- [GELU RTL](RTL/GELU) and [lane implementation](RTL/GELU/GELU_Lane/GELU.sv)
- [GELU lane testbench](RTL/GELU/GELU_Lane/GELU_tb.sv)
- [GELU design and verification documentation](Documentation/GELU/GELU_Module_Documentation.md)


## Architecture
![Arch](https://github.com/MohamedHussein27/BERT_AI_HW_Accelerator/blob/main/Documentation/Arch.png)

## FSM Diagram
![Diagram](https://github.com/MohamedHussein27/BERT_AI_HW_Accelerator/blob/main/Documentation/FSM_Diagram.png)

## General Flow
![MHA](https://github.com/MohamedHussein27/BERT_AI_HW_Accelerator/blob/main/Documentation/MHA_flow.png)
![FFN_O](https://github.com/MohamedHussein27/BERT_AI_HW_Accelerator/blob/main/Documentation/FFN_output_flow.png)
