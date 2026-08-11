# Documento de Requisitos – Portfólio Acadêmico Henrique Ulbricht

## 1. Visão Geral

### Nome do Projeto
Portfólio Acadêmico – Henrique Ulbricht

### Tipo de Aplicação
Website institucional / portfólio acadêmico responsivo.

### Objetivo
Apresentar a trajetória acadêmica, habilidades, tecnologias dominadas, projetos desenvolvidos e evolução educacional do aluno Henrique Ulbricht.

### Público-Alvo
- Recrutadores
- Professores
- Instituições de ensino
- Empresas de tecnologia
- Visitantes interessados em projetos de IA

---

# 2. Escopo do Sistema

O sistema consiste em uma Single Page Application (SPA) estática com navegação por âncoras, efeitos visuais avançados e apresentação de conteúdo acadêmico.

O portal permite:

- Exibir informações pessoais e acadêmicas.
- Apresentar competências técnicas.
- Exibir projetos realizados.
- Demonstrar evolução acadêmica.
- Organizar matérias estudadas.
- Disponibilizar informações institucionais.

---

# 3. Tecnologias Identificadas

## Front-End

- HTML5
- CSS3
- JavaScript Vanilla
- Tailwind CSS
- Google Fonts
- Material Symbols

## Recursos Gráficos

- WebGL
- Canvas
- Glassmorphism
- Neon Effects
- Partículas Animadas
- Typewriter Effect

---

# 4. Estrutura de Navegação

## Menu Principal

### Seções

1. About
2. Studies
3. Skills
4. Projects
5. Timeline
6. Contact (link existente, seção não implementada)

---

# 5. Requisitos Funcionais

## RF001 – Exibir Página Inicial

### Descrição
O sistema deve apresentar uma seção principal contendo informações acadêmicas do aluno.

### Dados Exibidos

- Nome
- Instituição
- Orientador
- Título do portfólio

---

## RF002 – Exibir Texto Dinâmico

### Descrição
O sistema deve exibir um texto digitado automaticamente.

### Conteúdo

"IA Generativa Aplicada à Programação | ChatGPT"

---

## RF003 – Navegação por Âncoras

### Descrição
Permitir navegação suave entre seções da página.

### Destinos

- About
- Studies
- Skills
- Projects
- Timeline

---

## RF004 – Exibir Perfil Técnico

### Descrição
Apresentar resumo profissional e acadêmico.

### Informações

- Desenvolvimento de IA
- Automação
- Chatbots
- Programação estruturada

---

## RF005 – Exibir Indicadores Acadêmicos

### Métricas

- Formação: 48h
- Tecnologias: 10+
- Certificação SENAI

---

## RF006 – Exibir Habilidades Técnicas

### Descrição
Apresentar competências com indicadores percentuais.

### Habilidades

- Python
- Machine Learning
- Deep Learning
- NLP
- Prompt Engineering
- Data Analysis
- GPT
- Whisper
- Blockchain
- Git
- Web Scraping

---

## RF007 – Exibir Nível de Proficiência

### Descrição
Cada habilidade deve possuir uma barra visual de progresso.

### Escala

0% a 100%

---

## RF008 – Exibir Projetos

### Descrição
Apresentar projetos acadêmicos e tecnológicos.

### Quantidade Identificada

6 projetos

---

## RF009 – Exibir Projeto de Visão Computacional

### Nome

Deep Learning Vision System

### Área

Computer Vision

### Objetivo

Reconhecimento e classificação de imagens.

---

## RF010 – Exibir Projeto NLP

### Nome

Natural Language Processor

### Área

Processamento de Linguagem Natural

### Objetivo

Análise e sumarização de textos.

---

## RF011 – Exibir Projeto Fintech

### Nome

Automated Trading Bot

### Área

Mercado Financeiro

### Objetivo

Análise preditiva de tendências.

---

## RF012 – Exibir Projeto Assistente Virtual

### Nome

Smart Home Voice Assistant

### Área

IoT + IA

### Objetivo

Assistente de voz integrado com GPT e Whisper.

---

## RF013 – Exibir Projeto HealthTech

### Nome

Predictive Health Dashboard

### Objetivo

Monitoramento preditivo de métricas de saúde.

---

## RF014 – Exibir Projeto Blockchain

### Nome

Blockchain Identity Verifier

### Objetivo

Validação de identidade utilizando blockchain.

---

## RF015 – Exibir Timeline Acadêmica

### Descrição

Exibir evolução da formação.

### Etapas

- Módulo 1
- Módulo 2
- Módulo 3
- Conclusão

---

## RF016 – Exibir Matérias Estudadas

### Disciplinas

- Machine Learning
- Prompt Engineering
- Python Development

---

## RF017 – Exibir Status das Disciplinas

