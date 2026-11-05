# Doodle Duel Privacy Policy

Effective date: 6 November 2026

This policy describes how the Doodle Duel Android game handles information. Doodle Duel is published by KANDIBOINA JNANADEEP. This public policy is maintained in the VRVikramAditya243 GitHub repository.

## Information used by the game

- **On your device:** The game stores your chosen display name and avatar, preferences, muted or blocked players, a randomly generated guest identifier and secret, local queue-performance records, and game progress such as coins, skips, cosmetic unlocks, and ad-reward progress. Local queue-performance records do not include your display name, drawings, or device identifier. Clearing the app's data removes this local information.
- **Online play:** When you join an online room, your display name, avatar, guest identifier, chat or guesses, and drawings may be sent to other players through Photon multiplayer services. Photon and its network providers may process connection information such as IP address and technical diagnostics to operate online play. Offline solo practice does not require an online room.
- **Player safety:** The app registers a randomly generated guest identifier with our HTTPS moderation service hosted on PythonAnywhere. The service stores a hash of the guest secret, not the secret itself. If you submit a report, we receive the reporter and reported-player identifiers, room and match details, player-name snapshots, the reason and explanation, and relevant chat or drawing evidence if included. Reports are reviewed by the game administrator; they do not automatically ban a player. The service also stores warnings or temporary suspension status and an audit of moderation decisions.

## Ads and advertising data

Ad-enabled versions of Doodle Duel use Google Mobile Ads (AdMob) to show a banner on the Home screen and optional rewarded ads that you choose to watch for in-game benefits. An ad-supported version may be distributed for testing before live ads are enabled. The game does not need your room chat, drawings, player reports, or guest secret to request ads, and we do not send those items to AdMob ourselves.

When the ads SDK runs, Google may automatically collect and share your IP address (which may indicate approximate location), ad or app interactions (such as app launches, taps and ad views), diagnostic and performance information, and device or app identifiers including the Android advertising ID when available. Google uses this information for ad delivery, measurement, analytics, and fraud prevention. Google and its advertising partners may process it under their own policies. See [Google's Privacy Policy](https://policies.google.com/privacy) and [how Google uses information from apps that use its services](https://policies.google.com/technologies/partner-sites).

Where required, the game uses Google's User Messaging Platform to present an ad-consent message before requesting ads. You can review available ad privacy choices in the game's Settings. Your device's Android privacy settings may also let you reset or delete its advertising ID. Ads may be unavailable if required privacy choices cannot be completed. The game's current ad integration requests child-appropriate ad treatment and a G-rated maximum ad content setting; this limits ad serving but does not mean the game is designed for children under 13.

## Why we use information and who receives it

We use game information to provide multiplayer matches, show player profiles in rooms, support muting and blocking, review reports, save progress, and enforce game-safety decisions. Online room information is shared with other players in that room and processed by Photon. Moderation information is processed by PythonAnywhere as our hosting provider and is accessible to the game administrator. We do not sell player profiles, room content, or moderation reports to advertisers. Advertising data is handled by Google and its advertising partners as described above.

## Security and retention

The moderation connection uses HTTPS. The guest secret is kept on your device and sent to the moderation service for authentication; the service stores a hash of it. Access to the moderation review dashboard is restricted to the administrator. The service database removes report evidence after 30 days and moderation-decision audit records after 180 days. Guest identifiers and current warning or suspension records may remain until deleted on request. Hosting-provider logs and backups may have separate retention periods. Google and Photon may retain information according to their own policies. Ad data sent to Google is encrypted in transit by the Google Mobile Ads SDK.

## Your choices and deletion requests

You can change your display name and avatar in the app, mute or block other players, review available ad privacy choices in Settings, and clear local information by clearing the app's data. Clearing app data does not automatically delete information already sent to the moderation service, Photon, Google, or other players. To ask about your information or request deletion of server-held information, [open a privacy request here](https://github.com/VRVikramAditya243/doodle-duel-privacy/issues/new). Do not post your guest secret, report details, or other sensitive information in a public issue; we will arrange a private way to verify and handle your request. Information needed for an active safety investigation may need to be retained for the periods described above. For Google's data controls, see [Google's Privacy Policy](https://policies.google.com/privacy).

## Changes and contact

We may update this policy when the game or its services change. The effective date above will be updated. For privacy questions, use the [privacy request page](https://github.com/VRVikramAditya243/doodle-duel-privacy/issues/new).
