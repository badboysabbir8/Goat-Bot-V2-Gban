# **Global Ban Storage Directory**

GoatBot stores global bans in a dedicated directory called Data-Gban-GoatBot-Project at the root level of the project. This directory contains ban files for each user who has been globally banned.

The forbidden file is an object containing multiple entries, each of which represents a banned user. Each entry has a unique identifier as its key and contains the reason for the ban, the proof (e.g. a screenshot), and the date of the ban. The proof is stored as an array of URLs pointing to the location of the proof files.

* `id`: the ID of the banned user
* `reason`: the reason for the ban
* `proof`: an array of URLs to proof of the ban
* `date`: the timestamp of the ban in ISO 8601 format
* **Here's an example ban file for a user with ID 123456789:**

```json
{
	"123456789": {
		"reason": "Spamming the chat",
		"proof": [
			"https://example.com/proof1.jpg",
			"https://example.com/proof2.mp4"
		],
		"date": "2023-04-02T12:12:12+0000"
	}
}
```
---

Any questions or complaints please contact with the information below:

[![Facebook](https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](https://www.facebook.com/ntkhang03)

[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/ntkhang03)

[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/ntkhang03)

[![Youtube](https://img.shields.io/badge/Youtube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@NTKhang03)

[![Github](https://img.shields.io/badge/Github-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ntkhang03)