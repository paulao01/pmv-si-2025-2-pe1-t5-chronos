# Template padrão do site

Personalidade: produtividade (foco), confiança (consistência) e elegância (mínimo ruído visual).
Estrutura: navegação lateral (sidebar) com ícones + títulos, topbar com logo e ações rápidas, conteúdo em cards com hierarquia tipográfica clara.
Contraste funcional: cores neutras para a base; uma primária para navegação e elementos persistentes; uma de destaque para ações (CTA) e estados.
Acessibilidade: contraste AA/AAA nos textos; tamanhos relativos (rem), espaçamento generoso, foco visível, estados hover/active.
Consistência: tokens de design via CSS custom properties (variáveis) para cores, tipografia, radius, sombras e espaçamentos.

## Design

Layout padrão
Header (topbar): altura 64px, fundo neutro claro; contém logo do Chronos ao centro e ações (pesquisa, lembretes, calendário) à esquerda.
Sidebar (fixa à esquerda): 280px em desktop (colapsável para 80px); itens com ícone + rótulo: Início, Buscar, Calendário, Rotina, Metas, Lembretes, Conquistas, Projetos.
Área de Conteúdo: largura fluida até 1200–1280px; grid responsivo de cards (resumo diário, progresso, próximas tarefas).
Dashboard: KPIs (tarefas concluídas, próximas reuniões), gráfico de produtividade, notas rápidas, progresso semanal.

Calendário: visão semana (padrão) e mês, com cores por categoria (Trabalho, Estudo, Rotina, Projeto).
Lembretes: lista com filtros (Hoje, Semana, Atrasados), tags e prioridade visual.
Metas/Conquistas: cartões com status (Em andamento, Concluído) e badges.
Projetos: painel com etapas, responsáveis, progresso (barra ou “donut”).
Logo: exibido no topo ao centro do sidebar (desktop) e/ou à esquerda em dispositivos moveis; manter margem 16–24px e altura máx. 32px no header.

## Cores

Cores
Paleta Chronos (tokens)
Primária – Azul petróleo (produtividade/confiança): #0F4C75
Primária clara (hover/soft): #155F92
Destaque – Verde ação (confirmações/CTAs): #2ECC71
Atenção – Laranja (alertas/prazos): #F39C12
Erro – Vermelho: #E74C3C
Neutros:
Fundo base: #F5F7FA
Superfície (cards): #FFFFFF
Borda suave: #E6E8EC
Texto principal: #1F2937
Texto secundário: #6B7280
Categorias do calendário (cores de evento)
Trabalho: #1A73E8
Estudo: #7E57C2
Rotina: #26A69A
Projeto: #EF5350
Pessoal: #F59E0B


## Tipografia

Títulos (H1–H3) & Navegação: Poppins (transmite confiança)
Pesos: 600/700
Corpo, rótulos e texto corrido: Roboto (alta legibilidade em UI)
Pesos: 400/500

## Iconografia

Biblioteca: Lucide React Icons (leve e consistente).
Uso:
Sidebar: inicio, buscar, calendario, rotinas,metas, lembretes, conquista, projetos.
Ações: Adicionar, Editar,Salvar, Fechar, Filtrar
Estados: check-circle (sucesso), x-circle (erro).
Cores: ícones seguem o texto; exceções para estados (verde/vermelho) e categorias no calendário.
