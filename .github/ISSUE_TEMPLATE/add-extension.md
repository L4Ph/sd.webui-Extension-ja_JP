---
name: add Extension
about: 拡張機能を追加する
title: 拡張機能をリストへ追加
labels: extension
assignees: Katsuyuki-Karasawa

---

```json
{
	"name": "拡張機能の名前",
	"url": "https://github.com/@username/@reponame",
	"description": "拡張機能の簡単な説明",
	"added": "yyyy-MM-dd",
	"tags": [
		"script",
		"localization",
		"tab",
		"training",
		"models",
		"UI related",
		"integrations"
	]
},
```
- `"name"` 拡張機能の名称  
- `"url"` 拡張機能のURL 直接拡張機能が反映されるディレクトリを指定してください  
- `"description"` 拡張機能の簡単な説明  
- `"added"` yyyy-MM-ddの形式でissueをpostした際の日付  
- `"tags"` [index.js](https://github.com/Katsuyuki-Karasawa/sd.webui-Extension-ja_JP/blob/main/index.json)を参照してください
