# Sistema de atendimento hospitalar

## R1 — Fila de pacientes

A fila usa uma estrutura encadeada FIFO: pacientes entram no final e são removidos pela frente. Cada nó guarda o nome e a urgência. `frente_peek()` consulta o próximo paciente sem removê-lo, `tamanho()` conta os pacientes, e os nós são liberados ao remover ou destruir a fila.

Na demonstração do R1, os pacientes são atendidos na ordem em que entram: Eduardo, Fernanda, Gabriel e Helena. A urgência fica armazenada em cada nó junto ao nome do paciente.
