[[+Home]] %% tags:: #MOC %% 

# Meetings MOC
Meetings are timestamped events with other people, where information is exchanged and collected. Meeting notes are intrinsically ephemeral. They're stored in a separate Space than other Umami notes (`_timestamps/meetings`) and rarely reviewed. If there's information in a meeting that needs to be accessed later, it should be moved into a more evergreen note in the Umami folder. 

**Template:** [[tpl_meeting]]

```button
name New Meeting
type note(_timestamps/meetings/TKTK) template
action Template, Meeting
templater true
```

```button
name New Meeting
type note(/_timestamps/meetings/TKTK) template
action tpl_meeting
templater true
```
^button-9hy9
## Meeting Notes

```dataview
TABLE file.cday as Created, summary
FROM "_timestamps/meetings" and -#MOC
SORT file.cday DESC
```
