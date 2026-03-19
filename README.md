# Tiktok Top KOL Dataset

Explore millions of top TikTok KOLs (Key Opinion Leaders) with the highest follower counts using this comprehensive dataset. This dataset is designed for data analysis, influencer research, marketing insights, and AI applications.

> 🔗 https://huggingface.co/datasets/Tikfly/tiktok-top-kol

## 🤝 Sponsors
<div align="center">
  <a href="https://tikfly.io" target="_blank">
    <img src="https://github.com/tikfly/tiktok-top-kol-dataset/blob/main/tikfly.png" width="100" alt="tikfly">
    <div>
      <b>Tikfly</b> is the fastest and most stable Unofficial Tiktok API available. Provides seamless integration and reliable performance for all your Tiktok data needs. And don't need to use your cookie or worry about proxy.
    </div>
  </a>
</div>

## 🚀 Features
- 🌍 Millions of TikTok creators worldwide
- 📈 Rich metadata for each account
- 🔍 Suitable for analytics, ML models, and influencer discovery
- ⚡ Continuously updated (if applicable)


## 📦 Dataset Structure
Each record in the dataset represents a TikTok user with the following schema

```json
{
  "uid": "127905465618821121",
  "sec_uid": "MS4wLjABAAAAwAg0rSzO65WQfz4RzQgGv2Xdv108BgPXhRrrmNVIHQZ9PO8-flwwRtEppYTS0OjA",
  "nickname": "Khabane lame",
  "unique_id": "khaby.lame",
  "signature": "Se vuoi ridere sei nel posto giusto😎 If u wanna laugh u r in the right place😎",
  "region": "IT",
  "language": "en",
  "verified": true,
  "secret": false,
  "aweme_count": 1312,
  "total_favorited": 2565203524,
  "follower_count": 160303057,
  "following_count": 85,
  "favoriting_count": 6728,
  "unique_id_modify_time": 1773153889,
  "create_time": 1470866554
}
```

## 🧾 Field Description
| Field | Type | Description |
|------|------|------------|
| `uid` | string | Unique numeric identifier assigned by TikTok |
| `sec_uid` | string | Encrypted user ID for internal and API use |
| `nickname` | string | Display name |
| `unique_id` | string | Username (used in profile URL) |
| `signature` | string | User bio |
| `region` | string | Country/region code |
| `language` | string | Primary account language |
| `verified` | boolean | Verified account status |
| `secret` | boolean | Privacy status (true = private) |
| `aweme_count` | integer | Total number of videos |
| `total_favorited` | integer | Total likes received |
| `follower_count` | integer | Number of followers |
| `following_count` | integer | Number of accounts followed |
| `favoriting_count` | integer | Number of liked videos |
| `unique_id_modify_time` | integer | Username last modified (Unix timestamp) |
| `create_time` | integer | Account creation time (Unix timestamp) |

## 🛠 Use Cases
- 📊 Influencer marketing analysis
- 🤖 Machine learning & recommendation systems
- 📈 Social media trend analysis
- 🧠 Audience segmentation
- 🔎 Top creator discovery

## 📥 How to Use
Load dataset with Python (HuggingFace)

```python
from datasets import load_dataset

dataset = load_dataset("Tikfly/tiktok-top-kol")

print(dataset["train"][0])
```

## 📬 Contact
If you have questions, suggestions, or collaboration ideas
- Open an issue
- Or contact via your preferred channel

## ⚠️ Disclaimer
This dataset is intended for research and educational purposes only. Ensure compliance with TikTok’s terms of service when using the data. Do not use the dataset for unethical tracking or privacy violations.
