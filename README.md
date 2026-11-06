# Life on 11 launch package

Mobile-first static web app prototype for Life on 11.

## Launch features in this build
- Podcast listening experience connected to the Transistor RSS feed.
- New **The Volume** section for weekly Friday articles.
- Article author selector for Jon or Jeremy in the admin preview.
- Blog articles display without reader comments.
- Existing Grow, Resources, and Profile areas retained.

## Important production notes
- The current admin publishing workflow is a local prototype only. It stores articles in the browser's local storage and does not sync between Jon and Jeremy.
- Before public launch, add secure individual administrator authentication and a shared database/CMS so both hosts can publish from their own devices.
- Reader accounts are not required for the planned launch.
- Push notifications require a service worker, user opt-in, and a server-side push service. iOS users must add the web app to their Home Screen and grant permission.
- Podcast audio remains hosted by Transistor.
