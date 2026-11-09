# GMChess privacy policy

Privacy policy for the GMChess: Chess Analysis & Puzzles Android app (`com.gmchess.app`).

Last updated: 9 November 2026

## Summary

- **No account, no sign-up.** The app does not ask for your name, email or password.
- **Your games stay on your phone.** Games, analysis, puzzles, progress, coins and settings are stored only on your device. We do not run a server and never receive them.
- **Game import** sends the username you type to Chess.com or Lichess to download that player's public games.
- **Ads** are provided by Google AdMob, which may collect device information to show and measure ads. In the EU/UK you are asked for consent first. GMChess Premium subscribers see no ads.
- **GMChess Premium** is an optional subscription sold through Google Play. Google handles the payment; we never see your card, UPI or bank details.
- **Scanning a scoresheet** is optional. Only when you use it, the photo you take or pick is sent to Google's Gemini AI to read the moves (or read on your phone when you are offline).
- **Reminders** are local notifications scheduled on your phone; nothing is sent from a server.

## 1. Who we are

This policy explains how the Android app **GMChess: Chess Analysis & Puzzles** ("the app", "we") handles information. If you have any question about it, contact us at [gmchess.analysis.puzzel@gmail.com](mailto:gmchess.analysis.puzzel@gmail.com).

## 2. Information stored on your device

The app keeps its data in a local database on your phone:

- chess games you import, paste or open from a PGN file, and the usernames you import them for
- engine analysis of those games, run on your phone by the built-in Stockfish engine
- games you play on the phone (against Stockfish or with a friend) and positions you set up in the board editor
- puzzles made from your mistakes, the bundled puzzle collection, your puzzle rating and your progress
- your daily streak, coins, training plans, Puzzle of the day, your Premium status (as last confirmed by Google Play), settings and preferences

This data is not sent to us or anyone else. You can delete your games and reset puzzle progress in the app's Settings ("Delete all games", "Reset puzzles"). All of it is removed when you clear the app's data or uninstall the app. If Android backup is turned on for your phone, Android may include this data in your device backup.

## 3. Game import from Chess.com and Lichess

When you import games, the app sends the username you entered to the public API of the site you chose:

