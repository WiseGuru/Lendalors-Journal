```dataview
TABLE WITHOUT ID
embed(link(meta(char_token).path)),
file.link 
WHERE contains(tags, "faction_sep") AND !contains(char_condition, "Dead")
SORT file.name asc
```