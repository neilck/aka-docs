---
sidebar_position: 1
---

# Introduction

AKA Profiles is a microservice/app for Nostr badges.

Badges are associated with Badge Award web pages, enabling qualified users to obtain the badge themselves.

As an example, it is common that apps require users to pass a Captcha to prevent bot signups/spam. With AKA Profiles, a user only has to pass a Captcha once, and the result is stored as a badge awarded to their account.

The user workflow is similar to OAuth.

1. Each app defines its group badge, specifying one or more badges from the badge library as eligibility requirements.
2. Users without required badges are directed from the app to AKA Profiles, where they can self-award badges based on respective badge award web pages.
3. Once all badges are awarded, the app's group badge is awarded, and the user is redirected back to the app.

To promote the re-use of badges, badges integrated with AKA Profiles can be re-used by multiple apps.
