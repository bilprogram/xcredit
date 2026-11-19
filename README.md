# Guia de Referencia e Estrutura — Projeto Xcredit

Este documento orienta exatamente como o novo site deve ser desenvolvido utilizando as referencias do Design System 1 e do Design System 2, alinhado a marca e conteudo da Xcredit.

---

## 1. Mapeamento de Papeis

1. Referencia Primaria (Estrutural):
   - Arquivo: ../design system 1/design-system1.html
   - Diretriz: Seguir prioritariamente a estrutura, densidade, hero e cartoes de construcao civil e engenharia (iBUILD).

2. Referencia Secundaria (Componentes e Fluxos):
   - Arquivo: ../design system 2/design-system2.html
   - Diretriz: Absorver os padroes de formularios, acordions de FAQ, pilulas de etapas e animacoes sutis (surgir, preencher, data-revelar).

3. Identidade Visual e Cores:
   - Fonte: conteudo/copy-diretrizes.md
   - Azul Institucional: #1A2B4C
   - Laranja de Acao / CTA: #F26522
   - Gradiente Oficial: #00B39B a #0085CA (135 graus)

4. Tipografia da Marca:
   - Titulos: Transducer ou Saira
   - Textos: Open Sans ou Inter

5. Conteudo e Copy:
   - Arquivo: conteudo/copy-diretrizes.md
   - Contem textos completos, titulos H1/H2, diferenciais de Steel Frame, Financiamento Caixa Aqui e depoimentos.

6. Logotipos Oficiais:
   - Pasta: assets/marca/
   - Arquivos: Logo_xcredit_correspondente_caixa-removebg-preview.png, Logo_oficial.jpg

7. Imagens de Conteudo:
   - Pasta: assets/imagens/
   - Arquivos: Fotos da Lidiane, congressos LATAM, obras Steel Frame e videos hero.

---

## 2. Organizacao das Pastas do Projeto

Projeto Xcredit/
├── design system 1/              (REFERENCIA 1: iBUILD - Engenharia e Steel Frame)
│   ├── design-system1.html
│   └── assets/
│
├── design system 2/              (REFERENCIA 2: Tristar - UI Components e Interacoes)
│   ├── design-system2.html
│   └── assets/
│
├── referencias-antigas-imagens/  (ISOLADO: Fotos antigas dos dois DS arquivadas)
│   ├── design-system-1/
│   └── design-system-2/
│
└── novo-site/                    (PRODUCAO ATIVA: Onde o novo site e construido)
    ├── README.md
    ├── conteudo/
    │   └── copy-diretrizes.md
    └── assets/
        ├── marca/
        └── imagens/

---

## 3. Regra de Execucao para o Desenvolvedor
1. NAO utilize imagens das referencias antigas no site novo; use exclusivamente as midias da pasta novo-site/assets/.
2. As referencias em design system 1 e design system 2 servem para guiar o codigo HTML/CSS, classes, layout e animacoes.
3. Substitua todas as variaveis de cores pelas cores da Xcredit (#1A2B4C e #F26522).
