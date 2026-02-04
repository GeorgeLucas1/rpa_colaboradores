# Bot de Análise e Classificação de E-mails

## Descrição
Bot automatizado para análise de e-mails de diferentes provedores (Gmail, Yahoo, entre outros). O sistema processa cada mensagem, avalia o conteúdo com base em palavras-chave e atribui um score de risco, classificando o nível de ameaça do e-mail.

## Objetivo
Identificar e classificar e-mails potencialmente suspeitos ou maliciosos, reduzindo riscos de segurança e apoiando a proteção de usuários menos experientes.

## Funcionalidades
- Leitura automática de e-mails.
- Compatibilidade com múltiplos provedores.
- Análise de conteúdo baseada em palavras-chave.
- Cálculo de score de risco.
- Classificação do nível de ameaça.
- Armazenamento dos dados em banco SQLite.
- Operação contínua (24/7).
- Estrutura preparada para evolução de funcionalidades.

## Tecnologias
- Linguagem: Python  
- Banco de dados: SQLite  
- Conteinerização: Docker (opcional)

## Funcionamento
1. Conexão com a caixa de e-mail configurada.
2. Leitura individual de cada e-mail.
3. Análise do conteúdo textual.
4. Identificação de palavras-chave de risco.
5. Cálculo do score de ameaça.
6. Classificação do e-mail.
7. Armazenamento das informações no banco de dados.

## Benefícios
- Redução de riscos causados por e-mails maliciosos.
- Automação da triagem de e-mails.
- Suporte à segurança da informação.
- Facilidade de implantação e manutenção.

## Implantação
- Execução local ou em servidor.
- Suporte à execução via Docker para padronização e portabilidade.

## Evolução
O bot pode ser expandido com:
- Novas regras e palavras-chave.
- Integração com outros bancos de dados.
- Sistemas de alerta e relatórios.
- Uso de técnicas de machine learning para classificação.
