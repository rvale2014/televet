# televet
Plataforma para Clínica de Telemedicina Veterinária

## Visão geral
Televet é uma aplicação web para suportar serviços de telemedicina veterinária. O objetivo é permitir consultas remotas, agendamento e gestão básica de pacientes e atendimentos, usando tecnologias modernas de front-end.

## Tecnologias principais
- Framework: Next.js (ver dependência em [package.json](package.json))  
- Biblioteca UI: React / React DOM (ver dependências em [package.json](package.json))  
- Versão Node recomendada: `lts/hydrogen` (definida em [.nvmrc](.nvmrc))

## Status atual
- Estrutura inicial do projeto criada.
- Dependências principais registradas em [package.json](package.json).
- Scripts de desenvolvimento/produção ainda não configurados em [package.json](package.json).

## Como executar (local)
1. Instalar dependências:
   - `npm install`
2. Executar em modo desenvolvimento (exemplo sem script personalizado):
   - `npx next dev`
3. Build e produção:
   - `npx next build`
   - `npx next start`

Recomenda-se adicionar scripts úteis no [package.json](package.json) (por exemplo `dev`, `build`, `start`) para facilitar o fluxo.

## Contribuição
- Abra issues para bugs ou novas funcionalidades.
- Envie pull requests com descrição clara das mudanças.

## Licença
MIT (conforme [package.json](package.json))
