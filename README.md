# Site Institucional - Ice Dream Produções

Este repositório contém o código-fonte do site institucional da **Ice Dream Produções**, empresa especializada em pistas de gelo real, patinação, hockey, curling e SlideCurl para eventos.

## 🔗 Site Live
[icedream-producoes.com.br](https://icedream-producoes.com.br/) 

---

## ✨ Destaques do Projeto

- ✅ **Acessibilidade 10/10** - Desenvolvido seguindo boas práticas WCAG 2.1
- ✅ **100% responsivo** - Funciona em dispositivos móveis, tablets e desktops
- ✅ **SEO otimizado** - Meta tags, palavras-chave e estrutura semântica
- ✅ **Design original** - Mantido integralmente, sem alterações visuais
- ✅ **Formulário funcional** - Integração com EmailJS (com whitelist de domínio)

---

## ♿ Acessibilidade (A11y)

O principal diferencial deste projeto foi o cuidado com a acessibilidade.

### Implementações realizadas:

| Recurso | Descrição |
|---------|-----------|
| **Navegação por teclado** | Via `Tab`, `Enter` e `Space` |
| **Leitores de tela** | Atributos `aria-*`, hierarquia correta de títulos, HTML semântico |
| **Contraste de cores** | Níveis WCAG AA (e superiores) |
| **Texto alternativo** | Todas as imagens com `alt` descritivo |
| **Skip to content** | Link para pular navegação |
| **Foco visível** | Indicadores claros para navegação por teclado |
| **Formulário acessível** | Labels associadas, `aria-required`, `aria-live` para mensagens |

### Ferramentas de validação:
- Lighthouse (Chrome DevTools) - pontuação 100/100 em acessibilidade
- WAVE Evaluation Tool
- Testes manuais com leitores de tela (NVDA, VoiceOver)

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Finalidade |
|------------|------------|
| HTML5 | Estrutura semântica |
| CSS3 | Estilização (design original mantido) |
| EmailJS | Envio de formulário de contato |
| GitHub Pages | Hospedagem |

---

## 🚀 Como Executar Localmente

```bash
# Clone o repositório
git clone https://github.com/teixeira-pri/teixeira-pri.github.io.git

# Acesse a pasta
cd teixeira-pri.github.io

# Abra o arquivo principal (clique duas vezes ou use um servidor local)
# Opção com servidor local (recomendado para testes):
npx serve .
