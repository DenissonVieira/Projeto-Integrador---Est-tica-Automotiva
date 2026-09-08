# Sistema de Agendamentos de Serviços para Estética Automotiva

## Objetivo

Desenvolver um sistema para gerenciar os agendamentos de serviços dos clientes, visando substituir o sistema atual de agendamentos via WhatsApp.

---

## Usuarios do Sistema

- Administrador
- Recepcionista
- Cliente

## Problemas Identificados

- Demora no atendimento (Tambem serve para a resposta do cliente).
- Controle manual da quantidade de serviços/atendimento.
- Controle manual da quantidade de pagamentos.
- Informações espalhadas em papel (Agenda).
- Risco de perda de dados.

## Requisitos Funcionais

- RF01 - Cadastrar cliente.
- RF02 - Editar cliente.
- RF03 - Excluir cliente.
- RF04 - Registrar serviços.
- RF05 - Registrar pagamentos via pix.
- RF06 - Gerenciar planilha de agendamentos.
- RF07 - Emitir relatórios.

## Requisitos Não Funcionais

- RNF01 - O sistema deve possuir autenticação.
- RNF02 - O sistema deve funcionar de forma eficiente.
- RNF03 - Tempo de resposta inferior a 3 segundos.
- RNF04 - Os dados devem possuir backup periódico.
- RNF05 - Apenas usuários autorizados poderão acessar determinadas funcionalidades.

## Regras de Negócio

- RN01 - Cada cliente registrado deve possuir um CPF único.
- RN02 - Cada cliente poderá fazer até 2 agendamentos por semana, sem precisar de pagamento antecipado para confirmar o agendamento.
- RN03 - O cliente que faz o agendamento e não comparece, para efetuar um novo agendamento somente com pagamento antecipado.
- RN04 - Apenas administradores podem excluir ou desmarcar clientes.


## Dúvidas para o Cliente

- Existe a integração com maquininhas ou links de pagamento?
- A estética possui mais de uma unidade?
- O cliente poderá cancelar o agendamento?
- Haverá emissão de recibos?