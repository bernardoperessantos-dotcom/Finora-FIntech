<div align="center">

<img src="assets/images/logo.svg" alt="Finora" width="180" />

<br />

# Finora — Dashboard Financeiro

**Interface de gestão financeira pessoal desenvolvida com HTML5, CSS3 e Tailwind CSS**

<br />

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/CSS)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com)
[![Poppins](https://img.shields.io/badge/Fonte-Poppins-4285F4?style=for-the-badge&logo=google-fonts&logoColor=white)](https://fonts.google.com/specimen/Poppins)

</div>

---

## Sobre o Projeto

A **Finora** é uma fintech fictícia de gestão financeira pessoal. O projeto consiste em um dashboard que reúne, em uma única tela, os principais indicadores financeiros do usuário — saldo, receitas, despesas, investimentos, histórico de transações e metas.

A interface foi desenvolvida como projeto acadêmico na **FIAP**, com foco em demonstrar a aplicação de HTML5 semântico, CSS3 e boas práticas de desenvolvimento Front-End, priorizando usabilidade, hierarquia visual e experiência do usuário.

---

## Funcionalidades

- **Indicadores financeiros** — cards de saldo, receitas, despesas e carteira de investimentos com variação percentual
- **Histórico de transações** — tabela com data, categoria, descrição e valor das últimas movimentações
- **Metas financeiras** — progresso visual de objetivos como reserva de emergência, veículo e viagem
- **Cartão virtual** — visualização do cartão Finora Platinum Black com barra de limite utilizado
- **Ações rápidas** — atalhos para transferência, depósito, Pix, pagamento, investimento e cashback
- **Carteira de investimentos** — distribuição por classe de ativo com barras de alocação
- **Navegação lateral** — menu fixo com Dashboard, Transações, Investimentos, Cartões, Metas, Perfil e Configurações

---

## Tecnologias

| Tecnologia | Uso |
|---|---|
| HTML5 | Estrutura semântica (`main`, `aside`, `nav`, `article`, `section`) |
| CSS3 | Design tokens, animações, shimmer, responsividade complementar |
| Tailwind CSS v3 | Layout, espaçamento, tipografia, cores, sombras e responsividade |
| Poppins (Google Fonts) | Tipografia principal — pesos 300 a 800 |
| SVG | Ícones e imagens vetoriais locais sem dependências externas |

O projeto não utiliza JavaScript e não requer build ou instalação de dependências.

---

## Estrutura

```
fintech-fiap/
├── index.html
├── style.css
├── README.md
└── assets/
    ├── images/
    │   ├── avatar.svg
    │   └── logo.svg
    └── icons/
```

---

## Como Executar

1. Faça o download ou clone do repositório.
2. Abra o arquivo index.html em qualquer navegador moderno.

Não há dependências, servidor ou build necessários.

---

## Responsividade

Desenvolvido com a abordagem **Mobile First** — o layout parte da menor tela e é progressivamente adaptado via breakpoints do Tailwind.

| Breakpoint | Largura | Comportamento |
|---|---|---|
| Base | 360px+ | Topbar mobile, coluna única |
| `sm` | 640px+ | Grade de 2 colunas nos cards |
| `md` | 768px+ | Layout de 2 colunas nas seções secundárias |
| `lg` | 1024px+ | Sidebar lateral fixa, grade de 3 colunas |
| `xl` | 1280px+ | Grade de 4 colunas nos KPIs, layout completo |

---

## Acessibilidade

- Estrutura semântica com roles ARIA (`navigation`, `main`, `banner`, `contentinfo`)
- `aria-label` em todos os elementos interativos
- `aria-current="page"` no item ativo da navegação
- `role="progressbar"` com `aria-valuenow` nas barras de progresso
- `aria-hidden="true"` nos elementos decorativos
- Suporte a navegação por teclado com `:focus-visible`
- Compatível com `prefers-reduced-motion` — animações desativadas quando necessário

---

## Versionamento

O desenvolvimento foi controlado por meio do **Git** e hospedado no **GitHub**.

Fluxo utilizado:

```bash
git init
git add .
git commit -m "Estrutura inicial do projeto"
git commit -m "Desenvolvimento do dashboard financeiro"
git commit -m "Implementação da responsividade"
git commit -m "Ajustes finais e documentação"
git push
```

---

## Autor

**Bernardo Peres Santos**  
Estudante de Analise e desenvolvimento de sistemas — FIAP

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/bernardoperessantos-dotcom?tab=repositories)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bernardo-peres-santos-ab2504258?utm_source=share_via&utm_content=profile&utm_medium=member_ios)

---

<sub>© Finora · Projeto acadêmico FIAP</sub>
