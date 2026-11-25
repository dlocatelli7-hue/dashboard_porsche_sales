#  Dashboard Interativa de Vendas - Porsche

Projeto desenvolvido como desafio prático do curso **Criando uma Dashboard da Porsche com Agentes de IA** (DIO), ministrado pelo expert Felipe Aguiar (Felipão). O objetivo é transformar uma base de dados sanitizada de 100 vendas da Porsche em uma aplicação web interativa (arquivo único `index.html`), publicada via GitHub Pages.

**Acesse a Dashboard Online:**

[Acessar Página 1 ChatGPT com recurso Canvas ](https://dlocatelli7-hue.github.io/dashboard_porsche_sales/)

- [Acessar Página 2 ( Agente personalizado com Skill de Dashboard)](https://dlocatelli7-hue.github.io/dashboard_porsche_sales/projeto2/)

---

## 🎯 Perguntas de Negócio Escolhidas

Para evitar um amontoado de gráficos sem propósito, a dashboard foi construída para responder a **3 perguntas de negócio estratégicas**:

1. **[Ex: Qual modelo da Porsche gera o maior faturamento total versus o maior volume de unidades vendidas?]**
   * **Por quê:** Permite identificar a diferença entre carros de entrada/alto giro (como Macan ou Cayenne) e modelos de ticket médio ultra-alto (como o 911), orientando o foco comercial.
2. **[Ex: Como as vendas e o faturamento se distribuem geograficamente entre as principais cidades/estados?]**
   * **Por quê:** Ajuda a mapear onde está concentrada a demanda de luxo para direcionar campanhas regionais e estoque das concessionárias.
3. **[Ex: Qual é a preferência dos clientes em relação aos métodos de pagamento e como o volume evoluiu por ano?]**
   * **Por quê:** Revela o perfil financeiro do comprador (à vista vs. financiamento/consórcio) e a sazonalidade das vendas ao longo dos anos.

---

## 🧹 Tratamento e Preparação da Base de Dados

Antes de enviar os dados para a Inteligência Artificial gerar o código, a planilha passou pelas seguintes etapas de higienização:

* **Seleção de Colunas:** Remoção das colunas com dados crus/sujos, mantendo exclusivamente as colunas já sanitizadas (`Modelo`, `Cidade`, `Estado`, `Ano`, `Preço` e `Método de Pagamento`).
* **Tipagem Numérica:** Conversão explícita das colunas de `Preço` e `Ano` para formato numérico puro (removendo símbolos de moeda como texto que quebrariam somas e médias no JavaScript).
* **Limpeza de Fórmulas e Segurança:** Cópia e colagem apenas como **valores** para eliminar fórmulas residuais e verificação para garantir que nenhum dado sensível (CPF, nome de cliente, etc.) estivesse presente, já que o dataset fica embutido no código-fonte.

---

## 🤖 Fluxo de Criação com IA e Engenharia de Prompt

* **Ferramenta utilizada:** ChatGPT com recurso Canvas / Agente personalizado com Skill de Dashboard / Ambos para comparação].
* **Identidade Visual:** Paleta inspirada na identidade clássica da Porsche (tons de preto/grafite escuro, vermelho corrida, branco e detalhes em cinza metálico) com tipografia moderna e limpa.

