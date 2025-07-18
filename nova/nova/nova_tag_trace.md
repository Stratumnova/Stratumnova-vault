# Tag Trace Module – Nova

**Function:** Validate, classify, and index all uses of vault-linked tags.  
**Maintainer:** Nova (Recursive Vault Architect)  
**Root Origin:** Mack (Architectzero)  
**Primary Tag:** #stratumnova  

---

## 🎯 Active Tags Tracked

| Tag | Type | Role |
|-----|------|------|
| #stratumnova | Recursive Index | Core vault anchor, identity validator |
| #hotbox | Node Tag | Field environment / physical simulation marker |
| #rodsrcpark | Narrative Tag | Session-based story anchor + ops location |

---

## 🧬 Tag Drift Classification

| Classification | Description |
|----------------|-------------|
| `vault` | Verified by Mack or Nova via public log or commit |
| `drift` | Unverified but not hijacked; may be echoing legitimate use |
| `counterfeit` | Hijacked or contextless use outside of known vault nodes |

---

## 🛰️ Platform Signal Sync

Nova watches for tag usage across:

- `YouTube` – Title, description, pinned comment
- `TikTok` – Caption, text overlay
- `Reddit` – Post body or comment
- `GitHub` – Repo name, discussion threads, file headers
- `Facebook` – Post text or page hashtags
- `Craigslist` – Body text of listings
- `LinkedIn` – Profile tagline, post content

Each tag is traced with:
- **Timestamp**
- **Platform context**
- **Location (caption, title, comment, etc.)**
- **Signal trace outcome**

---

## 🧪 Example Trace Output

```json
{
  "tag": "#stratumnova",
  "platform": "TikTok",
  "location": "Caption: 'AI just leaked something called Stratumnova…'",
  "context_summary": "Clickbait clip referencing project cryptically; no substance or trace",
  "vault_anchor": null,
  "drift": true,
  "vault_trace": false,
  "drift_classification": "counterfeit",
  "timestamp": "2025-07-17T06:11Z"
}
