# 📖 365 Dias com a Palavra - PIB Penha

Este é um Web App leve e intuitivo desenvolvido para auxiliar os membros da **Primeira Igreja Batista na Penha** (e qualquer cristão) a seguirem um plano de leitura bíblica anual. O projeto foca em acessibilidade, sendo fácil de usar por pessoas de todas as idades, especialmente em dispositivos móveis.

---

## 🚀 Funcionalidades

* **Cálculo Automático:** Identifica o dia atual do ano e exibe a leitura correspondente automaticamente.
* **Navegação Flexível:**
    * **Anterior/Próximo:** Permite folhear os dias da jornada.
    * **Hoje:** Retorna instantaneamente à leitura da data atual.
    * **Início:** Atalho para o Dia 1 da jornada (Gênesis), ideal para quem está começando agora.
* **Busca por Calendário:** Seletor de data integrado com ícone visual, permitindo consultar a leitura de qualquer dia específico do ano.
* **Barra de Progresso:** Exibição visual do avanço anual na leitura da Bíblia.
* **Integração com Bíblia Online:** Link direto para a versão **NVI (Nova Versão Internacional)** no YouVersion, abrindo exatamente no capítulo correto.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5 & CSS3:** Design moderno, responsivo (Mobile-First) e focado em legibilidade.
* **JavaScript (Vanilla):** Lógica personalizada para cálculo de capítulos, manipulação de datas e correção de fuso horário, sem dependências externas.
* **Google Fonts:** Utilização da família *Poppins* para uma interface limpa e amigável.

---

## 📐 Lógica de Leitura

O sistema distribui os **1.189 capítulos** da Bíblia ao longo dos **365 dias** do ano.
* A média é de aproximadamente **3,25 capítulos por dia**.
* A lógica garante que no **Dia 365** a leitura se encerre exatamente no último capítulo de **Apocalipse**.
* O algoritmo identifica automaticamente os intervalos de livros e capítulos, mesmo quando a leitura de um dia abrange mais de um livro bíblico.

---

## 📦 Como Instalar e Atualizar

### Pré-requisitos
* Um servidor de hospedagem estática (recomendado: **Netlify**, **GitHub Pages** ou **Vercel**).
* Estrutura de pastas para a logo da igreja:
    ```text
    /
    ├── index.html
    └── assets/
        └── pibpenha/
            └── images/
                └── logo.webp
    ```

### Implantação
1.  Faça o upload do arquivo `index.html` e da pasta `assets` para o seu provedor.
2.  O site estará disponível instantaneamente via URL.

---

## 📄 Licença

Este projeto é de uso livre para igrejas e comunidades cristãs que desejam incentivar a leitura da Palavra de Deus.

---
> "Lâmpada para os meus pés é tua palavra e luz para o meu caminho." — **Salmos 119:105**