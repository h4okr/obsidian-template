---
créé: <% moment(tp.file.creation_date()).format("YYYY-MM-DD") %>
---
# <% moment(tp.file.title,'W-YYYY').format("[Semaine n°]W") %>, [[Agenda/Mensuel/<% moment(tp.file.title, 'W-YYYY').format('YYYY/MMMM YYYY') %>|<% moment(tp.file.title, 'W-YYYY').format('MMMM') %>]] [[Agenda/Annuel/<% moment(tp.file.title, 'W-YYYY').format('[année ]YYYY') %>|<% moment(tp.file.title, 'W-YYYY').format('YYYY') %>]]

← [[Agenda/Hebdo/<% moment(tp.file.title, 'W-YYYY').subtract(7, 'd').format('YYYY/W-YYYY') %>|précédente]] | [[Agenda/Hebdo/<% moment(tp.file.title, 'W-YYYY').add(7, 'd').format('YYYY/W-YYYY') %>|suivante]] →
Du [[Agenda/Journal/<% moment(tp.file.title, 'W-YYYY').format('YYYY/MM-MMMM/YYYY-MM-DD-dddd') %>|<% moment(tp.file.title, 'W-YYYY').format('dddd D MMMM') %>]] au [[Agenda/Journal/<% moment(tp.file.title, 'W-YYYY').add(6, 'd').format('YYYY/MM-MMMM/YYYY-MM-DD-dddd') %>|<% moment(tp.file.title, 'W-YYYY').add(6, 'd').format('dddd D MMMM') %>]].

---
## Objectifs
<% tp.file.cursor() %>
### Tâches à réaliser
- [ ] 
### Notes importantes ou en cours d’écriture

## Résumé de la semaine