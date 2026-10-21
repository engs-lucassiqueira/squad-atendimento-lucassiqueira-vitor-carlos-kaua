# Sistema de atendimento hospitalar

## R1 — Fila de pacientes

A fila usa uma estrutura encadeada FIFO: pacientes entram no final e são removidos pela frente. Cada nó guarda o nome e a urgência. `frente_peek()` consulta o próximo paciente sem removê-lo, `tamanho()` conta os pacientes, e os nós são liberados ao remover ou destruir a fila.

Na demonstração do R1, os pacientes são atendidos na ordem em que entram: Eduardo, Fernanda, Gabriel e Helena. A urgência fica armazenada em cada nó junto ao nome do paciente.

## R2 – Histórico

Implementação de uma pilha para guardar os atendimentos concluídos. O push adiciona um atendimento, o pop remove o último e o peek mostra o último atendimento sem removê-lo.

## R3 – Lista de Médicos

Implementação de uma lista para controlar os médicos disponíveis. É possível adicionar médicos, chamar o próximo médico e visualizar a lista.

## R4 – Relatório de Atendimentos

Implementação de um relatório que mostra os atendimentos registrados, do mais recente ao mais antigo, sem apagar os dados do histórico.