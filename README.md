# 📊 Automação de Prospecção Contábil via WhatsApp

Ferramenta para captação de leads contábeis, integrando raspagem de dados do [EmpresaDois](https://empresadois.com.br), consulta de CNPJs na [Receita Federal](https://www.gov.br/receitafederal) e disparo de mensagens personalizadas via **API do WhatsApp**.

![Badge](https://img.shields.io/badge/Python-3.8%2B-blue) ![Badge](https://img.shields.io/badge/License-MIT-green) ![Badge](https://img.shields.io/badge/Status-Desenvolvimento%20Ativo-orange)

---

## ✨ Funcionalidades Principais

- **🕸️ Raspagem de Dados**:  
  Extrai CNPJs de empresas de acordo com filtros (localidade, atividade econômica, etc.) do site EmpresaDois.

- **🔍 Consulta de Contatos**:  
  Obtém telefones e e-mails associados aos CNPJs via dados públicos da Receita Federal.

- **📲 Integração com WhatsApp**:  
  Envio automatizado de mensagens oferecendo serviços contábeis.

- **📊 Filtros Personalizáveis**:  
  Busca empresas por segmento, região, porte ou CNAE.

---

## 🛠️ Tecnologias Utilizadas

- **Python** (*raspagem com `Selenium`/`BeautifulSoup` ou `Scrapy`*).  
- **API Oficial do WhatsApp Business** ou bibliotecas como `pywhatkit`.  
- **Banco de Dados** (*SQLite, PostgreSQL*) para armazenar CNPJs e contatos.  
- **Gerenciamento de Tasks** (*Celery* ou *Cron* para agendamento).  

---

## ⚠️ Aviso Importante

- Respeite as políticas de uso do WhatsApp e leis de proteção de dados (**LGPD/GDPR**).  
- **Evite spam**: personalize mensagens e priorize empresas com potencial real de interesse.  

---

## 🚀 Como Contribuir

1. Clone o repositório:  
   ```bash
   git clone https://github.com/seu-usuario/contabot.git
