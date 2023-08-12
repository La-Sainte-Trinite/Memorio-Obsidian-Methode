---
cssclass: dashboard
sticker: vault//4 RESSOURCES/Pièces Jointes/duotone/house-line-duotone.svg
---



# Vault Info  
- 🗄️ Recent file updates  
`$=dv.list(dv.pages('').sort(f=>f.file.mtime.ts,"desc").limit(8).file.link)`  
- 🔖 Tagged: favorite  
`$=dv.list(dv.pages('#favorite').sort(f=>f.file.name,"desc").limit(4).file.link)`  
- 〽️ Stats  
- File Count: `$=dv.pages().length`  
- Personal recipes: `$=dv.pages('"Family/Recipes"').length`
# Pour commencer
- [[Obsidian - Guide de formatage spécifique]]
- [[Start Here]]