Planejamento da Primeira Sprint - Sistema de Gestão de Competências
📋 Visão Geral do Projeto
Sistema web para gestão e mapeamento de competências internas que permite às lideranças visualizar, analisar e identificar talentos baseado em competências técnicas e comportamentais.
🎯 Objetivos da Sprint 1

Configuração inicial do ambiente de desenvolvimento
Definição da arquitetura do sistema
Criação das telas principais (mockups/protótipos)
Configuração do banco de dados básico
Setup dos ambientes de deploy

👥 Distribuição de Tarefas por Equipe
🎯 EQUIPE GERENCIAL (Aguinaldo, Carlos, Cleber)
Responsabilidades: Documentação, boards, histórias de usuário, suporte ao time
Tarefas Prioritárias:

Setup do Projeto (Cleber - líder técnico da equipe)

 Configurar GitHub Projects/Issues para gestão de tarefas
 Criar estrutura de branches (main, develop, feature/*)
 Definir padrões de commit e pull requests


Documentação de Requisitos (Todos)

 Mapear personas do sistema (Lideranças, Gestores, RH)
 Criar histórias de usuário detalhadas
 Definir critérios de aceite para cada funcionalidade
 Documentar regras de negócio


Análise e Design (Carlos e Aguinaldo)

 Pesquisar sistemas similares (benchmarking)
 Criar wireframes das telas principais
 Definir fluxos de navegação do usuário
 Criar manual de identidade visual (cores, tipografia)



Entregáveis da Sprint:

Documento de requisitos funcionais
Backlog completo do produto
Wireframes das telas principais
Board do projeto configurado


💻 EQUIPE CÓDIGO (Ed, Pedro)
Responsabilidades: Desenvolvimento front-end e back-end, configuração de deploys
Tarefas Prioritárias:
Setup e Configuração (Pedro)

 Configurar estrutura do projeto React + TypeScript + Tailwind v4
 Setup do Vite com configurações otimizadas
 Configurar ESLint e Prettier
 Setup inicial do deploy na Vercel
 Criar componentes base (Header, Sidebar, Layout)

Back-end Foundation (Ed)

 Inicializar projeto Spring Boot
 Configurar estrutura MVC básica
 Setup do Railway para deploy
 Configurar CORS para comunicação front-end
 Criar endpoints básicos de health check

Desenvolvimento Colaborativo (Ambos)

 Criar sistema de autenticação JWT básico
 Implementar middleware de segurança
 Setup de comunicação API (Axios/Fetch)
 Criar primeiras rotas protegidas

Entregáveis da Sprint:

Ambiente de desenvolvimento configurado
Deploy básico funcionando (front + back)
Autenticação implementada
Estrutura de componentes React


🗄️ EQUIPE BANCO DE DADOS (Kauã, Diego)
Responsabilidades: Modelagem, criação de tabelas, testes, documentação BD
Tarefas Prioritárias:
Modelagem de Dados (Kauã - líder técnico)

 Criar diagrama ER completo
 Definir entidades principais (User, Competencia, Avaliacao, Departamento)
 Mapear relacionamentos entre tabelas
 Criar dicionário de dados
 Definir índices e constraints

Implementação (Diego com suporte do Kauã)

 Criar scripts DDL (Create Tables)
 Implementar relacionamentos e foreign keys
 Criar scripts de dados iniciais (seed)
 Setup de backup e recovery básico
 Documentar estrutura do banco

Testes e Validação (Ambos)

 Criar casos de teste para integridade referencial
 Testar performance de consultas básicas
 Validar estrutura com cenários reais
 Criar scripts de migração

Entregáveis da Sprint:

Diagrama ER completo
Scripts de criação do banco
Dicionário de dados
Dados iniciais para testes


🖥️ Estrutura de Telas Propostas
1. Tela de Login

Formulário simples (email/senha)
Recuperação de senha
Integração com sistema corporativo (futuro)

2. Dashboard Principal

Visão geral de competências da empresa
Gráficos de distribuição por departamento
Indicadores principais (total de colaboradores, competências mapeadas)
Atalhos para funcionalidades principais

3. Mapa de Competências

Grid/lista de todos os colaboradores
Filtros por departamento, competência, nível
Visualização em cards ou tabela
Busca avançada

4. Perfil do Colaborador

Informações pessoais e profissionais
Lista de competências técnicas e comportamentais
Histórico de avaliações
Projetos participantes

5. Gestão de Competências

CRUD de competências (criar, editar, remover)
Categorização (técnica, comportamental, específica)
Níveis de proficiência (iniciante, intermediário, avançado, expert)

6. Avaliações

Formulário de avaliação de competências
Auto-avaliação vs avaliação do gestor
Histórico de avaliações anteriores

7. Relatórios e Analytics

Relatórios por departamento
Identificação de gaps de competência
Sugestões de treinamento
Exportação de dados

8. Configurações/Admin

Gestão de usuários
Configurações do sistema
Backup de dados


🗓️ Cronograma da Sprint (Sugestão: 2 semanas)
Semana 1:

Dias 1-2: Setup inicial, configurações, documentação base
Dias 3-5: Desenvolvimento das fundações (auth, BD, componentes base)

Semana 2:

Dias 1-3: Desenvolvimento das telas principais
Dias 4-5: Testes, deploy, documentação final


🚀 Critérios de Sucesso da Sprint
Must Have:

 Ambientes de desenvolvimento e produção funcionando
 Sistema de autenticação implementado
 Banco de dados modelado e criado
 Pelo menos 2-3 telas funcionais (Login + Dashboard)
 Documentação técnica básica

Nice to Have:

 Tela de mapa de competências básica
 Sistema de busca simples
 Primeiros relatórios
