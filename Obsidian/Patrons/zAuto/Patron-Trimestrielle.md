← [[Agenda/Mensuel/<% moment(tp.file.title,'YYYY[ Q]Q').subtract(3, 'M').format('YYYY/YYYY[ Q]Q') %>|<% moment(tp.file.title,'YYYY[ Q]Q').subtract(3, 'M').format('[Trimestre n°]Q YYYY') %>]] | [[Agenda/Mensuel/<% moment(tp.file.title,'YYYY[ Q]Q').add(3, 'M').format('YYYY/YYYY[ Q]Q') %>|<% moment(tp.file.title,'YYYY[ Q]Q').add(3, 'M').format('[Trimestre n°]Q YYYY') %>]] →

---
# <% moment(tp.file.title,'YYYY[ Q]Q').format("[Trimestre n°]Q") %> [[Agenda/Annuel/<% moment(tp.file.title, 'YYYY[ Q]Q').format('[année ]YYYY') %>|<% moment(tp.file.title,'YYYY[ Q]Q').format("YYYY") %>]]

<% tp.file.cursor() %>