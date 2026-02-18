# 💊 Calendário de Medicação

Um sistema completo feito em Python para gerenciar medicamentos, horários e histórico de doses de forma simples e organizada.

---

## 📋 Funcionalidades

- Cadastrar medicamentos com nome, dosagem, horários e observações
- Listar todos os medicamentos ativos
- Marcar doses como tomadas
- Ver lembretes do dia com progresso em percentual
- Consultar histórico por período (hoje, 7 dias, 30 dias ou tudo)
- Desativar ou remover medicamentos
- Salvar todos os dados automaticamente em um arquivo `.json`

---

## 💻 Exemplo de uso

```
==================================================
💊 CALENDÁRIO DE MEDICAÇÃO
==================================================
1. 📋 Listar medicamentos
2. ➕ Adicionar medicamento
3. ✅ Marcar dose tomada
4. ⏰ Ver lembretes de hoje
5. 📊 Ver histórico
6. 🗑️  Remover medicamento
7. 🚪 Sair
==================================================
```

```
⏰ LEMBRETES DE HOJE
🔔 PENDENTES (não tomados):
   ⏰ 08:00 - Losartana (50mg)
   ⏰ 12:00 - Vitamina D (1 comprimido)

📅 PRÓXIMOS:
   ⏰ 20:00 - Losartana (50mg)

📊 Progresso de hoje: 1/3 doses (33%)
```

---

## 💾 Sobre o armazenamento de dados

Todos os medicamentos e o histórico de doses são salvos automaticamente no arquivo `medicamentos.json` na mesma pasta do programa. Isso significa que seus dados são mantidos mesmo após fechar o programa.

---

## 🧰 O que foi usado

- `json` — para salvar e carregar os dados em arquivo
- `os` — para verificar se o arquivo de dados já existe
- `datetime` e `timedelta` — para trabalhar com datas, horários e filtros de período
- `Classes e orientação a objetos` — para organizar o sistema de forma estruturada
- `List comprehensions` — para filtrar medicamentos e histórico de forma eficiente
- `try/except` — para tratar erros de entrada do usuário

---

## 🧠 Conceitos abordados

- Programação orientada a objetos com `class`
- Leitura e escrita de arquivos com `open()` e `json`
- Manipulação de datas e horários com `datetime`
- Menus interativos com `while` e `input()`
- Filtragem de listas com condições
- Agrupamento de dados por chave

---

## 👩‍💻 Autora

Feito com 💜 por Aline  
Projeto de aprendizado — Python do zero!
