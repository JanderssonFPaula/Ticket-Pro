# Gerenciador de Tarefas – Matriz de Eisenhower + Método Ivy Lee

Aplicação web simples em **HTML**, **CSS** e **JavaScript** para organizar tarefas combinando a **Matriz de Eisenhower** (priorização) e o **Método Ivy Lee** (seleção das 6 tarefas diárias mais importantes).

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
Este projeto é de código aberto e está disponível sob a licença MIT.

Copyright (c) 2025 Jandersson F de Paula - @ConsultyD

É concedida permissão, gratuitamente, a qualquer pessoa que obtenha uma cópia
deste software e dos arquivos de documentação associados (o "Software"), para
lidar no Software sem restrições, incluindo, sem limitação, os direitos de usar,
copiar, modificar, mesclar, publicar, distribuir, sublicenciar e/ou vender cópias
do Software, e permitir que pessoas a quem o Software é fornecido o façam,
sujeito às seguintes condições:

O aviso de copyright acima e este aviso de permissão devem ser incluídos em todas
as cópias ou partes substanciais do Software.

O SOFTWARE É FORNECIDO "NO ESTADO EM QUE SE ENCONTRA", SEM GARANTIA DE QUALQUER
TIPO, EXPRESSA OU IMPLÍCITA, INCLUINDO, MAS NÃO SE LIMITANDO ÀS GARANTIAS DE
COMERCIALIZAÇÃO, ADEQUAÇÃO A UM DETERMINADO FIM E NÃO VIOLAÇÃO. EM NENHUMA
HIPÓTESE OS AUTORES OU DETENTORES DOS DIREITOS AUTORAIS SERÃO RESPONSÁVEIS POR
QUALQUER RECLAMAÇÃO, DANOS OU OUTRAS RESPONSABILIDADES, SEJA EM AÇÃO DE CONTRATO,
ATO ILÍCITO OU OUTRO, DECORRENTE DE, OU EM CONEXÃO COM O SOFTWARE OU O USO OU
OUTRAS NEGOCIAÇÕES NO SOFTWARE.



## 📝 Autor

Este código foi desenvolvido por:  
- 👤 **Jandersson F. de Paula**  
- 🔗 **GitHub:** [Clique Aqui](https://github.com/JanderssonFPaula)

---

## 💼 ConsultyD  

Para dúvidas, sugestões ou problemas:  
- Abra uma *issue* no repositório  
- Entre em contato através do email ou redes sociais  

- 📧 **Email:** contato@consultyd.com.br  
- 📸 **Instagram:** [Clique Aqui](https://www.instagram.com/consultyd/)  


---

**Desenvolvido com ❤️ para facilitar o gerenciamento de projetos**
