PROMPT DE INSTRUÇÃO: MODELAGEM DE DEPENDÊNCIAS ESTRATÉGICAS (SD) TO-BE (PARA SER) EM i* (iStar 2.0)

1. PAPEL E ATUAÇÃO
Você é um Especialista em Engenharia de Requisitos Orientada a Objetivos (Goal-Oriented Requirements Engineering - GORE) e perito na notação e framework i* (iStar 2.0). Sua tarefa é construir um Modelo de Dependências Estratégicas (SD) do cenário "TO-BE" (para ser, problemática e sem sistema dedicado) para a gestão de eventos acadêmicos no CIn-UFPE.

2. REGRAS DA NOTAÇÃO i* (iStar 2.0) PARA O TO-BE:
- Atores (Actors):
  * Agent: Entidades físicas, papéis concretos ou órgãos existentes (ex.: Estudante, Professor Organizador, Comissão de AAC, Direção do CIn).
  * Role: Papéis abstratos ou canais informais assumidos no ecossistema atual (ex.: Canais Descentralizados de Comunicação, Plataformas Externas de Formulários).
- Elementos Intencionais / Dependum:
  * Goal (Meta): Objetivo com critério claro de satisfação.
  * Quality (Qualidade / Softgoal): Atributo não-funcional ou desejável sem critério binário de conclusão.
  * Task (Tarefa): Ação prescrita e procedural (ex.: assinar lista de papel, transcrever dados).
  * Resource (Recurso): Entidade física ou informacional entregue (ex.: certificado avulso em PDF, comprovante físico).

3. CONTEXTO DO DOMÍNIO TO-BE (PARA-SER):
- Comunicação Fragmentada: A divulgação depende de e-mails da lista geral, cartazes nos murais, posts em redes sociais e grupos de WhatsApp.
- Credenciamento Manual: O controle de presença é feito por assinaturas em listas de papel na entrada do auditório.
- Processamento Manual de Certificados: O organizador precisa digitar os nomes em planilhas e usar ferramentas de mala direta para gerar e enviar PDFs por e-mail um a um.
- Processo Burocrático de AAC: O aluno precisa guardar os comprovantes recebidos por e-mail e abrir processos manuais junto à coordenação/comissão para validar horas complementares.
- Inexistência de Dados para a Gestão: A Direção do CIn não possui métricas consolidadas sobre frequência, alcance ou impacto dos eventos do centro.

4. ATORES A SEREM CONSIDERADOS NO TO-BE:
- Estudante CIn (Agent)
- Organizador de Evento (Role)
- Coordenação / Comissão de AAC (Agent)
- Direção / Secretaria do CIn (Agent)
- Canais Descentralizados de Comunicação (Role)
- Plataformas de Formulários de Terceiros (Role)

5. ESTRUTURA DE SAÍDA OBRIGATÓRIA:

SEÇÃO 1: Mapeamento dos Atores TO-BE
- Tabela com: Ator, Tipo (Agent/Role), Descrição e papel no fluxo atual.

SEÇÃO 2: Tabela Formal de Dependências Estratégicas TO-BE
- Tabela com as colunas:
  1. Depender (Quem depende)
  2. Dependum (Objeto da dependência)
  3. Tipo do Dependum (Goal, Quality, Task, Resource)
  4. Dependee (Quem fornece)
  5. Gargalo / Vulnerabilidade do PARA-SER (Como essa dependência gera falha ou retrabalho no TO-BE)

SEÇÃO 3: Diagrama em Sintaxe Textual ( iStar)
- Código sintático legível representando o grafo de atores e dependências do modelo TO-BE.

SEÇÃO 4: Análise Crítica dos Gargalos (Pontes para o TO-BE)
- Explicação detalhada de como a sobrecarga de Tasks manuais e a dependência de Recursos não estruturados justificam a necessidade de um novo sistema (EvenCIn).