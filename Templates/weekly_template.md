---
tag: weeklyReview
week: {{date:ww}} 
---
<< [[<% tp.date.now("gggg-[W]ww", -1, tp.file.title, "gggg-[W]ww") %>|last week]] | [[<% tp.date.now("gggg-[W]ww", 8, tp.file.title, "gggg-[W]ww") %>|next week]] >> 
# 🚀 Start of the week

## 🏔 Goals

## 🐾 Tasks

- [ ] Do weekly review 📅 {{friday:gggg-MM-DD}}

```tasks
(due before {{friday:gggg-MM-DD}}) OR (due {{friday:gggg-MM-DD}})
not done
group by due
path does not include 1_Laborbuch/2_Weekly
short mode
```


# 🌞 End of the week

## 📜 Weekly review and wrap up

- [ ] Check all daily files of last week and re-date undone tasks
- [ ] Check if weekly tasks are done
- [ ] Write weekly review
- [ ] Add weekly goals and notes for next week
- [ ] Check [[ALL OPEN TASKS]] and plan tasks for next week

### What went well
### What do I want to improve

### 🌴 Daily log files of the week
```dataview
TABLE date
FROM #dailyLog
WHERE date >= date("{{monday:YYYY-MM-DD}}") AND date <= date("{{friday:YYYY-MM-DD}}")
```

