# Année <% moment(tp.file.title,'[année ]YYYY').format("YYYY") %>

← [[Agenda/Annuel/<% moment(tp.file.title,'[année ]YYYY').subtract(1, 'Y').format('[année ]YYYY') %>|<% moment(tp.file.title,'[année ]YYYY').subtract(1, 'Y').format('YYYY') %>]] | [[Agenda/Journal/<% moment(tp.file.title,'[année ]YYYY').add(1, 'Y').format('[année ]YYYY') %>|<% moment(tp.file.title,'[année ]YYYY').add(1, 'Y').format('YYYY') %>]] →

---
<% tp.file.cursor() %>

---
## Mois par mois
![[Agenda/Mensuel/<% moment(tp.file.title,'[année ]YYYY').format('YYYY[/janvier ]YYYY[# janvier Agenda/Annuel/année ]YYYY YYYY') %>]]
![[Agenda/Mensuel/<% moment(tp.file.title,'[année ]YYYY').format('YYYY[/février ]YYYY[# février Agenda/Annuel/année ]YYYY YYYY') %>]]
![[Agenda/Mensuel/<% moment(tp.file.title,'[année ]YYYY').format('YYYY[/mars ]YYYY[# mars Agenda/Annuel/année ]YYYY YYYY') %>]]
![[Agenda/Mensuel/<% moment(tp.file.title,'[année ]YYYY').format('YYYY[/avril ]YYYY[# avril Agenda/Annuel/année ]YYYY YYYY') %>]]
![[Agenda/Mensuel/<% moment(tp.file.title,'[année ]YYYY').format('YYYY[/mai ]YYYY[# mai Agenda/Annuel/année ]YYYY YYYY') %>]]
![[Agenda/Mensuel/<% moment(tp.file.title,'[année ]YYYY').format('YYYY[/juin ]YYYY[# juin Agenda/Annuel/année ]YYYY YYYY') %>]]
![[Agenda/Mensuel/<% moment(tp.file.title,'[année ]YYYY').format('YYYY[/juillet ]YYYY[# juillet Agenda/Annuel/année ]YYYY YYYY') %>]]
![[Agenda/Mensuel/<% moment(tp.file.title,'[année ]YYYY').format('YYYY[/août ]YYYY[# août Agenda/Annuel/année ]YYYY YYYY') %>]]
![[Agenda/Mensuel/<% moment(tp.file.title,'[année ]YYYY').format('YYYY[/septembre ]YYYY[# septembre Agenda/Annuel/année ]YYYY YYYY') %>]]
![[Agenda/Mensuel/<% moment(tp.file.title,'[année ]YYYY').format('YYYY[/octobre ]YYYY[# octobre Agenda/Annuel/année ]YYYY YYYY') %>]]
![[Agenda/Mensuel/<% moment(tp.file.title,'[année ]YYYY').format('YYYY[/novembre ]YYYY[# novembre Agenda/Annuel/année ]YYYY YYYY') %>]]
![[Agenda/Mensuel/<% moment(tp.file.title,'[année ]YYYY').format('YYYY[/décembre ]YYYY[# décembre Agenda/Annuel/année ]YYYY YYYY') %>]]
## Trimestres
![[Agenda/Trimestriel/<% moment(tp.file.title,'[année ]YYYY').format('YYYY[/]YYYY[ Q1# Trimestre n°1 Agenda/Annuel/année ]YYYY YYYY') %>]]
![[Agenda/Trimestriel/<% moment(tp.file.title,'[année ]YYYY').format('YYYY[/]YYYY[ Q2# Trimestre n°2 Agenda/Annuel/année ]YYYY YYYY') %>]]
![[Agenda/Trimestriel/<% moment(tp.file.title,'[année ]YYYY').format('YYYY[/]YYYY[ Q3# Trimestre n°3 Agenda/Annuel/année ]YYYY YYYY') %>]]
![[Agenda/Trimestriel/<% moment(tp.file.title,'[année ]YYYY').format('YYYY[/]YYYY[ Q4# Trimestre n°4 Agenda/Annuel/année ]YYYY YYYY') %>]]