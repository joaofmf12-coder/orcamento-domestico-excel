# 📊 Sistema de Orçamento Doméstico - Excel

Sistema completo de controle financeiro pessoal desenvolvido em Excel, com dashboard interativo, fluxo de caixa, gestão de cartões de crédito e investimentos.

![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-blue.svg)

## 🎯 Funcionalidades

### 📝 Lançamentos
- **Receitas** - Salários, benefícios, rendas extras
- **Despesas** - Pagamentos à vista (Débito/PIX)
- **Cartões de Crédito** - Compras parceladas com geração automática de parcelas
- **Investimentos** - Aportes e resgates por tipo de ativo

### 📊 Relatórios
- **Dashboard** - KPIs, gráficos de pizza, barras e evolução
- **Orçamento** - Comparativo Previsto vs Realizado por categoria
- **Fluxo de Caixa** - Visão mensal + próximos 30 dias

### ⚙️ Recursos Avançados
- ✅ Parcelas de cartão geradas automaticamente
- ✅ Fluxo de caixa dinâmico (atualiza com HOJE())
- ✅ Validação de dados com dropdowns
- ✅ Formatação condicional para alertas
- ✅ Status visual de parcelas pendentes

## 📁 Estrutura da Planilha

| Aba | Descrição |
|-----|-----------|
| `INICIO` | Guia de uso e instruções |
| `DASHBOARD` | Visão geral com KPIs e gráficos |
| `ORCAMENTO` | Previsto vs Realizado mensal |
| `FLUXO_CAIXA` | Fluxo mensal + 30 dias |
| `LAN_RECEITAS` | Lançamento de receitas |
| `LAN_DESPESAS` | Lançamento de despesas |
| `LAN_CARTOES` | Compras no cartão de crédito |
| `LAN_INVESTIMENTOS` | Aportes e resgates |
| `PARCELAS` | Parcelas geradas (automático) |
| `PREVISOES` | Receitas/despesas futuras |
| `FATURAS_CARTAO` | Configuração dos cartões |
| `CAD_Categorias` | Cadastro de categorias |
| `CAD_Investimentos` | Tipos de ativos |

## 🚀 Como Usar

1. **Baixe** o arquivo `.xlsx`
2. **Abra** no Microsoft Excel (recomendado) ou Google Sheets
3. **Configure** o saldo inicial em `FLUXO_CAIXA!B4`
4. **Lance** suas receitas, despesas e compras de cartão
5. **Visualize** os resultados no Dashboard

### 💳 Sistema de Cartão de Crédito

1. Lance a compra na aba `LAN_CARTOES`
2. Verifique a coluna "Status_Parcelas"
3. Se mostrar "⚠️ Pendente", solicite a geração das parcelas
4. As parcelas aparecem automaticamente no fluxo de caixa

## 📸 Screenshots
<img width="1843" height="620" alt="image" src="https://github.com/user-attachments/assets/f6599a4a-72df-4c63-b1a9-1d595ff7521a" />
<img width="1585" height="657" alt="image" src="https://github.com/user-attachments/assets/3f51c1fc-1548-4dc7-ab94-5bf1bf5173f3" />
<img width="1528" height="631" alt="image" src="https://github.com/user-attachments/assets/b0668677-7401-45ad-9780-27795b3bfbef" />
<img width="1823" height="562" alt="image" src="https://github.com/user-attachments/assets/9f5b6f0d-637e-4b25-804e-ae48b7a24906" />
<img width="1801" height="663" alt="image" src="https://github.com/user-attachments/assets/6a790d71-af1d-419b-b498-9d1f038ac4a1" />



## 📋 Requisitos

- Microsoft Excel 2016+ (recomendado)
- Ou Google Sheets (algumas funcionalidades podem ter limitações)

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para:
- Abrir issues reportando bugs
- Sugerir melhorias
- Enviar pull requests

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## ✨ Autor

Desenvolvido por João F. M. Fonseca

---

⭐ Se este projeto foi útil para você, considere dar uma estrela!
