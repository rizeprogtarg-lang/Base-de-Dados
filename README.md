# 📊 Xbox Game Pass - Dashboard de Vendas e Assinaturas

## 📝 Descrição do Projeto
Este repositório contém o **Dashboard de Vendas do Xbox Game Pass**, desenvolvido no Microsoft Excel para a análise estratégica de dados de assinaturas do ano de 2024. 

O projeto transforma dados brutos de transações em informações visuais dinâmicas, permitindo avaliar o faturamento, a distribuição por planos de assinatura, a adesão a add-ons (*Season Passes*) e o comportamento de renovação dos clientes.

---

## 💡 Pergunta e Indicadores de Negócio Analisados
O painel foi construído para responder às seguintes perguntas estratégicas:
- **Faturamento Total:** Qual o volume bruto de receita gerado no período?
- **Desempenho por Plano:** Como a receita se divide entre os planos *Core*, *Standard* e *Ultimate*?
- **Planos Anuais vs. Recorrência:** Qual o faturamento vindo de assinaturas anuais em relação às mensais e trimestrais?
- **Penetração de Add-ons:** Qual a receita adicional gerada por pacotes como *EA Play Season Pass* e *Minecraft Season Pass*?

---

## 📈 Principais Métricas Extraídas (Visão Geral)
- **Faturamento Total:** R$ 7.633,00
- **Total de Pedidos/Assinaturas:** 295 transações
- **Ticket Médio por Cliente:** R$ 25,87
- **Plano com Maior Receita:** *Ultimate* (R$ 5.388,00 — representa ~70,5% do total)
- **Distribuição de Recorrência:**
  - **Mensal:** 139 assinaturas (R$ 3.571,00)
  - **Trimestral:** 85 assinaturas (R$ 2.308,00)
  - **Anual:** 71 assinaturas (R$ 1.754,00)

---

## 📂 Estrutura do Arquivo (`.xlsx`)
A planilha foi organizada em 4 abas para garantir escalabilidade e fácil manutenção:

1. **`Assets`:** Paleta de cores (Xbox Branding), menus visuais e identidades de marca.
2. **`Bases`:** Tabela de dados brutos (`Tabela1`) com 295 registros e colunas de identificação do assinante, tipo de plano, datas, cupons e valores totais.
3. **`Cálculos`:** Camada técnica isolada contendo as Tabelas Dinâmicas e consolidações por pergunta de negócio via funções `=INFOEXTRARDADOS()`.
4. **`Dashboard`:** Interface visual interativa para navegação do usuário final com gráficos dinâmicos e cartões de métricas.

---

## 🛠️ Tecnologias e Funcionalidades do Excel
- **Tabelas Dinâmicas & Gráficos Dinâmicos:** Agregação e visualização em tempo real.
- **Segmentadores de Dados (Slicers):** Filtros dinâmicos por tipo de assinatura e período.
- **Fórmulas de Extração:** `=INFOEXTRARDADOS()` e fórmulas de soma/contagem dinâmicas.
- **Formatação Condicional:** Destaque visual de metas e categorias.

---

## 🚀 Como Visualizar e Reproduzir
1. **Clonar o Repositório:**
   ```bash
   git clone [https://github.com/seu-usuario/nome-do-repositorio.git](https://github.com/seu-usuario/nome-do-repositorio.git)
