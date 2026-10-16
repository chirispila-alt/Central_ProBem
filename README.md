# Documentação e Apresentação do Projeto "Central de Informações do Beneficiário"
---

## 📋 Projeto

O repositorio tem o desenvolvimento frontend para o conceito visual sobre a reformulação da pagina da Central do Beneficiario. Projeto que foi estruturado em busca de diminuir o gargalo operacional: a fragmentação de cadastros e senhas por periodos que o beneficiario tem a bolsa, oferecendo a unificação das informações em somente um acesso.

---

## ⚠️ O Problema Identificado

No modelo tradicional, sempre que o estudante renova a bolsa (ex.: *2025-1, 2025-2, 2026-1*), um novo cadastro fragmentado é gerado para o mesmo CPF. Isso gera:

* Múltiplas credenciais e senhas fragmentadas para o mesmo usuário.
* Histórico de participações e benefícios espalhados.
* Sobrecarga nos canais de suporte técnico com chamados de recuperação de acesso.
* Necessidade de troca constante de contas.

---

## 💡 A Solução Proposta

1. **Acesso Único por CPF:** Unificação das credenciais para que o beneficiário possua apenas um login no portal.
2. **Aba "Bolsas" com Seletor Histórico:** Um painel onde o usuário escolhe o período desejado (ex: semestres anteriores e vigentes) para consultar dados, status e requerimentos.
3. **Assistente Virtual (Chatbot Contextual):** Integração planejada de um assistente inteligente focado estritamente nos dados da sessão autenticada do usuário, respondendo dúvidas sobre a ficha e indicando oportunidades em tempo real com total privacidade.
4. **Modernização do Frontend:** Interface totalmente reestilizada em componentes limpos e responsivos (cards organizados, janelas modais interativas para detalhes de vagas de estágio com integração CIEE, e filtros de busca em tempo real) alinhados à identidade visual institucional.

---

## 🛠️ Tecnologias Utilizadas
* **HTML5** & **CSS3** (Layout responsivo com Flexbox, Grid e design system próprio)
* **JavaScript (Vanilla / ES6+)** (Manipulação de DOM, modais dinâmicos e filtros de busca)
* **Git & GitHub** (Controle de versão e publicação via GitHub Pages)

---

## 📂 Estrutura de Arquivos

├── menu.js               # Componente modularizado do menu lateral
├── style.css             # Folha de estilos principal da aplicação
└── tipografia.css        # Configurações de fontes e variáveis visuais