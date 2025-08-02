---
banner: "![[1373839.png]]"
---


```meta-bind-button
label: Daily Note
icon: ""
style: default
class: ""
cssStyle: "background-color:purple;"
backgroundImage: ""
tooltip: ""
id: ""
hidden: false
actions:
  - type: command
    command: daily-notes

```

```contributionGraph
title: 
graphType: default
dateRangeValue: 365
dateRangeType: LATEST_DAYS
startOfWeek: 0
showCellRuleIndicators: true
titleStyle:
  textAlign: left
  fontSize: 15px
  fontWeight: normal
dataSource:
  type: PAGE
  value: ""
  dateField: {}
fillTheScreen: false
enableMainContainerShadow: false
cellStyleRules: []

```

## Daily 

> [!daily]
> - Walk 
> - Add Missing Note
> - Add New Note (Mini Essay or Story)
> - Add Old Note from other Notebook Here 
> - Add New Resource 
> - Read

## Todo

> [!todo]  Today
> - [ ] The story of the Owl and the Crow
> - [ ] Make a Audio player for DND 
> - [ ] Clean my desk
 
> [!warning]  Run On
 >  - [ ] Finish Session planning 


> [!hint]  Long Term  
> - [ ] look at dual degree 
 
> [!summary] What I want to do
> - Figure out how everything will work when I am in school
> - Read The Inner Game of Tennis and The Art of Thinking

## Work In Progress 

```dataview
list from #Rough 
sort file.mtime desc
```

## Recent Files
```dataview
table file.name as "Recent Files", file.mtime as "Last Modified"
from ""
sort file.mtime desc
limit 15
```
