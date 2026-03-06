# 📊 Documentação: Dashboard de Gestão de Fluxo Administrativo

Este projeto demonstra a aplicação de **Microsoft Excel Intermediário** para resolver gargalos operacionais em recepções clínicas e centros de assistência técnica, áreas onde possuo sólida experiência profissional.

## 🎯 Problema Resolvido
A falta de visibilidade em tempo real sobre o tempo de espera dos clientes e o status das demandas, o que prejudica a experiência do usuário e a eficiência da equipe de suporte.

## 🛠️ Estrutura da Planilha

### 1. Colunas de Dados e Organização
* **ID / Registro:** Identificador único para garantir a integridade do histórico, essencial para prontuários clínicos ou ordens de serviço (OS).
* **Timestamp (Entrada):** Registro do horário de chegada para cálculo de KPI de atendimento e agilidade no suporte.
* **Categoria de Serviço:** Validação de dados para segmentar o tipo de suporte técnico ou consulta.
* **Status Dinâmico:** Lista suspensa para controle de fluxo: *Triagem, Em Atendimento, Pendente, Concluído*.

### 2. Fórmulas e Lógica Aplicada
Utilizo lógica para automatizar alertas e garantir a proatividade no atendimento:
* **Sinalização de Atraso Crítico:** `=SE(E(C2="Pendente";AGORA()-B2>0,02);"⚠️ CRÍTICO";"✅ OK")`
  * *Objetivo:* Identifica automaticamente se um cliente excedeu o tempo de espera previsto (aprox. 30 min), permitindo uma intervenção rápida e atenciosa.
* **Busca de Dados (PROCV / XLOOKUP):** Integração de informações de clientes cadastrados em sistemas globais, simulando a operação em plataformas de larga escala.
* **Relatórios de Produtividade:** Uso de fórmulas de contagem (`CONT.SE`) para gerar dados para auditoria e gestão de contas.

---

### Por que isso é um diferencial?
Este modelo reflete minha **alta proficiência em sistemas internos** e minha facilidade em operar interfaces proprietárias complexas. Demonstra como utilizo ferramentas tradicionais para garantir a **integridade do histórico clínico e técnico**, sempre com foco em inovação e produtividade através de IA.
