# Caio Henrique Lopes da Silva

## Software Engineer / Desenvolvedor de Software

Crio aplicações web e ferramentas internas que ajudam a organizar processos, automatizar tarefas e conectar sistemas.

---

## Sobre

Na **Aviagen América Latina**, trabalho no dia a dia com sistemas corporativos e áreas operacionais, principalmente no ambiente do **Microsoft Dynamics 365 Finance & Operations**.

Estar próximo da operação me ensinou a olhar primeiro para a necessidade de quem usa a ferramenta antes de pensar no código. Aproveito essa vivência no desenvolvimento para criar soluções práticas: aplicações web, ferramentas internas, APIs e automações que conectam dados e eliminam trabalho manual.

Nos meus projetos, me preocupo em escrever código limpo, organizado e fácil de manter. O objetivo é sempre entregar software útil, seguro e que resolva o problema de verdade, sem complicar o que pode ser simples.

---

## Projetos Selecionados

### 01. AnáliseIA — Otimização de Inferência de Vídeo
Aplicação de visão computacional para análise automatizada de vídeos. O desafio foi portar o processamento (originalmente desenvolvido para Linux com GPU NVIDIA) para rodar com alto desempenho nas estações Windows da empresa com GPU dedicada Intel Arc.

Com Python e o toolkit OpenVINO, reestruturei o pipeline de inferência com aceleração direta em hardware: o tempo para processar cada bloco de vídeo caiu de **~50 minutos para cerca de 1 minuto** (-98%), viabilizando o uso contínuo na rotina de inspeção operacional.

`Python` · `OpenVINO` · `Intel Arc` · `Visão Computacional` · `Otimização de Hardware`  
*Uso corporativo interno.*

---

### 02. Sistema de Inventário de TI
Criado para substituir o controle de máquinas e equipamentos em planilhas soltas, reunindo cadastro patrimonial, alocação de ativos e cálculo de depreciação para planejamento de compra de novos aparelhos.

Para rodar sem custos adicionais de servidores de banco de dados, desenvolvi a aplicação em arquitetura local-first com a **File System Access API**, tratando concorrência entre múltiplos operadores na mesma rede interna. Também integrei a **Adobe Sign API** para gerar e recolher termos de entrega assinados digitalmente.

`JavaScript` · `File System Access API` · `Adobe Sign API` · `Local-First` · `Multiusuário`  
*Uso corporativo interno.*

---

### 03. Gestão de Faturas por Filial
Centraliza a esteira de faturas que chegam das filiais operacionais antes de irem para o setor fiscal, reduzindo o tempo de conferência e eliminando cobranças manuais por e-mail.

A ferramenta permite importar lotes de faturas via planilha, gera mensagens automáticas de conciliação fiscal e opera com leitura e gravação cooperativa em arquivos de rede compartilhada, permitindo que vários usuários trabalhem simultaneamente sem corromper dados.

`JavaScript` · `File System Access API` · `Importação de Planilhas` · `Rotinas Fiscais`  
*Uso corporativo interno.*

---

### 04. GerenteEvent
Plataforma SaaS multi-tenant que substitui o controle manual de eventos corporativos por um fluxo completo: convites por e-mail com token único, credenciamento na portaria via leitor de QR Code, emissão automática de certificados em PDF e métricas de adesão em tempo real.

Construído com **React 19, Vite e Tailwind CSS** no frontend, com backend no **Supabase** (PostgreSQL com RLS para isolamento de dados por workspace e Edge Functions serverless para envios transacionais de e-mail).

`React 19` · `Vite` · `TypeScript` · `Supabase/PostgreSQL` · `Edge Functions` · `Tailwind CSS`  
*Deploy pausado · Repositório privado*

---

### 05. CalculaMeta
Aplicação focada em acompanhamento diário de metas comerciais. Em vez de avaliar o resultado apenas no fim do mês quando não há mais tempo de reação, a ferramenta quebra a meta em ritmo diário (pacing) considerando os dias úteis reais trabalhados.

Desenvolvido com **Next.js 16 (App Router)**, TypeScript e Supabase, utilizando funções RPC para cálculos atômicos de projeção matemática e pipeline de integração contínua no GitHub Actions.

`Next.js 16` · `React 19` · `TypeScript` · `Supabase Postgres` · `Tailwind CSS` · `GitHub Actions`  
[Deploy na Vercel](https://calculametamo.vercel.app) · *Repositório privado*

---

### 06. Automações Corporativas & RPA (Dynamics 365 & Desktop)
Ferramentas práticas desenvolvidas para eliminar tarefas manuais repetitivas e acelerar rotinas de compras e logística:
- **Preenchedor D365 F&O:** aplicação local em Node.js com perfil de navegador dedicado que analisa XMLs de NF-e, preenche requisições de compra no ERP e avança automaticamente o fluxo de aprovação.
- **Gerador de Etiquetas Desktop:** aplicativo em Python (Tkinter + openpyxl) empacotado em `.exe` para mala direta veloz de listas de convidados em modelos Word formatados.

`Python` · `Tkinter` · `openpyxl` · `Node.js` · `Microsoft Dynamics 365 F&O` · `RPA`  
*Uso corporativo interno.*

---

## Base Técnica

- **Linguagens & Fundamentos:** TypeScript, JavaScript (ES6+), Python, SQL, C# / .NET, HTML5, CSS3.
- **Web & Frontend:** React 19, Next.js 16, Vite, Tailwind CSS, Local-First, File System Access API.
- **Backend, Dados & Cloud:** Node.js, Supabase (PostgreSQL, Auth, Storage, Edge Functions), REST APIs, Vercel, GitHub Actions.
- **Sistemas Corporativos & IA:** Microsoft Dynamics 365 Finance & Operations, OpenVINO, Adobe Sign API, RPA & Automações Office, Git.

---

## Experiência Profissional

- **Aviagen América Latina:** Atuação com sistemas corporativos, Microsoft Dynamics 365 F&O, processos de negócio, análise de requisitos com áreas operacionais e fiscais, testes integrados, homologação e desenvolvimento de ferramentas satélites de automação.

---

## Formação Acadêmica

- **Universidade São Francisco (USF):** Bacharelado em Engenharia da Computação.
  - Conclusão prevista para dezembro de 2026.

---

## Contato

- **LinkedIn:** [linkedin.com/in/caiohls](https://linkedin.com/in/caiohls)
- **GitHub:** [github.com/Caiohls](https://github.com/Caiohls)
- **E-mail:** [caiohls2003@gmail.com](mailto:caiohls2003@gmail.com)
