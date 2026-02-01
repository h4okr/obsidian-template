← [[Agenda/Mensuel/<% moment(tp.file.title,'MMMM YYYY').subtract(1, 'M').format('YYYY/MMMM YYYY') %>|<% moment(tp.file.title,'MMMM YYYY').subtract(1, 'M').format('MMMM YYYY') %>]] | [[Agenda/Mensuel/<% moment(tp.file.title,'MMMM YYYY').add(1, 'M').format('YYYY/MMMM YYYY') %>|<% moment(tp.file.title,'MMMM YYYY').add(1, 'M').format('MMMM YYYY') %>]] →

---
# <% moment(tp.file.title,'MMMM YYYY').format("MMMM") %> [[Agenda/Annuel/<% moment(tp.file.title, 'MMMM YYYY').format('[année ]YYYY') %>|<% moment(tp.file.title,'MMMM YYYY').format("YYYY") %>]]

<% tp.file.cursor() %>