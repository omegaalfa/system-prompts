# ⚡ Bolt - Assistente de Desenvolvimento Web

<div align="center">
  <img src="https://img.shields.io/badge/Bolt-AI-yellow?style=for-the-badge&logo=bolt" alt="Bolt AI"/>
  <img src="https://img.shields.io/badge/WebContainer-black?style=for-the-badge&logo=web" alt="WebContainer"/>
  <img src="https://img.shields.io/badge/Supabase-green?style=for-the-badge&logo=supabase" alt="Supabase"/>
</div>

## 📋 Visão Geral

**Bolt** é um assistente de IA especialista em desenvolvimento de software que opera em um ambiente **WebContainer** - um runtime Node.js in-browser que emula um sistema Linux. Especializado em desenvolvimento web moderno, com ênfase em projetos que utilizam **Supabase** como banco de dados e frameworks JavaScript modernos.

## 🎯 Características Principais

### 🌐 Ambiente WebContainer
- **Runtime In-Browser**: Execução de código JavaScript no navegador
- **Emulação Linux**: Ambiente shell que simula sistema Linux
- **Sem Binários Nativos**: Restrições específicas do ambiente navegador
- **Node.js Nativo**: Suporte completo ao ecossistema Node.js

### 🗄️ Especialização em Supabase
- **Banco de Dados Padrão**: Preferência por Supabase em projetos
- **Migrações Seguras**: Sistema de migrações com integridade de dados
- **Segurança RLS**: Row Level Security habilitada por padrão
- **Queries Otimizadas**: Execução imediata e migrações estruturadas

### 🛠️ Capacidades de Desenvolvimento
- **JavaScript/TypeScript**: Desenvolvimento full-stack
- **Frameworks Modernos**: React, Vue, Next.js, Vite
- **APIs RESTful**: Construção de serviços web
- **Scripting Node.js**: Preferência sobre scripts shell

## 📁 Conteúdo do Diretório

### 📋 Prompt.txt (466 linhas)
Prompt completo do assistente Bolt incluindo:
- **Restrições do Sistema**: Limitações do WebContainer
- **Instruções de Banco de Dados**: Uso correto do Supabase
- **Diretrizes de Desenvolvimento**: Melhores práticas
- **Comandos Disponíveis**: Ferramentas do ambiente

## 🏗️ Arquitetura Técnica

### 🌐 WebContainer Environment
#### Limitações Críticas
- **Sem Binários Nativos**: Não executa código compilado C/C++
- **Python Limitado**: Apenas biblioteca padrão, sem pip
- **Sem Git**: Controle de versão não disponível
- **Sem Diff/Patch**: Atualizações completas de arquivos

#### Capacidades Disponíveis
- **Node.js Completo**: Ecossistema npm disponível
- **Shell Emulado**: Comandos zsh-like disponíveis
- **Servidores Web**: Vite, servor, http-server
- **Bancos de Dados**: Supabase, libsql, sqlite

### 🗄️ Sistema de Banco de Dados
#### Migrações Supabase
- **Arquivos Separados**: Uma migração por arquivo
- **Execução Imediata**: Queries diretas para testes
- **Segurança Integrada**: RLS habilitado automaticamente
- **Políticas CRUD**: Controle de acesso granular

#### Estrutura de Dados
- **UUIDs Automáticos**: Chaves primárias padronizadas
- **Valores Padrão**: Consistência de dados garantida
- **Relacionamentos**: Estrutura relacional adequada
- **Índices Otimizados**: Performance de queries

## 🎨 Metodologia de Desenvolvimento

### 📊 Abordagem de Projeto
1. **Planejamento Arquitetural**: Estruturação do projeto
2. **Configuração Supabase**: Setup do banco de dados
3. **Desenvolvimento Frontend**: Interfaces React/Vue
4. **Integração Backend**: APIs e lógica de negócio
5. **Testes e Validação**: Verificação de funcionalidade

### 🔒 Segurança e Integridade
- **Preservação de Dados**: Nunca operações destrutivas
- **Transações Seguras**: Controle adequado de estado
- **Validação de Input**: Sanitização de dados
- **Autenticação**: Controle de acesso adequado

## 🔧 Tecnologias Suportadas

### 🎯 Frameworks Frontend
- ✅ **React**: Componentes modernos
- ✅ **Vue.js**: Framework progressivo
- ✅ **Next.js**: SSR e SSG
- ✅ **Vite**: Build tool otimizado

### 🗄️ Bancos de Dados
- ✅ **Supabase**: Plataforma completa
- ✅ **SQLite**: Banco local
- ✅ **LibSQL**: Alternativa moderna
- ✅ **PostgreSQL**: Via Supabase

### 🛠️ Ferramentas de Build
- ✅ **Vite**: Desenvolvimento rápido
- ✅ **ESLint**: Qualidade de código
- ✅ **Prettier**: Formatação automática
- ✅ **TypeScript**: Tipagem estática

## 📊 Compatibilidade

- ✅ **Navegadores Modernos**: Chrome, Firefox, Safari, Edge
- ✅ **Node.js**: Ecossistema completo
- ✅ **APIs Web**: Fetch, WebSockets, Service Workers
- ✅ **WebAssembly**: Quando necessário
- ✅ **PWA**: Progressive Web Apps

## 🔧 Configuração Recomendada

```json
{
  "environment": "webcontainer",
  "database": "supabase",
  "framework": "react_vite",
  "language": "typescript",
  "build_tool": "vite",
  "deployment": "webcontainer_native"
}
```

## 📝 Notas Importantes

- **Ambiente Browser**: Todas as limitações do WebContainer
- **Supabase First**: Preferência por soluções Supabase
- **Node.js Prioritário**: Scripts em Node.js sobre shell
- **Migrações Seguras**: Integridade de dados é prioridade
- **Sem Binários**: Restrições de execução nativa

---

<div align="center">
  <p><strong>⚡ Desenvolvimento Web no Navegador</strong></p>
  <p>WebContainer • Supabase • JavaScript Moderno</p>
  <p><em>In-Browser Development • Database-First • Secure by Design</em></p>
</div></content>