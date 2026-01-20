# CPA - Cálculo de Pensão Alimentícia

<div align="center">
<img src="public/img/logo_cpa.svg" width="500">
</div>

### Badges
![Vite](https://img.shields.io/badge/Vite-Fast%20Builds-646CFF?logo=vite&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-Typed%20JS-3178C6?logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-Componentes%20Reativos-61DAFB?logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-Estilização%20Rápida-06B6D4?logo=tailwindcss&logoColor=white)
![shadcn/ui](https://img.shields.io/badge/shadcn%2Fui-UI%20Moderna-8B5CF6?logo=vercel&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-Automação-2088FF?logo=githubactions&logoColor=white)
[![Netlify Status](https://api.netlify.com/api/v1/badges/ee8557bb-5ee7-4bfe-83fe-2aed892ca947/deploy-status)](https://app.netlify.com/projects/cpa-calculopensaoalimenticia/deploys)
[![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-blue)](https://github.com/seu-usuario/seu-repositorio)
[![Licença: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


### Sumário

* [Descrição do Projeto](#descrição-do-projeto)
* [Status do Projeto](#status-do-projeto)
* [Funcionalidades e Demonstração da Aplicação](#funcionalidades-e-demonstração-da-aplicação)
* [Tecnologias Utilizadas](#tecnologias-utilizadas)
* [Como Usar a Aplicação](#como-usar-a-aplicação)
* [Cálculos Implementados](#cálculos-implementados)
* [Equipe do Projeto](#equipe-do-projeto)
* [Conclusão](#conclusão)


## Descrição do Projeto

O **CPA - Cálculo de Pensão Alimentícia** é uma aplicação web intuitiva e poderosa, desenvolvida para simplificar e automatizar o cálculo de valores de pensão alimentícia. É uma ferramenta essencial para **advogados, contadores** e **pessoas físicas** que precisam determinar valores precisos, incluindo juros, correção monetária, multas e honorários advocatícios, tudo em conformidade com a legislação brasileira vigente.

Nosso sistema foi criado para eliminar a complexidade dos cálculos retroativos de pensão alimentícia, aplicando automaticamente os índices de correção monetária, taxas de juros legais e considerando os valores do salário mínimo de cada período.

### Status do Projeto

O projeto **CPA - Cálculo de Pensão Alimentícia** está atualmente em fase de **desenvolvimento ativo**. As funcionalidades principais já foram implementadas e estão em fase de testes rigorosos para garantir a precisão. Novas funcionalidades são adicionadas regularmente, buscando sempre aprimorar a experiência do usuário e a exatidão dos cálculos.


## Funcionalidades e Demonstração da Aplicação

### Principais Funcionalidades

1.  **Cálculo de Pensão Alimentícia:**
    * **Base no Salário Mínimo:** Permite calcular valores com base em um percentual do salário mínimo vigente em cada período.
    * **Base na Remuneração:** Suporte para cálculos baseados na remuneração do alimentante, caso possua vínculo empregatício.
2.  **Período de Cálculo Customizado:**
    * **Flexibilidade:** Definição clara do período inicial e final para os cálculos.
    * **13º Salário:** Opção para incluir ou não o 13º salário nos cálculos.
3.  **Juros e Correção Monetária:**
    * **Juros de Mora:** Aplicação automática de juros de 1% ao mês, conforme o Código Civil.
    * **Correção Monetária:** Correção aplicada de acordo com os índices oficiais (Lei 6.899/81).
    * **Precisão:** Contagem exata dos dias em atraso, excluindo o dia corrente.
4.  **Multas e Honorários:**
    * **Multa:** Opção para incluir multa de 10% (Art. 523, §1º do CPC).
    * **Honorários:** Cálculo de honorários advocatícios de 10%, conforme a legislação.
5.  **Exportação e Impressão:**
    * **Exportação:** Exporte os resultados detalhados para o Excel para análise posterior.
    * **Impressão:** Imprima os cálculos em formato PDF para documentação.
    * **Visualização:** Tenha uma visualização detalhada dos valores calculados mês a mês.
6.  **Interface Intuitiva:**
    * **Responsividade:** Design adaptável para uso em dispositivos móveis e desktops.
    * **Formulário:** Formulário de fácil preenchimento com instruções claras.
    * **Resultados:** Tabela de resultados detalhada e de fácil compreensão.

### Como os Cálculos são Realizados

A aplicação segue um fluxo lógico e preciso para calcular os valores da pensão alimentícia:

1.  **Salário Mínimo:** Determina o valor do salário mínimo vigente em cada mês do período selecionado.
2.  **Aplicação do Percentual/Remuneração:** Aplica o percentual de pensão definido sobre o salário mínimo ou a remuneração informada.
3.  **Dias em Atraso:** Calcula os dias em atraso para cada mês (do dia de vencimento até a data atual do cálculo).
4.  **Juros de Mora:** Aplica juros de mora de 1% ao mês sobre os valores em atraso, proporcionalmente aos dias.
5.  **Correção Monetária:** Aplica a correção monetária utilizando os índices oficiais para atualizar os valores.
6.  **Multa e Honorários:** Adiciona multa e honorários advocatícios, se essas opções forem selecionadas.
7.  **Totalização:** Apresenta os valores totalizados e detalhados para cada período.

## Tecnologias Utilizadas

Este projeto foi construído com as seguintes tecnologias de ponta, garantindo performance e uma ótima experiência de usuário:

* **React**: Um framework JavaScript robusto para construção da interface de usuário reativa e eficiente.
* **TypeScript**: Uma linguagem de programação que adiciona tipagem estática ao JavaScript, aumentando a segurança e a manutenibilidade do código.
* **Tailwind CSS**: Um framework CSS utilitário que permite estilização rápida e responsiva, focando na performance.
* **shadcn/ui**: Uma coleção de componentes de UI (User Interface) reutilizáveis e acessíveis, que aceleram o desenvolvimento e garantem um design moderno.
* **date-fns**: Uma biblioteca leve e modular para manipulação de datas, facilitando cálculos e formatações.
* **xlsx**: Uma biblioteca poderosa para exportação de dados, permitindo gerar planilhas Excel com facilidade.
* **Vite**: Uma ferramenta de build extremamente rápida que otimiza o ambiente de desenvolvimento e a compilação do projeto.

## Como Usar a Aplicação

Para utilizar a calculadora de pensão alimentícia, siga estes passos simples:

1.  **Preencha o Número do Processo (Opcional):** Você pode inserir o número do processo para sua organização.
2.  **Informe o Vínculo Empregatício:**
    * Se o alimentante **possui vínculo empregatício**, informe o valor de sua remuneração.
    * Caso **não possua vínculo**, o cálculo será baseado no salário mínimo.
3.  **Defina o Percentual da Pensão:** Informe o percentual da pensão a ser aplicado (ex: 30%).
4.  **Incluir 13º Salário:** Selecione se deseja incluir o 13º salário no cálculo.
5.  **Defina o Período:** Escolha a data inicial e final para o cálculo da pensão.
6.  **Multa e Honorários:** Marque as opções se desejar aplicar multa e honorários advocatícios.
7.  **Calcular:** Clique no botão "Calcular" para visualizar os resultados detalhados.
8.  **Exportar/Imprimir:** Utilize os botões para exportar os resultados para o Excel ou imprimir em formato PDF.


## Cálculos Implementados

Nossa aplicação baseia seus cálculos em referências legais e oficiais para garantir a máxima precisão:

### Salário Mínimo

A aplicação mantém uma base de dados interna com os valores históricos do salário mínimo brasileiro. Estes valores são fundamentais para os cálculos que são baseados em um percentual do salário mínimo.

### Juros de Mora

Os juros de mora são calculados à taxa de **1% ao mês**, proporcionalmente aos dias em atraso. Este cálculo segue o que está estabelecido no **Art. 406 do Código Civil (Lei 10.406/2002)**, em conjunto com o **Art. 161, § 1º, do Código Tributário Nacional (Lei 5.172/1966)**.

### Correção Monetária

A correção monetária é aplicada utilizando os **índices de correção oficiais**, conforme determinado pela **Lei 6.899/81**. Isso assegura que os valores sejam atualizados de acordo com a desvalorização da moeda ao longo do tempo, mantendo seu poder de compra.

### Multa e Honorários

Quando selecionados pelo usuário, a multa e os honorários são aplicados conforme o **Art. 523, §1º do Código de Processo Civil (Lei 13.105/2015)**. Este artigo estabelece uma **multa de 10%** e **honorários advocatícios de 10%** para o cumprimento de sentença.


## Equipe do Projeto

Gostaríamos de agradecer a todos que contribuem para este projeto:

<a href="https://github.com/amaro-netto" title="Amaro Netto"><img width="180" src="https://github.com/user-attachments/assets/19f46efc-57ff-4a4b-ac19-11da9e2d59c9"/></a> <a href="https://www.instagram.com/isabelamattos.adv/" title="Isabela Mattos Advogada"><img width="180" src="https://github.com/user-attachments/assets/8f752358-75a7-429d-8319-7afbffa8a2cd"/></a>

## Conclusão

O **CPA - Cálculo de Pensão Alimentícia** foi desenvolvido com o propósito de **facilitar e automatizar** os complexos cálculos envolvidos em processos de pensão alimentícia. Nosso objetivo é proporcionar **economia de tempo** e **maior precisão** para profissionais e cidadãos. A aplicação está em **constante evolução** para se adaptar às necessidades dos usuários e às mudanças na legislação brasileira.

> [!IMPORTANT]
> **Aviso Legal**: Esta ferramenta foi desenvolvida exclusivamente para **fins informativos**. Ela não substitui a orientação jurídica profissional e não deve ser utilizada como única base para decisões legais. Os cálculos são baseados na legislação vigente e nos dados fornecidos pelo usuário, podendo haver variações de acordo com interpretações judiciais específicas ou particularidades de cada caso. Sempre consulte um profissional do direito.

## Prévia do Projeto:

[Acesse o site](https://cpa-calculopensaoalimenticia.netlify.app/)

### Screenshot
<img src="https://github.com/user-attachments/assets/14492323-5727-4ed3-ba15-0095ca9a2443" height="500"> <img src="https://github.com/user-attachments/assets/cc158a0e-c7ae-4a87-832b-21f479003e1f" height="500">




