

# Daily note/2025-06-21

---
exercise: true
study_time_hours: 10
---

install plugin dataview and contribution graph

# Tracker
```contributionGraph
title: 🎨 Work
graphType: default
dateRangeValue: 365
dateRangeType: LATEST_DAYS
startOfWeek: "1"
showCellRuleIndicators: true
titleStyle:
  textAlign: left
  fontSize: 15px
  fontWeight: normal
dataSource:
  type: PAGE
  value: '"Daily note"'
  dateField:
    type: FILE_NAME
  countField:
    type: PAGE_PROPERTY
    value: Working_hours
fillTheScreen: false
enableMainContainerShadow: false
cellStyleRules: []
cellStyle:
  minWidth: 10px
  minHeight: 10px

```
```contributionGraph
title: 💪Exercise
graphType: default
dateRangeValue: 365
dateRangeType: LATEST_DAYS
startOfWeek: "1"
showCellRuleIndicators: true
titleStyle:
  textAlign: left
  fontSize: 15px
  fontWeight: normal
dataSource:
  type: PAGE
  value: '"Daily note"'
  dateField:
    type: FILE_NAME
  countField:
    type: PAGE_PROPERTY
    value: exercise
fillTheScreen: false
enableMainContainerShadow: false
cellStyleRules:
  - id: Halloween_d
    color: "#d94e49"
    min: 5
    max: "2"
cellStyle:
  minWidth: 10px
  minHeight: 10px

```
