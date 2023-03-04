---
name: tab
about: tabのタグの拡張機能を追加する
title: 拡張機能の名称[tab]
labels: extension, tab
assignees: Katsuyuki-Karasawa

---

```json
{
	"name": "拡張機能の名前",
	"url": "https://github.com/@username/@reponame",
	"description": "拡張機能の簡単な説明",
	"added": "yyyy-MM-dd",
	"tags": [
		"tab"
	]
},
```
- `"name"` 拡張機能の名称  
- `"url"` 拡張機能のURL 直接拡張機能が反映されるディレクトリを指定してください  
- `"description"` 拡張機能の簡単な説明  
- `"added"` yyyy-MM-ddの形式でissueをpostした際の日付  

issueのタイトルを、拡張機能の名称(`"name"`)としてください。
拡張機能の検索も兼ねています。複数ある場合はどれか1つで構いません。
