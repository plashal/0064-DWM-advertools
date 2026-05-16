---
type: projects
title: advertools
project-id: '0064'
client_abbrev: DWM
client_name: Dew Wealth Management
description: Advertools (fork)
status: archived
priority: normal
version: 0.1.0
dateCreated: 2026-02-24T00:00
dateModified: '2026-05-16T00:06:24Z'
domain: dwm
monday-item-id: 11449887660 - monday
focus-areas: []
visibility: private
publish-target: none
publish-ready: false
tags:
- DWM
- pid-0064
- projects
notion-project-id: 3121bbea-44ec-817f-9156-c844c017fba2
notion-project-url: https://www.notion.so/3121bbea44ec817f9156c844c017fba2
---
# advertools

## Objective

# Project: advertools

## Overview

Advertools (fork)

## Tasks

```dataview
TABLE WITHOUT ID
  file.link as "Task",
  status as "Status",
  priority as "Priority",
  due as "Due"
FROM "TaskNotes/Tasks"
WHERE project-id = this.project-id
SORT choice(status = "in-progress", 0, choice(status = "open", 1, choice(status = "waiting", 2, 3))) ASC, priority DESC
```
