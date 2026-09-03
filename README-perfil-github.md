# Caio Henrique Lopes da Silva

## Software Engineer / Desenvolvedor de Software

Construo software voltado para resolver problemas reais de negócio: sistemas corporativos internos, integrações de processos, aplicações web modernas e automações de alta eficiência.

---

## Sobre

Minha atuação na **Aviagen América Latina** me colocou em contato direto com a complexidade de sistemas corporativos, integrações de grande porte e fluxos operacionais críticos, tendo o ecossistema **Microsoft Dynamics 365 Finance & Operations** como base dessa rotina.

**É justamente a partir desse contato com a operação** que direciono meu trabalho como desenvolvedor. Mais do que apenas mapear necessidades do negócio, meu foco é transformá-las em software de alto nível — projetando arquiteturas sólidas, construindo APIs, modelando bancos de dados e desenvolvendo aplicações web e automações que resolvem gargalos reais com rigor técnico.

**E para que essas soluções sustentem o dia a dia da empresa com consistência**, aplico em cada projeto um equilíbrio rigoroso entre qualidade de código, segurança, performance e facilidade de manutenção. O objetivo nunca é apenas entregar uma automação pontual, mas engenheirar sistemas confiáveis, limpos de manter e preparados para evoluir continuamente com o negócio.

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
