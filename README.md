# JMS Lajes e Muros — Relatórios Executivos & Auditoria de Performance

Dossiê interativo de auditoria do **Chatbot de WhatsApp**, conferência de pedidos/vendas e performance de tráfego pago (Google Ads) da **JMS Lajes e Muros Pré-moldados** (Atibaia/SP).

---

## 📊 Conteúdo Disponível

1. **Auditoria de Chatbot & Vendas (Outubro/2026) — Principal (`/` ou `/relatorio_auditoria_outubro`)**
   - **440 contatos** analisados individualmente (cruzamento Supabase × Histórico WhatsApp × Planilha CRM).
   - **97 pedidos gerados** no mês (22,0% de conversão em ticket comercial).
   - **42 visitas presenciais agendadas** (43,3% dos pedidos).
   - **7 vendas formalmente fechadas** confirmadas no mês auditado.
   - Diagnóstico técnico de comportamento da IA, gargalos de handoff humano e tempo de resposta.
   - Download direto da base auditada completa em CSV (`/CRM/auditoria_pedidos_outubro_detalhada.csv`).
   - **Seção "Status do Projeto"**: Check-in executivo com todas as entregas concluídas, correções aplicadas e roadmap operacional.

2. **Apresentação Executiva Google Ads (Outubro/2026) (`/apresentacao_google_outubro`)**
   - Performance de campanhas de pesquisa e captação de leads.
   - Métricas de impressões, cliques, CTR, custo por lead e termos de pesquisa de maior conversão.
   - Modo de visualização em slides e exportação para PDF em alta definição.

3. **Apresentação de Marketing (Setembro/2026) (`/apresentacao_marketing_setembro`)**
   - Histórico consolidado do mês anterior para comparação evolutiva.

---

## 📌 Status do Projeto & Check-in de Entregas

- ✅ **Auditoria Concluída:** Base de Outubro 100% auditada e conferida contra o CRM.
- ✅ **Recepcionista Unificada em Produção:** Novo agente de IA ("José") com tom consultivo humanizado no WhatsApp.
- ✅ **Política Anti-Preço & Ticket 100%:** Chatbot blindado contra orçamentos automáticos; criação obrigatória de tickets para 100% dos produtos do catálogo.
- ✅ **Infraestrutura UAZAPI & Áudio Ativa:** Transcrição de mensagens de voz via Whisper e tratamento completo de identificadores da Meta (PN e LID).
- 🔄 **Próximos Passos:** Régua de follow-up automático (24h/72h) e parametrização avançada de UTMs nos anúncios.

---

## 🚀 Deploy na Vercel

Este repositório foi construído com arquitetura estática leve (Tailwind CSS via CDN + Chart.js) e possui o arquivo `vercel.json` configurado:
- **Build Command:** Vazio (não requer compilação / zero-config).
- **Output Directory:** `.` (raiz).
- **Clean URLs:** Habilitado para navegação limpa sem extensão `.html`.

---

Desenvolvido por **Tecx Consultoria**.
