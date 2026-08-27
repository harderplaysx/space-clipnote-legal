# Privacy Policy for Space ClipNote

**Effective Date:** [INSERT DATE]
**Last Updated:** [INSERT DATE]

This Privacy Policy explains how Space ClipNote ("the Bot," "we," "us") handles information when you use it on Discord. It applies to all users who interact with the Bot, whether via direct message, the `/note` command, the `/list` command, or any button or menu the Bot presents.

This document is intended to be a clear, accurate, and complete description of the Bot's data practices. It is not a substitute for legal advice. If you are deploying this Bot at scale, commercially, or in a jurisdiction with specific regulatory requirements (such as GDPR in the EU/UK or COPPA in the US), you should have this policy reviewed by a qualified attorney before relying on it.

---

## 1. Who This Policy Covers

This policy applies to anyone who:

- Sends a direct message to the Bot
- Uses the `/note` slash command in a server or via a user-installed context
- Uses the `/list` slash command
- Interacts with any button (Edit, Delete, Share, Previous, Next) attached to a message the Bot has sent

If you do not interact with the Bot in any of these ways, the Bot does not process any information about you.

---

## 2. Data Controller

The Bot is developed and operated by an independent individual developer (the "Developer"). The Developer is the data controller for any processing described in this policy. Contact information is provided in Section 11.

---

## 3. What Information the Bot Collects and Processes

### 3.1 Note Content
When you send a direct message to the Bot, or use the `/note` command, the text you provide is processed **in order to generate a formatted response** (the "note" message with Edit, Delete, and Share buttons). This is the core function of the Bot.

### 3.2 Discord User and Message Identifiers
While processing a command or button interaction, the Bot temporarily has access to standard information that Discord provides to any bot as part of normal operation, including:

- Your Discord user ID
- The channel or DM ID the interaction took place in
- The message ID and content of the note being acted on (for Edit, Delete, and Share actions)

This information is used only to carry out the specific action you requested (e.g., confirming that you are the person who created a note before allowing you to edit or delete it).

### 3.3 Command Usage
When you run `/list`, the Bot reads recent message history in that specific DM channel to identify messages it previously sent that match the note format. This is a **live, on-demand read** — it happens only at the moment you run the command, and only within the channel where you ran it.

---

## 4. What Information the Bot Does NOT Collect

We want to be explicit about this, because it is central to how the Bot is designed:

- **The Bot does not maintain a database.** There is no persistent storage system — no SQL database, no file-based storage, no key-value store — that records your notes, your user ID, or your activity.
- **The Bot does not log note content to any external system.** Note text is not written to disk, sent to a logging service, or retained in memory after the request that used it has finished processing.
- **The Bot does not share data with third parties.** No note content, user ID, or usage data is sold, rented, or transmitted to advertisers, analytics providers, or any other third party.
- **The Bot does not use analytics or tracking services.** There is no telemetry, no usage-pattern tracking, and no behavioral profiling.
- **The Bot does not access message content outside of what you directly send it.** It does not read, scan, or monitor other messages in a server or DM beyond what is necessary to identify its own prior note messages when you run `/list`.
- **The Bot does not require or request personal information** such as your real name, email address, phone number, physical location, or payment information, and has no mechanism to collect any of these even if offered.

---

## 5. How "Storage" Actually Works

Because the Bot has no database, a "note" is not stored by the Bot in any independent sense. **The note *is* the Discord message itself.** When the Bot sends you a formatted note, that message is stored by Discord, subject to Discord's own Privacy Policy and Terms of Service, exactly like any other message you or anyone else sends on the platform.

This has a direct consequence: **if you delete the note (via the Delete button, or by deleting the message yourself), the data is gone.** There is no backup, archive, or secondary copy retained by the Bot.

---

## 6. The Share Feature

The Share button generates an image rendering of your note text, styled with the Bot's branding, for the purpose of letting you save or forward it outside of Discord.

- This image is generated **on demand, in server memory, at the moment you click Share.**
- It is sent directly back to you as a file attachment in an ephemeral (only-visible-to-you) message.
- The generated image is **not saved, cached, or retained** by the Bot after it is sent. It is not stored on disk and is not kept in memory beyond the single request that created it.

---

## 7. Hosting and Infrastructure

The Bot runs on third-party server infrastructure (a hosting provider) in order to remain online and responsive to Discord's servers. This means:

- The hosting provider may, as a routine and standard part of operating any server, have low-level infrastructure logs (such as connection timestamps or resource usage) that are generated automatically by the hosting platform itself, separate from anything the Bot's code does.
- The Developer does not use these infrastructure-level logs to extract, compile, or analyze note content or user behavior.
- If you have questions about a specific hosting provider's own infrastructure logging practices, you may wish to consult that provider's own privacy documentation.

---

## 8. Data Retention

Because the Bot does not independently store data, there is no separate retention period to disclose. Retention of note content is governed entirely by:

1. How long you choose to keep the note message before deleting it, and
2. Discord's own message retention and deletion policies, which are outside the Bot's control.

---

## 9. Your Rights and Choices

You are always in control of your data with respect to this Bot:

- **You can delete any note at any time** using the Delete button, which permanently removes the message.
- **You can stop using the Bot at any time** by simply not interacting with it. No account, sign-up, or opt-out process is required, because none exists.
- **You can revoke the Bot's authorization** to your Discord account at any time via Discord's own Authorized Apps settings, which immediately prevents the Bot from being used in your name going forward.

Because the Bot retains no independent copy of your data, there is no separate "data export" or "data deletion request" process needed beyond the above — deleting the message **is** the deletion of the data.

---

## 10. Children's Privacy

The Bot does not knowingly collect any personal information beyond what is described in this policy, and does not collect information sufficient to determine a user's age. The Bot's functionality (formatting and returning text you provide) does not differ based on age, and no age-gated or age-restricted content is generated or served by the Bot.

If you are a parent or guardian and believe a minor has provided information through the Bot that you believe should not have been processed, you may contact the Developer using the information in Section 11, though as described above, deleting the relevant message is generally sufficient to remove the data entirely.

---

## 11. Contact

For questions, concerns, or requests related to this Privacy Policy, you may reach the Developer at:

**[INSERT CONTACT METHOD — e.g., Discord support server, email, or contact form]**

---

## 12. Changes to This Policy

This Privacy Policy may be updated from time to time to reflect changes in the Bot's functionality or for legal and regulatory reasons. Material changes will be reflected by updating the "Last Updated" date at the top of this document. Continued use of the Bot after changes are posted constitutes acceptance of the revised policy.

---

## 13. Summary (Plain-Language Recap)

For clarity, here is a short, plain-language summary of the above. In the event of any conflict between this summary and the full text above, the full text governs.

- ✅ The Bot reads what you type to it, in order to format it back to you as a note.
- ✅ The Bot briefly uses your Discord ID and message ID to confirm you own a note before letting you edit/delete/share it.
- ✅ `/list` reads your DM history with the Bot live, at the moment you run it, to find your notes.
- ❌ The Bot does not have a database.
- ❌ The Bot does not log, save, or archive your notes anywhere outside the Discord message itself.
- ❌ The Bot does not share, sell, or transmit your data to any third party.
- ❌ The Bot does not track your usage, behavior, or activity over time.
- ❌ The Bot does not collect your name, email, location, or payment details.
- 🗑️ Deleting a note deletes the data. There is no backup.
