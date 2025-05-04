Automação de Prospecção Contábil via WhatsApp

Ferramenta para captação de leads contábeis, integrando raspagem de dados do EmpresaDois, consulta de CNPJs na Receita Federal e disparo de mensagens personalizadas via API do WhatsApp.

Funcionalidades Principais
🕸️ Raspagem de Dados: Extrai CNPJs de empresas de acordo com filtros (localidade, atividade econômica, etc.) do site EmpresaDois.

🔍 Consulta de Contatos: Obtém telefones e e-mails associados aos CNPJs via dados públicos da Receita Federal.

📲 Integração com WhatsApp: Envio automatizado de mensagens oferecendo serviços contábeis.

📊 Filtros Personalizáveis: Busca empresas por segmento, região, porte ou CNAE.

Tecnologias Utilizadas
Python (raspagem com Selenium/BeautifulSoup ou Scrapy).

API Oficial do WhatsApp Business ou bibliotecas como pywhatkit.

Banco de Dados (SQLite, PostgreSQL) para armazenar CNPJs e contatos.

Gerenciamento de Tasks (Celery ou Cron para agendamento).

Aviso Importante
⚠️ Respeite as políticas de uso do WhatsApp e leis de proteção de dados (LGPD/GDPR).

Evite spam: personalize mensagens e priorize empresas com potencial real de interesse.

Como Contribuir
Clone o repositório: git clone https://github.com/seu-usuario/contabot.git

Instale as dependências: pip install -r requirements.txt

Configure as variáveis de ambiente (API keys, tokens).

Execute: python main.py

Contribuições são bem-vindas! 👩💻👨💻

Licença
Distribuído sob a licença MIT. Veja LICENSE para detalhes.

Tags
prospecção contabilidade automação whatsapp-api web-scraping cnpj
