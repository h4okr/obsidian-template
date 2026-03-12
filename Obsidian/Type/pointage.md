---
limit: 20
mapWithTag: false
icon: clock
tagNames:
filesPaths:
bookmarksGroups:
excludes:
extends: racine
savedViews: []
favoriteView:
fieldsOrder:
  - uR4Jwb
  - wArSGV
  - RtCKCe
  - dmgBDf
version: "2.5"
fields:
  - name: début
    type: DateTime
    options:
      dateShiftInterval: 10 minutes
      dateFormat: YYYY-MM-DD HH:mm
      defaultInsertAsLink: false
      linkPath: ""
    path: ""
    id: dmgBDf
  - name: fin
    type: DateTime
    options:
      dateShiftInterval: 10 minutes
      dateFormat: YYYY-MM-DD HH:mm
      defaultInsertAsLink: false
      linkPath: ""
    path: ""
    id: RtCKCe
  - name: pause
    type: Time
    options:
      dateShiftInterval: 5 minutes
      dateFormat: H[h]mm
      defaultInsertAsLink: false
      linkPath: ""
    path: ""
    id: wArSGV
  - name: durée
    type: Formula
    options:
      autoUpdate: false
      formula: 'current?.début != null ? moment.utc(moment.duration((current.fin ? moment(new Date(current.fin)) : moment()).diff(moment(new Date(current.début)))).subtract(moment.duration("PT" + (current.pause ?? "0h00").toUpperCase()+"M")).asMilliseconds()).format("H[h]mm") : null'
    path: ""
    id: uR4Jwb
---
