# Site Institucional - Ice Dream Produções

Este repositório contém o código-fonte do site institucional da Ice Dream Produções, empresa especializada em pistas de gelo real, patinação, hockey, curling e SlideCurl para eventos.

🔗 Site Live  
https://icedream-producoes.com.br

---

## ✨ Sobre o Projeto

Este projeto foi desenvolvido com foco em performance, responsividade e, principalmente, **acessibilidade em evolução contínua**.

Durante o desenvolvimento, foram aplicadas boas práticas de acessibilidade mas, ao testar com ferramentas e leitores de tela, ficou claro que ainda há pontos importantes de melhoria.

Ou seja: este não é um projeto “finalizado” em acessibilidade, mas sim um **caso real de aprendizado e evolução prática em A11y**.

---

## ♿ Acessibilidade (A11y)

A acessibilidade foi tratada como parte do processo, não como etapa final.

### ✔️ Implementações já realizadas

- Navegação por teclado (Tab, Enter e Space)
- Estrutura semântica com HTML5
- Uso de atributos `aria-*`
- Hierarquia de títulos organizada
- Textos alternativos em imagens
- Link "skip to content"
- Estados de foco visíveis
- Formulário com labels associadas e feedback acessível
- Contraste de cores próximo aos níveis recomendados WCAG
- Implementação de recurso com suporte em **Libras (assistente visual)**

---

### ⚠️ Pontos em evolução

Testes com ferramentas automatizadas e leitores de tela indicaram que ainda existem melhorias a serem feitas, como:

- Ajustes na experiência com leitores de tela
- Melhorias na navegação não visual
- Refinamento de semântica em alguns componentes
- Otimizações adicionais de contraste e feedbacks dinâmicos

Pontuação atual em ferramenta automatizada:
→ Aproximadamente **5.7 / 10**

---

### 🧪 Testes realizados

- Testes manuais com leitores de tela (NVDA, VoiceOver)
- Avaliação com ferramentas automatizadas
- Navegação apenas por teclado

> Observação: ferramentas automatizadas não substituem testes reais com usuários.

---

## 🛠️ Tecnologias Utilizadas

- HTML5 — Estrutura semântica  
- CSS3 — Estilização (design original mantido)  
- GitHub Pages — Hospedagem  

---

## 🚀 Como Executar Localmente

```bash
# Clone o repositório
git clone https://github.com/teixeira-pri/teixeira-pri.github.io.git

# Acesse a pasta
cd teixeira-pri.github.io

# Execute com servidor local (recomendado)
npx serve .