- **Chess.com** (api.chess.com) – [Chess.com privacy policy](https://www.chess.com/legal/privacy)
- **Lichess** (lichess.org) – [Lichess privacy policy](https://lichess.org/privacy)

These requests download publicly available games. As with any internet request, those services receive your device's IP address. The app does not log in to these sites and does not access any private account data.

## 4. Advertising (Google AdMob)

The free version shows ads from Google AdMob: a banner on some screens, an occasional full-screen ad between puzzles, and optional rewarded ads you can choose to watch to earn coins or unlock focus mode for the day. To show, limit and measure ads and to prevent fraud, Google may collect and process information such as:

- your device's advertising ID (Android Advertising ID)
- IP address and approximate location derived from it
- device and app information (model, operating system, language, app version)
- interactions with ads (views and taps) and diagnostic information about ad performance

This information is collected by Google, not by us; we only see aggregated reports (for example, how many ads were shown). Learn more in [How Google uses information from sites or apps that use its services](https://policies.google.com/technologies/partner-sites) and [Google's Privacy Policy](https://policies.google.com/privacy).

**Your choices:**

- If you are in the European Economic Area, the UK or Switzerland, the app asks for your consent before personalised ads are shown, using Google's consent message. You can refuse, and you can change your choice later.
- You can reset or delete your advertising ID, or opt out of personalised ads, in your phone's settings (*Settings → Google → Ads*, or *Settings → Privacy → Ads*, depending on your device).
- GMChess Premium subscribers are not shown ads.

## 5. Purchases: GMChess Premium (Google Play and RevenueCat)

GMChess Premium (no ads, unlimited hints, solutions and engine analysis) is an optional auto-renewing subscription sold through **Google Play Billing**.

- **Payment** is handled entirely by Google Play. The app never receives your card, UPI, bank or billing-address details. See [Google Payments privacy notice](https://payments.google.com/payments/apis-secure/get_legal_document?ldo=0&ldt=privacynotice).
- To confirm that your subscription is active (and to restore it on a new phone), the app uses **RevenueCat**. RevenueCat receives the purchase record from Google Play (which plan, purchase and expiry dates, a purchase token) linked to a random, anonymous app user ID created on your device. It does not receive your name or email. See [RevenueCat's privacy policy](https://www.revenuecat.com/privacy).
- You can cancel or change your subscription at any time in the Google Play Store (*Payments & subscriptions → Subscriptions*), or from the app's Premium screen.

## 6. Scanning a handwritten scoresheet (camera, photos, Google Gemini)

This feature is optional and only runs when you choose **Import → Scan scoresheet**:

- The app uses your **camera** to take a photo of your scoresheet, or lets you pick an existing photo. It does not access your camera or photos at any other time.
- When you are online, the photo is sent over an encrypted connection to **Google's Gemini API**, which reads the handwritten moves and sends the text back to the app. The photo is processed only to read the moves; we do not keep it on any server. Google processes it under the [Gemini API terms](https://ai.google.dev/gemini-api/terms); on the free tier Google may use submitted content to improve its services, so please do not scan sheets containing information you do not want to share.
- If you are offline, or Gemini is unavailable, the photo is read **on your phone** with Google ML Kit text recognition (provided by Google Play services) and nothing is sent.
- The moves read from the photo appear on a review screen for you to check before anything is imported.

## 7. Notifications

The app can remind you when the Puzzle of the day is ready and in the evening if your streak is about to end. These are **local notifications** scheduled on your phone; no server sends them and no data leaves your device for them. You can turn them off in the app (*More → Reminders*) or in your phone's notification settings.

## 8. Sharing and inviting friends

If you tap **Share** (for example on a game or the Puzzle of the day) or **Invite friends**, the app creates an image or message on your phone and hands it to the app you choose, such as WhatsApp or Instagram. We do not receive it; what happens next is covered by that app's privacy policy. **Report a bug** and **Rate us** simply open your email app or the Play Store.

## 9. Permissions

| Permission | Why the app uses it |
|---|---|
| Internet, network state | Ads, purchases, game imports, scoresheet reading |
| Camera | Only when you choose to photograph a scoresheet |
| Notifications | Puzzle of the day and streak reminders |
| Google Play Billing | GMChess Premium subscriptions |
| Advertising ID | Ads (Google AdMob) |
| Vibration, run at startup, keep awake | Haptic feedback, keeping reminders after a restart, keeping analysis running while the app is open |

The app does not use your microphone, contacts, precise location, call log or SMS. It only opens a file or photo that you pick yourself.

## 10. Data safety summary

This matches what we declare in the Google Play Data safety section.

| Data | Collected by | Purpose | Shared | Required? |
|---|---|---|---|---|
| Device or other IDs (advertising ID; random app user ID) | Google AdMob; RevenueCat | Advertising, analytics, fraud prevention; confirming Premium | AdMob: with Google's ad partners | Yes (ads) / only for subscribers |
| Approximate location (from IP address) | Google AdMob | Advertising | With Google's ad partners | Yes (ads) |
| App interactions (ad views and taps) | Google AdMob | Advertising, analytics | With Google's ad partners | Yes (ads) |
| Diagnostics / crash logs | Google AdMob | Ad performance and stability | No | Yes (ads) |
| Purchase history | Google Play; RevenueCat | Providing GMChess Premium | No | Only if you subscribe |
| Photos | Google Gemini (processed only to read moves, not stored) | App functionality: reading your scoresheet | No | Only if you scan a scoresheet |

All data is encrypted in transit (HTTPS). The app has no accounts.

## Delete your data

GMChess: Chess Analysis & Puzzles has no accounts and no server, so everything the app stores is on your phone and you can delete it yourself at any time:

- **Games and analysis:** open the app, go to *More → Settings* and tap *Delete all games*. This also removes the puzzles made from your mistakes.
- **Puzzle progress:** in *More → Settings*, tap *Reset puzzles*.
- **Everything at once:** uninstall the app, or open your phone's *Settings → Apps → GMChess → Storage → Clear data*. Games, analysis, puzzle progress, streak, coins and settings are all deleted immediately; nothing is kept.
- **Subscription:** cancel it in the Google Play Store (*Payments & subscriptions → Subscriptions*). To have your anonymous purchase record deleted from RevenueCat, email us and we will remove it.
- **Advertising data** collected by Google AdMob is held by Google, not by us. You can reset or delete your advertising ID in your phone's settings (*Settings → Google → Ads*, or *Settings → Privacy → Ads*), and manage your Google data at [myaccount.google.com](https://myaccount.google.com/data-and-privacy).
- **Scanned photos** are not stored by us. They are processed by Google Gemini only to read the moves.

Need help? Email [gmchess.analysis.puzzel@gmail.com](mailto:gmchess.analysis.puzzel@gmail.com).

## 11. Information we do not collect

We do not collect your name, email address, phone number, contacts, precise location, or payment card details. Photos are used only when you choose to scan a scoresheet, as described in section 6. The app has no analytics or crash-reporting service of its own and no user accounts.

## 12. Data sharing and selling

We do not sell your personal information, and we do not share it except as described above: the username you enter with Chess.com or Lichess for importing, device information collected by Google AdMob for ads, your purchase record with Google Play and RevenueCat if you subscribe, and a scoresheet photo with Google Gemini if you scan one.

## 13. Security

Requests to Chess.com, Lichess, Google (AdMob, Play, Gemini) and RevenueCat are made over encrypted connections (HTTPS). Data stored on your phone is protected by Android's app sandbox, so other apps cannot read it.

## 14. Children

The app is not directed at children under 13, and we do not knowingly collect personal information from children. If you believe a child has provided personal information through the app, contact us and we will help remove it.

## 15. Third-party content and credits

The bundled puzzles come from the [Lichess open puzzle database](https://database.lichess.org/#puzzles) (CC0). Analysis and the Stockfish opponent use the open-source Stockfish engine (GPLv3), running on your device. Handwriting is read by Google Gemini and, offline, Google ML Kit.

## 16. Changes to this policy

We may update this policy, for example when the app gains new features. The "Last updated" date at the top shows the latest version. Significant changes will also be noted in the app's release notes.

## 17. Contact

Questions or requests about this policy: [gmchess.analysis.puzzel@gmail.com](mailto:gmchess.analysis.puzzel@gmail.com)

© 2026 GMChess
