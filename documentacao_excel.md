# 📊 Documentação: Dashboard de Gestão de Fluxo Administrativo

[cite_start]Este projeto demonstra a aplicação de **Microsoft Excel Intermediário** [cite: 17, 42] [cite_start]para resolver gargalos operacionais em recepções clínicas e centros de assistência técnica, áreas onde possuo sólida experiência profissional.

## 🎯 Problema Resolvido
[cite_start]A falta de visibilidade em tempo real sobre o tempo de espera dos clientes e o status das demandas, o que prejudica a experiência do usuário e a eficiência da equipe de suporte[cite: 12, 29].

## 🛠️ Estrutura da Planilha

### 1. Colunas de Dados e Organização
* [cite_start]**ID / Registro:** Identificador único para garantir a integridade do histórico, essencial para prontuários clínicos ou ordens de serviço (OS)[cite: 22, 26].
* [cite_start]**Timestamp (Entrada):** Registro do horário de chegada para cálculo de KPI de atendimento e agilidade no suporte[cite: 21, 29].
* [cite_start]**Categoria de Serviço:** Validação de dados para segmentar o tipo de suporte técnico ou consulta[cite: 26, 31].
* [cite_start]**Status Dinâmico:** Lista suspensa para controle de fluxo: *Triagem, Em Atendimento, Pendente, Concluído*[cite: 21, 26].

### 2. Fórmulas e Lógica Aplicada
Utilizo lógica para automatizar alertas e garantir a proatividade no atendimento:
* **Sinalização de Atraso Crítico:** `=SE(E(C2="Pendente";AGORA()-B2>0,02);"⚠️ CRÍTICO";"✅ OK")`
  * *Objetivo:* Identifica automaticamente se um cliente excedeu o tempo de espera previsto (aprox. 30 min), permitindo uma intervenção rápida e atenciosa.
* [cite_start]**Busca de Dados (PROCV / XLOOKUP):** Integração de informações de clientes cadastrados em sistemas globais, simulando a operação em plataformas de larga escala como Samsung e Claro[cite: 26, 31].
* [cite_start]**Relatórios de Produtividade:** Uso de fórmulas de contagem (`CONT.SE`) para gerar dados para auditoria e gestão de contas B2B[cite: 27, 31].

---

### Por que isso é um diferencial?
[cite_start]Este modelo reflete minha **alta proficiência em sistemas internos** [cite: 6] [cite_start]e minha facilidade em operar interfaces proprietárias complexas[cite: 11, 15]. [cite_start]Demonstra como utilizo ferramentas tradicionais para garantir a **integridade do histórico clínico e técnico** [cite: 23, 27][cite_start], sempre com foco em inovação e produtividade através de IA[cite: 13, 16].
