
# 👋 Sobre mim

Sou estudante de Análise e Desenvolvimento de Sistemas na FIAP (conclusão prevista para dezembro de 2026) e trabalho com front-end, automação e integração de sistemas.

Na maioria dos projetos que desenvolvi, o ponto de partida não foi uma tecnologia, foi um processo manual que estava consumindo tempo de alguém, uma recepção confirmando agendamento um a um pelo WhatsApp, um site institucional que nunca acompanhava o conteúdo que o cliente produzia em outro lugar. Prefiro entender esse tipo de gargalo antes de decidir qual stack faz sentido para resolvê-lo.

Atualmente busco oportunidades como **Desenvolvedora Front-end, Full Stack Júnior ou Automation Developer**.

📍 São Paulo, Brasil

---

# Áreas de atuação

- Front-end com React e TypeScript
- Automação de processos com n8n
- Integração entre sistemas e consumo de APIs REST
- Aplicação de IA em fluxos de atendimento e processamento de dados
- Modelagem de banco de dados e arquitetura de solução (Supabase/PostgreSQL, Docker)

Também estou me aprofundando em Spring Boot e Power BI para ampliar minha atuação em backend e análise de dados.

---

# Tecnologias

<div align="center">
<img src="https://skillicons.dev/icons?i=react,ts,js,html,css,nodejs,java,spring,postgres,mysql,git,docker,figma"/>
</div>

---

# Projetos

## 🤖 SaaS multi-tenant para clínicas de estética
Clínicas de estética confirmavam agendamentos manualmente pelo WhatsApp, o que gerava esquecimentos, faltas e retrabalho para a recepção. Desenvolvi a automação completa do relacionamento com o paciente em n8n — lembretes automáticos, reagendamento, cancelamento e um atendimento inicial com IA.

Desde o início, desenhei a solução como multi-tenant: cada clínica opera com sua própria configuração e seus próprios dados, sobre a mesma base de arquitetura, o que permite atender novos clientes sem reconstruir o sistema. Fui responsável pela modelagem dos fluxos, pelas regras de negócio, pela integração entre WhatsApp e banco de dados (Supabase/PostgreSQL) e pela infraestrutura em Docker e Redis. O dashboard administrativo teve apoio de ferramentas de IA na implementação, sob minha direção técnica.

O resultado é uma base pronta para ser comercializada como Micro SaaS, e não apenas uma solução pontual para um único cliente.

`n8n` `Supabase` `PostgreSQL` `React` `Docker`

---

## 💊 Chatbot de medicamentos
Encontrar informação técnica confiável sobre medicamentos costuma exigir consultar documentos extensos em fontes dispersas. Construí um chatbot em n8n que consulta diretamente a base oficial do FDA e usa o Google Gemini para interpretar e organizar essa informação em linguagem clara.

Um ponto que exigiu atenção especial foi delimitar o escopo das respostas, para que o bot nunca chegasse perto de oferecer orientação médica — ele resume dados oficiais, não os interpreta clinicamente. O relatório completo só é gerado quando solicitado explicitamente.

`n8n` `Google Gemini` `API FDA`

---

## 🏥 Plataforma de acessibilidade — Hospital das Clínicas
Desenvolvido durante um desafio acadêmico da FIAP em parceria com o Hospital das Clínicas, com foco em pacientes com baixa familiaridade tecnológica. Atuei no front-end (React, TypeScript, Vite, Tailwind CSS), consumindo a API construída pelo time de backend em Java.

A prioridade aqui não era sofisticação visual, e sim garantir que a navegação fosse simples e acessível para quem tem pouco contato com interfaces digitais.

`React` `TypeScript` `Vite` `Tailwind`

---

## ⚖️ Landing page integrada à YouTube API
Um cliente da área jurídica produzia conteúdo regularmente no YouTube, mas seu site institucional não refletia isso — ficava desatualizado em relação ao canal. Integrei a YouTube Data API diretamente na landing page, com paginação de resultados, para que novos vídeos passassem a aparecer automaticamente, sem necessidade de atualização manual.

`JavaScript` `YouTube Data API`

---

## 📊 FlowCap
Ferramenta para simular cenários operacionais e tornar visível o crescimento de backlog quando há uma diferença sustentada entre demanda e capacidade. Separei claramente a lógica de cálculo (backlog, atraso, classificação de risco) da camada de interface, para que as regras de negócio pudessem evoluir sem impactar a experiência do usuário.

`React` `TypeScript`

---

# Contato

💼 [LinkedIn](https://br.linkedin.com/in/thaissa-kailaine)· 📧 thaissakailaine.ti@gmail.com
