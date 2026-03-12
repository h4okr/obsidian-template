---
créé: <% moment(tp.file.creation_date()).format("YYYY-MM-DD") %>
---
← [[Agenda/Trimestriel/<% moment(tp.file.title,'YYYY[ Q]Q').subtract(1, 'Q').format('YYYY/YYYY[ Q]Q') %>|<% moment(tp.file.title,'YYYY[ Q]Q').subtract(1, 'Q').format('[Trimestre n°]Q YYYY') %>]] | [[Agenda/Trimestriel/<% moment(tp.file.title,'YYYY[ Q]Q').add(1, 'Q').format('YYYY/YYYY[ Q]Q') %>|<% moment(tp.file.title,'YYYY[ Q]Q').add(1, 'Q').format('[Trimestre n°]Q YYYY') %>]] →

---
# <% moment(tp.file.title,'YYYY[ Q]Q').format("[Trimestre n°]Q") %> [[Agenda/Annuel/<% moment(tp.file.title, 'YYYY[ Q]Q').format('[année ]YYYY') %>|<% moment(tp.file.title,'YYYY[ Q]Q').format("YYYY") %>]]

<% tp.file.cursor() %>