# 📱 SmartQueue - Sistema de Fila Inteligente

O SmartQueue é um sistema de gerenciamento de filas digitais que substitui filas físicas por uma solução moderna, organizada e eficiente.

## 🚀 Objetivo

Reduzir o tempo de espera, evitar aglomerações e melhorar a experiência do usuário em ambientes como hospitais, bancos e comércios.

## 🧠 Funcionalidades

- Cadastro de usuários
- Entrada e saída da fila
- Visualização da posição em tempo real
- Cálculo de tempo estimado de espera
- Painel administrativo para controle da fila
- Sistema de prioridade (normal e preferencial)
- Notificações de chamada
- Histórico de atendimentos

## ⚙️ Tecnologias Utilizadas

- Python
- FastAPI
- SQLite
- SQLAlchemy
- HTML, CSS e JavaScript
- Chart.js

## 📊 Diferenciais

- Previsão de tempo de espera baseada em dados
- Organização automática da fila
- Interface simples e intuitiva
- Aplicação em cenários reais

## 🖥️ Como executar o projeto

```bash
# Clonar repositório
git clone https://github.com/seu-usuario/smartqueue

# Entrar na pasta
cd smartqueue

# Instalar dependências
pip install -r requirements.txt

# Rodar o servidor
uvicorn app.main:app --reload