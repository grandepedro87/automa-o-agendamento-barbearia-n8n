Atue como um especialista em N8N.
Crie uma automação para agendamento automático de clientes de uma barbearia.

Público:
Clientes que buscam agendar serviços em uma barbearia.

Ferramentas envolvidas:
Google Forms, Google Sheets e WhatsApp.

Fluxo:
1. Receber os dados do formulário (Nome, WhatsApp, Data/Horário e Tipo de Serviço).
2. Verificar a disponibilidade do horário consultando a planilha.
3. Se o horário estiver livre: Registrar os dados na planilha com status "Confirmado", calcular o valor e enviar mensagem de confirmação no WhatsApp com o valor do serviço.
4. Se o horário estiver ocupado: Registrar os dados com status "Recusado" e enviar mensagem no WhatsApp informando a indisponibilidade do horário.

Regras:
- Só agendar se o horário estiver livre.
- Formatar o número do WhatsApp para incluir o código do país (55) e DDD.
- Atribuir o valor correto conforme o serviço selecionado (Corte: R$ 40, Barba: R$ 30, Combo: R$ 60).

Explique quais nós do N8N devem ser utilizados e a lógica de funcionamento do workflow.