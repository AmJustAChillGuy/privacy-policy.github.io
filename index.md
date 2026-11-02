# 📜 Privacy Policy for AsTrazu

**Last Updated:** November 3, 2026

Thank you for choosing **AsTrazu**! Your privacy and trust are our highest priorities. This Privacy Policy outlines what information we collect, how it is processed and protected, and your rights regarding your data when interacting with our Discord bot, services, and associated systems.

We are committed to total transparency, data minimization, and strict compliance with the **Discord Developer Policy** and **Discord Developer Terms of Service**.

---

## 📌 1. What Data Do We Collect?

### A. Message Content
We only process message content in real time when strictly necessary to deliver requested bot functionality:
* **Security & Moderation Features:** Real-time heuristic scanning to detect and mitigate malicious links (anti-link), discord invite spam, raid/nuke exploits, and toxic behavior according to server configuration.
* **Command Processing:** Parsing message content for custom prefix commands (e.g., `Zdaily`, `Ztransfer`, `Zplay`, `Zwork`, `Zslot`, `Zkhlakhlouk`).
* **AI Conversations (Groq Integration):** When users directly invoke or interact with AsTrazu's AI chat features, the prompt text is transmitted to our secure inference gateway to generate a real-time reply.

> ➡️ **Zero Permanent Message Storage:** We **do not** log or permanently store raw message content. Messages are inspected in-memory in real time and are immediately discarded after processing.

---

### B. User and Server Metadata
To support persistent features like the economy system, user profiles, levels, and server security configurations, we store minimal metadata:
* **User Identifiers:** Discord User IDs, usernames, and avatar hashes (used for user profiles, economy balances, inventory, married soulmates, and moderation audit trails).
* **Server (Guild) Identifiers:** Discord Guild IDs, channel IDs, and role IDs (used to isolate server-specific configurations, anti-nuke thresholds, custom prefixes, and logging channels).
* **Voice State Data:** Ephemeral voice channel IDs and active guild playback states (stored purely in memory while music is playing; destroyed immediately when playback stops).

---

### C. Command Usage & Operational Metrics
* **Anonymized Command Statistics:** We collect anonymous usage counters (e.g., command frequency, latency, Lavalink connection status, and error logs).
* **Purpose:** To monitor bot uptime, optimize performance across Discord gateway shards, resolve software defects, and maintain system stability.
* **Privacy:** Operational logs never contain personal identifiable information (PII) or message contents.

---

## ⚙️ 2. How Do We Use Your Data?

We use collected data solely for operating, securing, and maintaining AsTrazu's built-in features:

1. **Prefix & Slash Commands:** Executing requested commands seamlessly (e.g., `Ztransfer @user 100`, `/play <song>`, `Zprofile`).
2. **Security & Anti-Nuke Defenses:** Real-time automated defenses preventing server nukes, channel deletions, mass-bans, unauthorized bot additions, and spam raids.
3. **Economy & Matrimony Systems:** Safely maintaining wallet balances, bank accounts, investments, inventory items, pet data, and marriage relationships.
4. **Music Streaming & Lyrics:** Streaming audio packets to your voice channel and displaying track titles, artists, and lyrics.
5. **System Stability & Bug Fixes:** Diagnostic evaluation of shards, database response times, and connection health.

---

## 🔐 3. Do We Store Your Data?

| Data Category | Stored Permanently? | Storage Method & Retention |
| :--- | :---: | :--- |
| **Message Content** | ❌ **No** | In-memory stream only. Discarded immediately after command/security scan. |
| **Economy & Profiles** | ✅ **Yes** | Stored in secure MongoDB database clusters encrypted at rest (AES-256). Retained while user/guild actively uses the bot. |
| **Server Security Settings** | ✅ **Yes** | Stored in MongoDB to maintain guild protection rules and log channels. |
| **Music Queues & Voice** | ❌ **No** | Temporary in-memory queue. Destroyed as soon as playback stops or the player leaves. |
| **Diagnostic Logs** | ⏱️ **Temporary** | Anonymized operational logs automatically rotated and permanently purged every 30 days. |

---

## 🔄 4. Can You Request Data Deletion?

**Yes.** You have the fundamental right to request complete deletion of all data associated with your Discord account or your Discord server.

### How to Request Deletion:
1. **Self-Service In-Bot Command:** Use the command `/deleteaccount` or `Zdeleteaccount` to purge your economy profile and user data instantly.
2. **Official Support Server:** Join our Discord Support Server at **https://discord.gg/JDEHYsYWBZ** and open a support ticket.
3. **Direct Email:** Contact the bot maintainer directly at **senghongly8828@gmail.com** with your Discord User ID or Server ID.

> ⚠️ **Notice:** Once deleted, account data (including coins, items, levels, streaks, and custom profiles) is permanently removed from all production databases and cannot be restored.

---

## 🤝 5. Do We Share Your Data?

**No.** We do not sell, rent, monetize, or trade your personal data with third-party advertisers or data brokers under any circumstances.

Data is only transmitted to trusted third-party infrastructure providers necessary to run the service:
* **Discord API:** To transmit commands, messages, embeds, and voice events.
* **MongoDB Atlas Cloud:** Dedicated secure cloud storage with encrypted volumes for persistent game and profile states.
* **Lavalink Audio Nodes:** Real-time audio streaming nodes to playback requested music.
* **Groq Cloud API:** Secure inference gateway used strictly for generating real-time AI replies when requested.

---

## 🤖 6. Do We Use Data for AI or Machine Learning?

**No.** We **do not** use your messages, voice, or user data to train, fine-tune, or develop artificial intelligence, machine learning models, or automated user profiling systems.

---

## 🚫 7. How Can You Opt Out?

* **Message Content Scanning:** Server administrators can configure AsTrazu's channel permissions to deny "Read Messages" / "View Channel" in channels where bot functionality is not required.
* **Economy & Profile Opt-Out:** Users can reset their profile bios via `Zsetbio reset` or delete their account data entirely using `/deleteaccount`.
* **Bot Removal:** Kicking or banning AsTrazu from your server stops all data processing for that server. Server owners may subsequently request database cleanup via support.

---

## 🔒 8. Data Security Standards

We implement strict, multi-layered security measures to protect stored information:
* **Encryption at Rest:** All persistent database storage uses AES-256 encryption.
* **Encryption in Transit:** All communications with Discord, databases, and external APIs are strictly enforced through TLS 1.3 / HTTPS.
* **Access Control:** Database credentials and bot tokens are restricted strictly to the verified lead developer via environment variable isolation.
* **Sanitization:** All inputs are strictly validated and sanitized to prevent injection attacks and memory leaks.

---

## 🔄 9. Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect new features, security improvements, or regulatory changes. 

Updates will be published transparently on:
* **Official Web Page:** [https://amjustachillguy.github.io/privacy-policy.github.io/](https://amjustachillguy.github.io/privacy-policy.github.io/)
* **In-Bot Commands:** Via the bot's `/privacy` and `/help` commands.

---

## 📬 10. Contact Information

If you have any questions, concerns, or privacy inquiries:
* **Discord Support Server:** [https://discord.gg/by9MHVEW9k](https://discord.gg/by9MHVEW9k)
* **Direct Email:** [senghongly8828@gmail.com](mailto:senghongly8828@gmail.com)
* **Developer User ID:** `144541606995820545`

---

✅ *AsTrazu is committed to providing a secure, engaging, and high-performance Discord experience while maintaining the highest standard of user privacy and transparency.*
