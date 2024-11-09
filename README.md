# Sistema de Agendamento de Ambientes

Este é um sistema de agendamento para a web que permite que usuários e administradores façam e gerenciem reservas de ambientes e recursos, como Biblioteca, JBL, Multiuso, Interioridades, entre outros.

## Índice
- [Funcionalidades](#funcionalidades)
- [Pré-requisitos](#pré-requisitos)
- [Instalação](#instalação)
- [Uso](#uso)
- [Login](#login)
- [Personalização](#personalização)
- [Considerações](#considerações)

## Funcionalidades

- **Login para usuários específicos**: Login básico para escolas e administradores.
- **Agendamento em etapas**: Interface em várias etapas para o usuário selecionar recurso, data e horário.
- **Feedback Visual**: Exibe mensagens visuais sobre o sucesso ou falha das ações do usuário.
- **Persistência de Dados Local**: Salva agendamentos em um arquivo JSON, permitindo o uso sem a necessidade de banco de dados.
- **Painel de Administrador**: Permite ao administrador visualizar e excluir agendamentos.
- **Atualização automática**: Remove agendamentos antigos para manter os dados atualizados.

## Pré-requisitos

1. **Node.js** (para rodar um servidor de desenvolvimento local, caso necessário).
2. Um **editor de código** como VSCode para modificar e testar o código.

## Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/SKbrookk/sistema-agendamento.git
   cd sistema-agendamento
