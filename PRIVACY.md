# LofixBot Privacy Policy

Last updated: September 10, 2026

This policy explains how LofixBot processes data when installed in a Discord server or used through Discord interactions.

## Data Processed

LofixBot may process:

- Discord user, server, channel, message, and role identifiers
- Server configuration and feature settings
- User-submitted links, text, attachments, and media required to provide bot features
- Basic technical and error logs used for security, abuse prevention, and reliability

## Message Content

LofixBot does not use Message Content access for prefix commands. User-invoked features use Discord application commands.

Message Content access is used for automatic workflows that react when supported content is posted in configured guild channels:

- Social-media link detection, metadata extraction, and rich media embedding
- Song identification from supported links and audio or video attachments
- Edit-rating workflows for supported media links

LofixBot does not maintain a general archive of Discord message text. Message content is processed only to provide these features. It is not sold, used for advertising, or used to train machine-learning or AI models.

## User Choices

Users can manage automatic media processing with the /privacy command:

- /privacy opt-out prevents LofixBot from processing the user's future guild messages for automatic social-media embedding, song identification, and edit-rating workflows.
- /privacy opt-in enables those automatic workflows again.
- /privacy status shows the current setting.

The opt-out preference is stored so it remains active across restarts and servers. Opting out does not delete previously stored data or Discord messages. Users may request deletion using the process below. Slash commands remain available; data directly submitted through a slash command is processed to provide that requested feature.

## Storage and Retention

Temporary downloaded or converted media is removed after processing or when no longer required.

Some feature state, including user, channel, and message identifiers, supported media URLs, and rating state, may be stored in operational files until the related workflow is completed, cleanup occurs, or deletion is requested. LofixBot does not keep a general archive of message text.

## Third-Party Processing

Some requested features may transmit user-provided links, files, or media to service providers required to complete media downloading, conversion, metadata extraction, or audio identification. Data is shared only when needed to provide the requested feature and is subject to the service provider's own privacy terms.

## Data Not Collected

LofixBot does not collect passwords, payment-card information, private authentication credentials, or user presence and activity data. LofixBot does not record Discord voice-channel audio.

## Security

Access to stored configuration and operational data is restricted to the bot operator and the systems required to run LofixBot. Reasonable technical measures are used to protect data against unauthorized access, alteration, or disclosure.

## Data Deletion

Users and server administrators may request deletion of stored data associated with them or their server by emailing tqdm3842@gmail.com. Include the relevant Discord user ID and, for server-related requests, the server ID. Requests may require identity or server-ownership verification.

## Changes

This policy may be updated when LofixBot's features or data practices change. The current version and last-updated date will remain publicly available in this repository.

## Contact

For privacy questions or deletion requests, email tqdm3842@gmail.com.
