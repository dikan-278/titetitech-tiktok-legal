# Privacy Policy — Tí Te Tí Tech Dashboard (TikTok integration)

Last updated: 2026-11-07

This privacy policy covers a private, single-user analytics tool built and operated by the owner of the TikTok account `@tite_titech` ("the owner", "we", "the app"). It is not a public product and does not collect data from any user other than the owner.

## What data we access
After the owner signs in through TikTok Login Kit (OAuth2 with PKCE) and explicitly grants consent, the app requests these scopes:
- `user.info.basic` — the owner's open ID, display name, and avatar, used only to confirm which account is connected.
- `video.list` — the owner's own public TikTok videos and their public counters: view count, like count, comment count, share count, title, description, creation time, and share URL.

## What we do not access
The app does not access private messages, drafts, analytics of other accounts, follower lists, or any data beyond the owner's own public video metadata and public engagement counts.

## How the data is stored
- OAuth tokens (access token, refresh token) are stored only in a local file on the owner's own computer, never transmitted anywhere except directly to TikTok's official API endpoints over HTTPS.
- Video metrics fetched from the API are stored locally in the owner's own private analytics database, used to track the performance of their own content over time.
- No data is uploaded to any third-party service, advertising platform, or analytics vendor.

## Data sharing
We do not sell, rent, or share this data with any third party. The data is used exclusively by the account owner, for their own private review.

## Data retention and deletion
The owner can delete all locally stored tokens and metrics at any time by deleting the local data files. Revoking the app's access from TikTok's account settings immediately stops any further data access.

## Changes to this policy
The owner may update this policy as the app changes. The "Last updated" date above reflects the latest revision.

## Contact
For questions about this policy, contact the owner through the TikTok account `@tite_titech`.
