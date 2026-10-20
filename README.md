Atue como um especialista em n8n.

Crie uma automação para confirmação de inscrição em um evento. 

# **Público:**

Organizadores de eventos, palestras e workshops.

# **Ferramentas envolvidas:** 

Google Forms, Google Sheets e Gmail. 

# **Fluxo Desejado:**

1 - Receber uma nova inscrição por meio do Google Forms.

2 - Registrar automaticamente os dados do participante no Google Sheets. 

3 - Validar se o participante informou um e-mail válido.

4 - Enviar um e-mail de confirmação de inscrição. 

# **Regras Importantes:**
1 - Ignorar inscrições sem e-mail válido.

2 - Registrar os dados de cada participante no Google Sheets. 

3 - Disparar e-mail de confirmação apenas após o registro bem sucedido da inscrição. 

4 - Evitar o envio de confirmações duplicadas. 

5 - Informar no e-mail os detalhes do evento. 

 
# **Nós a serem utilizados no n8n e a lógica de funcionamento.**


Google Forms - O participante preenche o formulário com os dados necessários para realizar a inscrição.

Google Sheets Trigger - Detecta uma nova linha na planilha vinculada ao Google Forms, sendo o gatilho que inicia o workflow no n8n. 

IF - Verifica se o e-mail preenchido durante a inscrição é válido. 

Gmail - Envia um e-mail automático confirmando o recebimento da inscrição, caso o e-mail seja válido. 

Google Sheets (Update Row) - Atualiza a tabela registrando o status do envio do e-mail. 
