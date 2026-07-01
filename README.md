# 🚀 Barber Plus
Plataforma SaaS de alta performance para gestão estratégica, agendamento em tempo real e controle de faturamento para barbearias modernas.

---

## 📷 Demonstração Visual e Acesso
> **Nota:** O código-fonte deste projeto é proprietário e mantido de forma privada. Esta página serve como vitrine técnica, demonstração de arquitetura e usabilidade.

*   🌐 **Acesse a aplicação rodando:** [Clique aqui para acessar o Deploy Ativo](https://projetos.techcarlos.com.br/barber)
*   🎥 **Vídeo de Demonstração (Walkthrough):** [Assista ao funcionamento na prática](https://github.com/techcarlosandre/portfolio-carlos/raw/main/public/barber/barber-app_opt.mp4)

---

## ✨ Funcionalidades Principais
*   📅 **Agendamento Inteligente em Tempo Real** — Fluxo dinâmico de reserva de horários que evita conflitos de agendas e overbooking.
*   👥 **Painel de Gestão de Profissionais** — Gestão individual de comissões, horários de expediente e serviços habilitados por barbeiro.
*   📊 **Dashboard de Faturamento** — Gráficos detalhados exibindo ticket médio, faturamento por período e serviços mais procurados.

## 🛠️ Stack Tecnológica & Arquitetura
*   **Frontend:** Next.js 16 (App Router), React 19, TailwindCSS v4, Lucide Icons, Framer Motion (para micro-animações de transições de telas).
*   **Backend & APIs:** Server-side Rendering (SSR) nativo do Next.js e API Routes para operações e persistência de dados.
*   **Banco de Dados & Persistência:** PostgreSQL (com transações ACID estritas para garantir consistência em agendamentos concorrentes).

## 🏗️ Diferenciais Técnicos Aplicados
*   **Controle de Concorrência Confiável:** Escolha de banco relacional para garantir integridade referencial nas tabelas de agendamentos, usuários e comissões.
*   **Experiência de Usuário Premium:** Layout responsivo otimizado para celulares (onde ocorrem 90% dos agendamentos) com animações fluidas via Framer Motion.
*   **Estruturação Escalável:** Uso do App Router do Next.js modularizado e componentização limpa baseada nos princípios de Clean Code.
