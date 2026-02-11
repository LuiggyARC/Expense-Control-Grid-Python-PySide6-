# Expense Control Grid

Aplicação desktop desenvolvida em **Python** com **PySide6** para controle de gastos e receitas, utilizando uma interface em formato de planilha (grid editável), com resumo automático e exportação de dados.

Este projeto é um **MVP funcional e evolutivo**, pensado para receber melhorias contínuas conforme o uso real, ainda não esta terminado sera implementado melhoras e testes em uso vou atualizar layouts e funcionalidades futuramente.

---

## 📌 Funcionalidades
- Interface em **grid editável** (estilo planilha)
- Tipos de lançamento: **Entrada / Saída**
- Categorias em lista (inclui **Salário** e **Vendas**)
- Filtro por mês ou visualização geral
- Resumo automático:
  - Entradas
  - Saídas
  - Saldo (lucro/prejuízo)
- Botão **+ Nova linha**
- Botão **Excluir linha selecionada**
- Atalho de teclado (**DEL**) para exclusão
- Exportação de dados para **CSV**
- Tema moderno em azul, com:
  - Entradas destacadas em verde
  - Saídas destacadas em vermelho

---

## 🖥️ Screenshots

### Tela principal
<img width="1366" height="725" alt="image" src="https://github.com/user-attachments/assets/0e330b61-52f4-4a16-ada3-f3078ce7a3a9" />


### Grid de lançamentos
<img width="1366" height="492" alt="image" src="https://github.com/user-attachments/assets/b90ed01b-342f-4546-8f8f-3d687e46fd3d" />



### Resumo e visualização
<img width="1366" height="726" alt="image" src="https://github.com/user-attachments/assets/8394667f-fd01-473e-876e-52e458abbe05" />

---

## 🧰 Tecnologias utilizadas
- Python 3
- PySide6 (Qt)
- SQLite (persistência local)
- Git

---

## ▶️ Como executar o projeto (Windows / PowerShell)
```powershell, quando projeto estiver concluido ele sera um executavel semelhante ao execel.
cd expense_mvp
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
python app.py
