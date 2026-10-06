# Doodle Duel Privacy Policy

Effective date: 6 October 2026

This policy describes how the Doodle Duel Android game handles information. Doodle Duel is operated by the developer of this GitHub repository, VRVikramAditya243.

## Information used by the game

- **On your device:** The game stores your chosen display name and avatar, game preferences, muted or blocked players, a randomly generated guest identifier and secret, and local queue-performance records. The local queue-performance records do not include your display name, drawings, or device identifier. Clearing the app’s data removes this local information.
- **Online play:** When you join an online room, your display name, avatar, guest identifier, chat or guesses, and drawings may be sent to other players through Photon multiplayer services. Photon and its network providers may process connection information, such as IP address and technical diagnostics, to operate online play. Offline solo practice does not require an online room.
- **Player safety:** The app registers a randomly generated guest identifier with our HTTPS moderation service hosted on PythonAnywhere. The service stores a hash of the guest secret, not the secret itself. If you submit a report, we receive the reporter and reported-player identifiers, room and match details, player-name snapshots, the reason and explanation, and relevant chat or drawing evidence if included. Reports are reviewed by the game administrator; they do not automatically ban a player. The service also stores warnings or temporary suspension status and an audit of moderation decisions.

## Why we use it and who receives it

We use this information to provide multiplayer matches, show player profiles in rooms, support muting and blocking, review reports, and enforce game-safety decisions. Online room information is shared with other players in that room and processed by Photon. Moderation information is processed by PythonAnywhere as our hosting provider and is accessible to the game administrator. We do not sell this information or use it for advertising. The game currently contains no ads.

## Security and retention

The moderation connection uses HTTPS. The guest secret is kept on your device and sent to the moderation service for authentication; the service stores a hash of it. Access to the moderation review dashboard is restricted to the administrator. The game’s service database removes report evidence after 30 days and moderation-decision audit records after 180 days. Guest identifiers and current warning or suspension records may remain until deleted on request. Hosting-provider logs and backups may have separate retention periods.

## Your choices and deletion requests

You can change your display name and avatar in the app, mute or block other players, and clear local information by clearing the app’s data. Clearing app data does not automatically delete information already sent to the moderation service or other players. To ask about your information or request deletion of server-held information, [open a privacy request here](https://github.com/VRVikramAditya243/doodle-duel-privacy/issues/new). Do not post your guest secret, report details, or other sensitive information in a public issue; we will arrange a private way to verify and handle your request. Information needed for an active safety investigation may need to be retained for the periods described above.

## Changes and contact

We may update this policy when the game or its services change. The effective date above will be updated. For privacy questions, use the [privacy request page](https://github.com/VRVikramAditya243/doodle-duel-privacy/issues/new).
