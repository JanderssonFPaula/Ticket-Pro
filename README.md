# Ticket-Pro - Gerenciador de Tarefas – Matriz de Eisenhower + Método Ivy Lee
Aplicação web em HTML, CSS e JavaScript para organizar tarefas com a Matriz de Eisenhower e o Método Ivy Lee. Importa e exporta arquivos Excel, classifica tarefas por prioridade e permite escolher até 6 tarefas diárias, tudo direto no navegador, sem necessidade de backend.

O sistema funciona 100% no navegador, sem necessidade de backend. É possível **importar** um arquivo Excel com tarefas, classificá-las automaticamente nos quadrantes da matriz e **exportar** o resultado atualizado para Excel.

---

## 📌 Funcionalidades
- 📂 **Importar Excel** com colunas `Nome`, `Urgente`, `Importante`.
- 📊 Classificação automática nos 4 quadrantes da Matriz de Eisenhower:
  1. Urgente & Importante
  2. Não Urgente & Importante
  3. Urgente & Não Importante
  4. Não Urgente & Não Importante
- ✅ Seleção de até **6 tarefas diárias** (Método Ivy Lee).
- 💾 Exportação para Excel com as tarefas atualizadas.
- 🔄 Compatibilidade com `TRUE`, `False`, `1`, `0` para valores booleanos.

---

## 📂 Estrutura do Projeto
```
/eisenhower-ivy
  ├── index.html
  ├── style.css
  ├── README.md
  └── tarefas_exemplo.xlsx
```

---

## 📥 Como Usar
1. Abra o arquivo `index.html` no navegador.
2. Clique em **Escolher arquivo** e selecione um Excel com suas tarefas.
3. As tarefas serão exibidas automaticamente nos quadrantes.
4. Clique em uma tarefa para adicioná-la à lista de tarefas do dia (máximo 6).
5. Ao terminar, clique em **Baixar Excel** para salvar as alterações.

---

## 📑 Formato do Excel de Entrada
| Nome              | Urgente | Importante |
|-------------------|---------|------------|
| Reunião com cliente | TRUE    | TRUE       |
| Estudar Java      | FALSE   | TRUE       |
| Enviar relatório  | TRUE    | FALSE      |
| Organizar mesa    | FALSE   | FALSE      |

> Você pode usar o arquivo `tarefas_exemplo.xlsx` que acompanha o projeto para testar.

---

## 🛠 Tecnologias Usadas
- HTML5
- CSS3
- JavaScript (ES6+)
- [SheetJS (XLSX.js)](https://sheetjs.com/) para leitura e escrita de arquivos Excel

---

## 📜 Licença
Este projeto está licenciado sob a licença MIT - veja o arquivo LICENSE para mais detalhes.



## 📝 Autor
Este código foi desenvolvido por:

**💼 ConsultyD**
- **👤 Jandersson Ferreira de Paula**  
- **📧 Email:** contato@consultyd.com.br
- **🔗 GitHub:**[Clique Aqui](https://github.com/JanderssonFPaula)