### Status Possíveis

- Ativo
- Concluído

---

## RF018 – Exibir Rodapé

### Informações

- Nome do aluno
- Copyright
- Política de Privacidade
- Termos de Serviço

---

# 6. Requisitos Não Funcionais

## RNF001 – Responsividade

O sistema deve funcionar em:

- Desktop
- Tablet
- Smartphone

---

## RNF002 – Performance

As animações devem executar sem degradação perceptível.

---

## RNF003 – Compatibilidade

Compatível com navegadores modernos:

- Chrome
- Edge
- Firefox
- Safari

---

## RNF004 – Experiência Visual

Utilizar:

- Glassmorphism
- Neon Glow
- Blur Effects
- WebGL

---

## RNF005 – Navegação Fluida

A navegação deve utilizar scroll suave.

---

## RNF006 – Acessibilidade Básica

Os elementos devem possuir contraste adequado e estrutura semântica.

---

# 7. Componentes Identificados

## Navbar

Responsável por:

- Navegação
- Acesso rápido às seções
- Botão Hire Me

---

## Hero Section

Responsável por:

- Apresentação principal
- Chamada visual
- CTA

---

## About Section

Responsável por:

- Perfil técnico
- Indicadores acadêmicos

---

## Skills Section

Responsável por:

- Exibição de competências
- Barras de progresso

---

## Projects Section

Responsável por:

- Catálogo de projetos
- Classificação por categoria

---

## Timeline Section

Responsável por:

- Evolução acadêmica
- Marcos educacionais

---

## Studies Section

Responsável por:

- Exibição das disciplinas

---

## Footer

Responsável por:

- Informações institucionais
- Links legais

---

# 8. Classes de Domínio Identificadas

## Classe Portfolio

### Responsabilidades

- Centralizar informações acadêmicas
- Gerenciar conteúdo exibido

### Atributos

- nome
- instituicao
- orientador
- descricao

---

## Classe Habilidade

### Atributos

- id
- nome
- percentual
- categoria

### Métodos

- obterNivel()
- renderizarBarra()

---

## Classe Projeto

### Atributos

- id
- nome
- categoria
- descricao

### Métodos

- exibirProjeto()

---

## Classe Materia

### Atributos

- id
- nome
- descricao
- status

### Métodos

- obterStatus()

---

## Classe TimelineItem

### Atributos

- modulo
- titulo
- descricao

### Métodos

- renderizarMarco()

---

## Classe Certificacao

### Atributos

- nome
- cargaHoraria
- instituicao

---

# 9. Classes Técnicas Identificadas

## ShaderBackground

### Responsabilidades

- Gerenciar WebGL
- Renderizar fundo animado

### Métodos

- syncSize()
- render()

---

## TypewriterEffect

### Responsabilidades

- Simular digitação

### Métodos

- type()

---

## RevealAnimation

### Responsabilidades

- Animar elementos no scroll

### Métodos

- reveal()

---

## ParticleSystem

### Responsabilidades

- Criar partículas visuais

### Métodos

- createParticle()

---

# 10. Regras de Negócio

## RN001

Toda habilidade deve possuir percentual de proficiência.

---

## RN002

Todo projeto deve possuir categoria.

---

## RN003

Toda matéria deve possuir status.

---

## RN004

A timeline deve seguir ordem cronológica.

---

## RN005

O portfólio deve destacar competências em Inteligência Artificial.

---

# 11. Fluxo Principal

## Fluxo de Navegação

1. Usuário acessa o site.
2. Visualiza apresentação inicial.
3. Navega pelo menu.
4. Consulta perfil técnico.
5. Analisa habilidades.
6. Visualiza projetos.
7. Consulta timeline acadêmica.
8. Consulta disciplinas estudadas.
9. Finaliza navegação no rodapé.

---

# 12. Integrações Identificadas

## Tailwind CDN

Responsável pelo framework visual.

## Google Fonts

Responsável pelas fontes.

## Material Symbols

Responsável pelos ícones.

## WebGL

Responsável pelo shader animado.

---

# 13. Melhorias Futuras Recomendadas

## Funcionais

- Formulário de contato.
- Download de currículo.
- Galeria de certificados.
- Integração GitHub.
- Integração LinkedIn.
- Área administrativa.

## Técnicas

- Migração para React.
- API de conteúdo.
- CMS para gerenciamento.
- Analytics.
- SEO avançado.

---

# 14. Conclusão

O projeto é um portfólio acadêmico de página única focado na apresentação de competências em Inteligência Artificial, Machine Learning, automação e desenvolvimento Python. A solução possui forte apelo visual, navegação responsiva e estrutura modular baseada em componentes de apresentação, habilidades, projetos, disciplinas e evolução acadêmica.