# Automação de e-mails personalizados com n8n e Gemini

## Sobre o projeto

Este projeto automatiza a geração de e-mails personalizados para clientes com base em seus dados e em produtos de investimento compatíveis com seus perfis.

## Tecnologias utilizadas

- **n8n:** automação do fluxo de trabalho.
- **Google Colab:** envio dos dados por meio de uma requisição HTTP.
- **Google Gemini API:** geração de mensagens personalizadas.
- **Webhook:** comunicação entre o Colab e o n8n.
- **GitHub:** armazenamento e compartilhamento do workflow.

## Como funciona

1. O Google Colab envia os dados para o webhook do n8n.
2. O n8n organiza os dados dos clientes e dos produtos.
3. Os dados são enviados ao Gemini para gerar mensagens personalizadas.
4. O workflow organiza os resultados com nome, e-mail e mensagem.

## Como utilizar

1. Baixe o arquivo JSON deste repositório.
2. Importe o workflow para sua instância do n8n.
3. Configure suas próprias credenciais e chaves de API.
4. Ajuste a URL do webhook e execute os testes.

**Observação:** não inclua chaves de API, credenciais ou dados reais de clientes no repositório.
