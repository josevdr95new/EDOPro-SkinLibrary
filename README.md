EDOPro-SkinLibrary
EDOPro-SkinLibrary is a collection of skins designed for the Yu-Gi-Oh! EDOPro game. All skins have been created by josevdr95. This library aims to enhance the visual experience of players by allowing them to customize the game interface with different styles.

🌟 Description
EDOPro is a Yu-Gi-Oh! card simulator that allows players to enjoy online matches with a customizable interface. This library offers a variety of skins that change the visual appearance of the game, adapting it to different themes and styles.

🎨 Features
Variety of Styles: Each skin has a unique design, inspired by different themes such as science fiction, eSports games, and anime.

Full Customization: The colors, backgrounds, and visual elements of each skin have been carefully designed to provide an immersive gaming experience.


| **Project**          | **Version** | **Date**        |
|----------------------|-------------|------------------|
| OGame                | v1.0       | 2024-12-16       |
| Dota 2               | v1.0       | 2024-12-17       |
| Naruto               | v1.0       | 2024-12-18       |
| Minecraft            | v1.0       | 2024-12-19       |
| Fortnite             | v1.0       | 2024-12-19       |
| Christmas            | v1.0       | 2024-12-19       |



## ⚙️ Toda la configs
```bash
{
	"repos": [
	    {
			"url": "https://github.com/josevdr95new/EDOPro-SkinLibrary",
			"repo_name": "josevdr95 edopro-skinlibrary",
			"repo_path": "./skin",
			"should_update": true,
			"should_read": true
		},
		{
			"url": "https://github.com/ProjectIgnis/DeltaPuppetOfStrings",
			"repo_name": "Project Ignis updates",
			"repo_path": "./repositories/delta-puppet",
			"has_core": true,
			"core_path": "bin",
			"data_path": "",
			"script_path": "script",
			"should_update": true,
			"should_read": true
		},
		{
			"url": "https://github.com/ProjectIgnis/LFLists",
			"repo_name": "Forbidden & Limited Card Lists",
			"repo_path": "./repositories/lflists",
			"lflist_path": ".",
			"should_update": true,
			"should_read": true
		},
		{
			"url": "https://github.com/ProjectIgnis/Puzzles",
			"repo_name": "Project Ignis puzzles",
			"repo_path": "./puzzles/Canon collection",
			"should_update": true,
			"should_read": true
		}
	],
	"urls": [
		{
			"url": "default",
			"type": "pic"
		},
		{
			"url": "default",
			"type": "field"
		},
		{
			"url": "default",
			"type": "cover"
		}
	],
	"servers": [
		{
			"name": "EU Central (Casual)",
			"address": "eu.projectignis.org",
			"duelport": 7912,
			"roomaddress": "eu.projectignis.org",
			"roomlistprotocol": "http",
			"roomlistport": 7923
		},
		{
			"name": "EU Central (Competitive)",
			"address": "eu.projectignis.org",
			"duelport": 7911,
			"roomaddress": "eu.projectignis.org",
			"roomlistprotocol": "http",
			"roomlistport": 7922
		},
		{
			"name": "US West (Casual)",
			"address": "us.projectignis.org",
			"duelport": 7911,
			"roomaddress": "us.projectignis.org",
			"roomlistprotocol": "http",
			"roomlistport": 7922
		},
		{
			"name": "US West (Competitive)",
			"address": "us.projectignis.org",
			"duelport": 7912,
			"roomaddress": "us.projectignis.org",
			"roomlistprotocol": "http",
			"roomlistport": 7923
		},
		{
			"name": "Asia Central (Casual/Competitive)",
			"address": "ignis-duel.ygopro.cn",
			"duelport": 44444,
			"roomaddress": "ignis-room.ygopro.cn",
			"roomlistprotocol": "https",
			"roomlistport": 443
		}
	],
	"posixPathExtension": "/usr/local/bin:/Library/Frameworks/Mono.framework/Versions/Current/Commands"
}

```