---
créé: <% moment(tp.file.creation_date()).format("YYYY-MM-DD") %>
type: quotidienne
---
# <% moment(tp.file.title,'YYYY-MM-DD').format("dddd D MMMM YYYY") %>

← [[Agenda/Journal/<% moment(tp.file.title, 'YYYY-MM-DD').subtract(1, 'd').format('YYYY/MM-MMMM/YYYY-MM-DD-dddd') %>|la veille]] | [[Agenda/Journal/<% moment(tp.file.title, 'YYYY-MM-DD').add(1, 'd').format('YYYY/MM-MMMM/YYYY-MM-DD-dddd') %>|le lendemain]] →

---
# 📝Notes
<% tp.file.cursor() %>

# ✅Pense-bête
- [ ] …
