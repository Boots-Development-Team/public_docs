# Privacy Policy

**Effective date: October 12, 2026**

This policy explains what information is collected when you use this Discord bot (referred to as "the bot"), why it is collected, and what you can ask us to do with it. It applies to the bot's stored data and to the AI features it provides.

If you do not agree with this policy, please do not use the bot.

## 1. Who operates the bot

The bot is operated by its developer. The developer is the sole data controller for the information described in this policy.

**Contact:** r3tr00_ on Discord (`889871287453888532`)

## 2. What information we collect

We only collect what the bot needs in order to run, to moderate, and to power the features you use.

### Information Discord provides to us
When you interact with the bot, Discord supplies us with identifiers and metadata such as your user ID, username, server ID, channel ID, and the IDs of the messages you send. The bot does not receive your IP address or your email address.

### Information you deliberately give the bot
If you use these features, the content you provide is stored:

- **Quotes** — the message text you attach to a quote
- **Reminders** — the reminder text and the time you set
- **To-dos** — the task text you save
- **Server tags** — the text content of tags created
- **AFK status** — the reason you give for being away
- **AI conversations and memories** — the messages you send to the AI features, summaries the bot generates to keep long conversations coherent, and long-term notes the bot records about you

### Moderation information
The bot reads moderation channels to help track staff actions. This can include the name of the moderator, the person or account being actioned, the reason given, the punishment applied, and any notes or proof attached when a claim is reviewed. These records contain whatever free text staff wrote, and are treated as sensitive.

In addition, the bot's automated moderation reviews messages in monitored servers for scams, phishing and other rule-breaking content. When a message is flagged, an encrypted snippet of the flagged message is kept with the review record so staff can investigate it before deciding on a report.

### Activity information
To operate statistics and moderation tools, the bot records activity metadata. This includes which commands were used, reaction, voice and typing activity, join and leave events, nickname changes, role changes, message activity such as whether a message had attachments or embeds, and automod matches.

**The bot does not store the text of ordinary Discord messages for activity tracking.** Activity records capture identifiers, timestamps, and event types, not message bodies.

### Roblox account links
If you link a Roblox account, the bot stores that link and any verification status associated with it, along with moderation history tied to the Roblox account.

### Usage counters
If you use the AI features, the bot keeps a per-day count of how many AI messages you have used, so that daily limits can be enforced.

### Risk scoring
To support staff investigations, the bot computes advisory risk and anomaly scores for members from the records described above. These scores are estimates derived from activity metadata and moderation history, are accompanied by a numerical summary of the inputs used, and are never used to take an action automatically.

## 3. How we use your information

We use collected information to:

- Provide the features you request, such as reminders, to-dos, quotes, tags and AI replies
- Enforce daily usage limits and prevent abuse of AI features
- Support moderation, including reviewing moderation claims and maintaining records of staff actions
- Produce statistics about activity
- Protect the operation and security of the bot
- Comply with valid legal obligations and Discord's platform rules

We do not use your information for advertising or profiling for advertising. Automated and AI-generated output — such as moderation flags, background checks, investigations and risk scores — is advisory: it is reviewed by staff, and moderation actions that affect you are carried out by staff, never by an automated system alone.

We do not use message content or AI conversations to train machine-learning models. The bot's internal models are trained only on aggregated activity statistics and on bundled non-personal public datasets.

Where required by applicable law, we rely on your consent for features you opt into and on our legitimate interests in operating, moderating and securing the bot.

## 4. Encryption

Content that could contain your words — AI conversations and memories, quotes, reminders, to-dos, tag content, AFK reasons, moderation reasons and notes, flagged message snippets used for moderation review, command parameters, and matched automod content — is encrypted before it is written to storage, using authenticated encryption (AES-256-GCM).

Identifiers, timestamps, counters, event types, scores and status values are **not** encrypted, because they are required for indexing, joining and lookups. Separating them from content means that the most sensitive material is unreadable without the encryption keys.

Encryption keys are held separately from the stored data and are not stored in the database. If the keys are lost, encrypted content cannot be recovered.

## 5. Who else can see your information

- **Discord.** The bot operates on Discord and receives the information Discord provides in order to function. Your use of the bot is also subject to Discord's own Privacy Policy and Terms of Service.
- **NVIDIA.** AI features are provided using AI models hosted by NVIDIA. When you use an AI feature, the messages you send, any attachments you ask the bot to describe, and — for the investigation and background-check tools — summaries of stored records and public data may be transmitted to that provider so the feature can work. This information is sent for the purpose of completing your request only, and may be processed on servers located outside your country.
- **Search.** Web-search tools run through the bot's self-hosted search service, which forwards queries to public search engines to return results. Queries are sent only when a search feature is used and are not used for profiling.
- **Service providers and legal authorities.** We may disclose information if we believe in good faith that it is required by law, necessary to protect the safety of the bot, its users, or the public, or necessary to comply with a valid legal process.

We do not sell your information. We do not share it for anyone else's marketing.

## 6. Data retention

We keep information for as long as the bot is operating and the information is needed for the purpose it was collected, and we review the information we hold periodically so it is not kept longer than needed.

- Activity records, AI conversations, AI memories, quotes, reminders, to-dos, tags, and moderation records are retained until you or a server administrator request deletion.
- Per-day AI usage counters accumulate one entry per day you use the AI features; entries are kept only while needed to enforce daily limits and are pruned as they age.
- The bot takes a daily database backup and retains only the most recent backup.

Because a backup is retained, information deleted on request may still be present in that backup until it is replaced by the next backup. Backups are not restored for ordinary operation.

## 7. Your choices and rights

Depending on where you live, you may have rights to access, correct, export, or delete personal information we hold about you, and to object to or restrict certain processing.

You can exercise these rights by contacting us. In particular you may ask us to:

- Provide a copy of the information we hold about you
- Correct information that is inaccurate
- Delete information we hold about you
- Delete information held for you within a server, where you have the authority to request that

If you are the subject of a staff background check or investigation carried out with the bot, you can exercise these same rights for the information compiled about you.

To request deletion of information tied to a specific Discord account, provide the account's user ID and state clearly that you want the data deleted. If you are not the account holder, we will ask you to demonstrate that you are a server administrator for that account before acting.

Deletion is carried out by the operator rather than automatically, and is limited to information associated with a single account. It does not remove records that are the operator's own actions, such as entries the operator made as a moderator.

We will verify requests before acting on them. We will acknowledge requests promptly and complete them as soon as reasonably practicable. We may decline a request where we are legally required to retain the information.

## 8. How we protect information

- Sensitive content is encrypted at rest as described in section 4.
- Access to stored data, encryption keys and configuration is limited to the developer.
- The bot's internal automated tooling is prevented from reading files that hold secrets, credentials, logs or database backups.
- Where the bot's automated tooling queries stored data, encrypted fields are withheld from the result rather than being exposed.

No method of transmission or storage is completely secure. We take reasonable steps to protect data, but we cannot guarantee absolute security.

## 9. Children

The bot is not directed at children under 13, and we do not knowingly collect information from children under 13. Discord sets its own minimum age requirement for using its platform, and users are responsible for complying with it. If you believe a child under 13 has provided information to the bot, contact us and we will delete it.

## 10. Changes to this policy

We may update this policy as the bot changes. The effective date at the top of this page shows when it was last changed. If a change materially affects how information is used, we will make that apparent through the bot's normal channels.

## 11. Contact

Questions, requests and complaints about this policy or about your information can be sent to:

**r3tr00_ on Discord — `889871287453888532`**
