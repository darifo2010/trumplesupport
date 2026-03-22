---
layout: default
title: Privacy Policy — Trumple
---

# Privacy Policy for Trumple

**Last updated:** March 22, 2026

## 1. Information We Collect

**Authentication:** Trumple requires Apple Game Center sign-in to play. We receive your Game Center player identifier, display name, and a cryptographic signature from Apple to verify your identity. We do not collect your Apple ID, email address, or password.

**Player Profile:** We store your chosen display name and avatar selection on our servers.

**Game Statistics:** We track gameplay statistics such as games played, games won, tricks won, bid accuracy, win streaks, and scores. These stats are used to report achievements and leaderboard scores to Apple Game Center.

**Device Information:** We collect an anonymous device identifier solely for app functionality purposes. We do not use this identifier for advertising or tracking across other apps.

**Local Preferences:** We use on-device storage (UserDefaults) to save your app preferences such as sound and volume settings.

**Voice Chat:** When you use voice chat in online games, your microphone audio is transmitted in real time to other players in your lobby via LiveKit (a third-party audio server). Voice audio is streamed live and is not recorded or stored by us or by LiveKit. Microphone access requires your explicit permission and can be revoked at any time in iOS Settings.

**In-App Purchases:** Trumple uses Apple's StoreKit 2 for in-app purchases (game type unlocks and Trumple+ subscription). Purchase receipts are cryptographically verified on our server to confirm entitlements. We store your purchase status (which game types are unlocked and subscription expiry) on our servers. We do not receive or store your payment details — all payment processing is handled by Apple.

## 2. How We Use Your Information

- To authenticate you and maintain your game account
- To enable real-time multiplayer gameplay
- To transmit voice chat audio between players in your lobby
- To track your game statistics and progress
- To report achievements and leaderboard scores to Apple Game Center
- To verify and restore your in-app purchases across devices
- To restore your profile when you return to the app

## 3. Data Storage and Security

Your data is stored on Supabase (hosted on AWS). Game state and player data are protected by row-level security policies that prevent players from accessing other players' private information (such as card hands). Spectators can watch games but cannot see any player's hand. All communication between the app and our servers is encrypted via HTTPS.

## 4. Third-Party Services

- **Apple Game Center** — Authentication, achievements, and leaderboards (subject to [Apple's Privacy Policy](https://www.apple.com/legal/privacy/))
- **Supabase** — Database and real-time multiplayer infrastructure (hosted on AWS)
- **LiveKit** — Voice chat audio streaming (audio is transmitted live, never recorded or stored)

No analytics, advertising, or tracking SDKs are used.

## 5. Data Sharing

We do not sell, rent, or share your personal information with third parties. Your gameplay statistics are reported to Apple Game Center for achievements and leaderboards. Voice audio is transmitted directly between players and is not stored.

## 6. Data Retention

Your player profile and statistics are retained as long as your account is active. Game and lobby data older than 30 days is automatically deleted. You may request deletion of your account and associated data by contacting us at the email below.

## 7. Children's Privacy

Trumple does not knowingly collect personal information from children under 13. Game Center authentication is managed by Apple and subject to parental controls.

## 8. Changes to This Policy

We may update this privacy policy from time to time. Changes will be reflected by the "Last updated" date above.

## 9. Contact Us

If you have questions about this privacy policy or wish to request data deletion, please use the form on our [Contact & Support](contact) page.
