Descrição

Automação de agendamento de consultas via WhatsApp utilizando IA (Gemini).



Pré-requisitos

\- Docker e Docker Compose instalados.

\- Uma conta no Gemini.

\- Um celular com WhatsApp para conectar ao WAHA.



Como rodar

1\. Abra o arquivo `docker-compose.yml` e insira sua chave da API Gemini na linha indicada.

2\. No terminal, rode: `docker-compose up -d`.

3\. Acesse o n8n em: http://localhost:5678

4\. Acesse o WAHA em: http://localhost:3000 e leia o QR Code.

5\. Importe o arquivo da pasta `/workflows` para o n8n.



Link DOC de configurações: https://docs.google.com/document/d/1lCUMJD\_YDr7tTxXUQrQz4SX6pIgGmGrA91uTPRLMfR0/edit?usp=sharing

