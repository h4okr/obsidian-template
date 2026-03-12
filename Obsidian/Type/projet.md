---
limit: 20
mapWithTag: false
icon: map
tagNames:
filesPaths:
bookmarksGroups:
excludes:
extends: racine
savedViews: []
favoriteView:
fieldsOrder:
  - TJblcx
  - kabN8o
  - 09tASI
  - NQWlE5
version: "2.7"
fields:
  - name: revue
    type: Date
    options:
      dateShiftInterval: 1 day
      dateFormat: YYYY-MM-DD
      defaultInsertAsLink: false
      linkPath: ""
    path: ""
    id: NQWlE5
  - name: maturité
    type: File
    options:
      dvQueryString: dv.pages('"Obsidian/Énumération/Littéraux"').where(x => x.énumération === "Maturité")
      customRendering: "`${page.file.name} (${page.valeur})`"
      customSorting: "this.app.plugins.plugins.dataview.api.page(a.path).valeur - this.app.plugins.plugins.dataview.api.page(b.path).valeur "
    path: ""
    id: 09tASI
  - name: priorité
    type: File
    options:
      dvQueryString: dv.pages('"Obsidian/Énumération/Littéraux"').where(x => x.énumération === "Priorité")
      customRendering: "`${page.file.name} (${page.valeur})`"
      customSorting: "this.app.plugins.plugins.dataview.api.page(a.path).valeur - this.app.plugins.plugins.dataview.api.page(b.path).valeur "
    path: ""
    id: kabN8o
  - name: parent
    type: File
    options:
      dvQueryString: dv.pages('!"Obsidian" and !"Agenda"').where(x => x.type === "projet")
    path: ""
    id: TJblcx
---
