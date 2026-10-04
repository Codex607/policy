# TGADeveloper Privacy Policy

**Last updated:** October 4, 2026

This policy explains what data **TGADeveloper& Tga bot operated by WhoIam & Rdx-Samip S, collects and how it is used.

## 1. Data we store

**Server configuration**
- Server (guild) ID, the ID of the private configuration channel, and the optional organizer role ID.
- For each tournament: its name, prefix, settings (slot count, group size, required mentions, registration format), registration status, and the IDs of the category, channels and roles the Bot created.

**Registration and team data**
- Discord user IDs of the person who posted a registration and of the players they mentioned.
- Team names, slot numbers, team status (confirmed or cancelled), and timestamps.

**Registration logs**
- For each registration attempt in a tournament's registration channel: the user ID, message ID, outcome (success or denied), the reason, and the text of the message (truncated to 1,500 characters).
- Organizer actions such as manual additions, cancellations, and opening, pausing or closing registration, including the organizer's user ID.

## 2. Data we do not store
We do not store direct messages, messages posted outside a tournament's registration channel, email addresses, payment details, IP addresses, or voice data. The Bot receives message events from Discord in order to check the registration channel, but ignores and does not keep messages from other channels.

## 3. How we use data
Only to run the Bot's features: validating and recording registrations, assigning roles, building slot lists and groups, showing logs to organizers, and cleaning up after tournaments. We do not sell data, use it for advertising, or use it to train AI models.

## 4. Where data is stored and who can see it
Data is stored in a database on the server or computer where the Bot is hosted. The Bot's operator can access it. Registration logs are also posted to the private log channel of the tournament, visible only to the server's staff. Data is shared with Discord Inc. only as part of normal Bot operation through Discord's platform, and with our hosting provider **[HOSTING PROVIDER, if any]**. We do not share it with anyone else unless required by law.

## 5. Retention and deletion
- Running `/cleanup tournament` deletes that tournament's configuration, teams and player lists from the database.
- Registration logs are **kept** after cleanup, as a history of past events, until deleted on request.
- Removing the Bot from a server does not automatically delete its stored data.

To have your data or your server's data deleted, contact us (section 8) with the server ID or your Discord user ID. We will act on verified requests within a reasonable time.

## 6. Your rights
Depending on where you live, you may have the right to access, correct, or delete your personal data, or to object to its processing. Contact us and we will help where we can.

## 7. Children
The Bot is only available through Discord and is not directed to children under the minimum age Discord allows. If you believe a child's data was collected, contact us and we will delete it.

## 8. Contact
Privacy questions and deletion requests: **[YOUR EMAIL OR SUPPORT SERVER LINK]**

## 9. Changes
We may update this policy; the "Last updated" date will change when we do.
