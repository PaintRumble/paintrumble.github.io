# Paint Rumble Privacy Policy

**Effective date:** November 12, 2026

## 1. Who we are and what this policy covers

Paint Rumble (the "game", published as Paint.io until November 2026) is a territory game for iPhone and Android, made by Gary Lam ("we", "us"). You can reach us at **paintrumble@gmail.com**; that email is our only contact point.

This policy explains what the game stores, what leaves your device, who receives it and what you can do about it. The short version of how the game is built:

- There is no account and no login of our own, and we run no server of our own.
- The game uses one analytics tool, Google Analytics for Firebase, to measure how rounds and sessions go, and for some play sessions it also keeps a recording of how the rounds were played and which buttons were pressed (section 2b), so we can make the game better to play. Neither knows who you are. If the game crashes, Firebase Crashlytics sends a crash report (section 2c) so we can fix it. There is no social feature. The rivals you play against are controlled by the computer.
- We advertise the game on Facebook and Instagram. So that we can tell whether those ads work, the game includes software from Meta that tells Meta when the game was installed and when it is opened (section 2d). It is used for nothing else: there is no Facebook login and no sharing to Facebook.
- The game shows ads from one company, Google AdMob, and Google's ad software collects data about your device while it does.
- Your progress can be saved to your own iCloud or Google Play Games account, which we cannot read (section 4).

## 2. Who receives data

| Recipient | What | Why |
|---|---|---|
| Google AdMob | Ad data: your advertising ID and other device identifiers, IP address and approximate location, ad interactions, and device and app information | Showing and measuring ads |
| Google Analytics for Firebase | Usage data: how rounds and play sessions go (for example how long a round lasted, how it ended, how it was played, which rivals were dealt, whether you played again), which screens and shop shelves you open and for how long and which looks you try on, which avatar you play and how far you have levelled it, missions, unlocks and settings changes, and whether you shared the game from the invite and to which kind of app (for example "messages" or "whatsapp"; never who you sent it to); a random app-instance identifier made by the analytics software; device and app information; IP address and approximate location. The advertising ID is **not** collected for analytics, and we set no user identifier | Measuring and improving the game: seeing what keeps rounds fun and tuning the rivals and missions you are dealt (section 2a) |
| Firebase Crashlytics | Crash reports (section 2c): what the game was doing when it crashed (the code's call stack and log lines), the device model, OS and app version, and a random installation identifier made by Crashlytics | Finding and fixing crashes |
| Google Cloud Storage for Firebase (our storage) | Session recordings (section 2b): how the rounds of a play session went and which menu buttons were pressed, under a random recording identifier; the IP address of the upload | Finding out why players stop playing and improving the game |
| Meta Platforms (Facebook, Instagram) | Install measurement (section 2d): that the game was installed and when it is opened; device and app information (model, OS and app version, language, time zone, screen size and similar); IP address; identifiers made by Meta's software for the app; technical reports about Meta's own software (its settings, and crashes inside it); your advertising ID, on iPhone only if you chose Allow tracking, on Android unless you have deleted it. On iPhone, Apple's SKAdNetwork also tells Meta that an install followed one of our ads, without saying whose | Measuring our own ads for the game on Meta's apps, and letting Meta show those ads to people likely to install it |
| Apple (iPhone) | Your iCloud save; purchases; Game Center sign-in | Cloud save, Remove ads, choosing the right ads |
| Google Play (Android) | Play Games sign-in (your player name and ID); your Saved Game; purchases | Cloud save, Remove ads |

### Sharing the game

After a good round the game may invite you to share it with friends. Sharing opens your phone's own share sheet with a short message and a link to the game on the App Store (from an iPhone) or Google Play (from an Android phone). You choose the app and the people; the game never sees your contacts, who you sent it to, or what you wrote, and never sends anything itself. Your phone tells the game only whether the share went through and which app you picked, which the game uses to count shares towards a coin prize (saved with your progress, section 4) and reports to Google Analytics for Firebase as a kind of app (section 2). The invite is never shown to a child account.

### 2a. How the game adapts to you

The game keeps a small record on your device of how your recent rounds went and what you did at the end of each (played again, went home, or left the game). It uses that record to deal your next round: which computer rivals are near you at the start, how gentle or lively the lobby is, and later which missions you get. The record is part of your save (section 4), so it syncs with your progress. It never changes a round while you are playing it, and it never changes your own speed or controls. Delete my data clears it.

A copy of the same facts goes to Google Analytics for Firebase as events, with the settings we used for that round, so we can see whether the adaptation works and tune it. Settings for the adaptation can be delivered to the game by Firebase Remote Config, which sends the game's version, language, country and time zone to Google to do so.

### 2b. Session recordings

For some play sessions (at present most of them; later a small share for players who have played a while), the game records what happened so we can replay it and see where the game was confusing, too hard or not fun:

- **in rounds:** the round's starting conditions, your steering, where every player was each second, what was captured, who was knocked out and how the round ended;
- **in the menus:** which screen was up, which button you pressed and where on the screen, when sheets opened and closed and how far you scrolled the shop, with the time since the session began.

A recording is stored under a random identifier made for that session. It is not your analytics identifier, your advertising ID or your device identifier, and we cannot link it to you or to your other sessions. It contains no name, account, location or device details. The game writes it on your device and sends it to our storage at Google (Cloud Storage for Firebase) when you leave the game; a recording that can't be sent waits on your device for the next time. Nothing in it changes how the game plays.

The game never records players Game Center reports as children.

### 2c. Crash reports

If the game crashes, Firebase Crashlytics records what the game was doing at the moment (the code's call stack and recent log lines), the device model, OS and app version, and a random installation identifier Crashlytics makes, and sends it the next time the game starts. It is used only to find and fix crashes. It is collected only when analytics is (never for players Game Center reports as children); reports saved while collection is off are deleted, not sent later. Delete my data deletes any report not yet sent.

### 2d. Install measurement (Meta)

We pay for ads for Paint Rumble on Facebook and Instagram. To know whether an ad led to an install, the game includes Meta's software (the Facebook SDK), set up to do one job: it tells Meta that the game was installed and each time it is opened. Meta's software also sends Meta technical reports about itself (which of its settings are on, whether you answered Apple's tracking prompt, and crashes inside Meta's software). We send Meta nothing about how you play, what you unlock or what you buy, and the game has no Facebook login, friends list or sharing to Facebook.

With that signal Meta receives technical details about the device and app (section 2), your IP address and, where allowed, your advertising ID: on iPhone only if you chose Allow tracking in Apple's prompt, on Android unless you have deleted it in your Google ad settings (resetting it only gives you a new one). If Meta recognises the advertising ID, it can connect the install to a Facebook or Instagram account and use it under its own privacy policy, including for advertising. Without the advertising ID, installs on iPhone are counted through Apple's SKAdNetwork, which reports totals and never who installed.

Meta's software is not started for players Game Center reports as children: on iPhone the game waits for Game Center's answer first (up to 20 seconds; with no answer by then it treats you as 13 or over, as it does for ads), and if Game Center says so later, Meta's software is switched off for the rest of that launch. Where the game shows Apple's tracking prompt, Meta's software starts only after you have answered it; if you bought Remove ads the game never shows that prompt, and Meta's software then runs without your advertising ID. **Delete my data** switches it off for the rest of that launch. To stop your advertising ID being used, choose "Ask App Not to Track" on iPhone or delete your advertising ID in Android's settings; you can also manage how Meta uses data from other apps in your Facebook or Instagram settings ("Your activity off Meta technologies").

### Other recipients

We show ads from no ad network other than Google AdMob, and use no mediation partners. Others who take part in showing ads through Google's systems may also receive limited data, under Google's rules. We may disclose information if the law requires it.

## 3. Purchases

"Remove ads" is bought through Apple or Google. They handle payment, and we never see your payment details. The game keeps a local note on your device that the purchase succeeded. Apple or Google keep the purchase record, and you can restore it through their systems.

## 4. Cloud save

- **iPhone:** progress, including the device identifier, is stored in iCloud key-value storage under your Apple ID. It does not require Game Center.
- **Android:** when you are signed in to Google Play Games, a Saved Game with your progress is stored in your Google account. Sign-in can happen automatically for returning players; you can sign out in Play Games.

These copies are held by Apple or Google under their own policies, and we cannot read them. Nothing syncs between iPhone and Android.

## 5. How long data is kept

| Data | How long |
|---|---|
| On your device | Until you use Delete my data (for progress) or uninstall the game |
| Cloud save | Until you delete it in your Apple or Google account; uninstalling does not remove it |
| Ad data held by Google | Under Google's own retention rules |
| Analytics events | Up to 14 months tied to the app-instance identifier in Google Analytics; we may keep an export of the events for longer to study them, and aggregate reports indefinitely |
| Crash reports | Kept by Google for 90 days (Crashlytics' own retention) |
| Install measurement held by Meta | Under Meta's own retention rules |
| Session recordings | Kept as long as they help us improve the game; older ones move to cheaper storage. They can't be linked to you, so they can't be found or deleted on request |
| Emails you send us | Only as long as needed to answer you and keep a record of your request |
| Other data held by us | None: we keep no copy of players' progress or ad data beyond the analytics and session recordings above |

## 6. Security

We do not run servers or keep player data, other than emails you send us, the analytics events Google holds for us and the session recordings in our Google Cloud storage. Progress sits in your phone's app storage and in your own iCloud or Google account, protected by Apple's and Google's systems. No system is perfectly secure, and the security of Google's ad and analytics data is Google's responsibility, and that of the install measurement data is Meta's.

## 7. Where data goes

We transfer no data ourselves. Google may process ad and analytics data and session recordings in the United States and other countries, under its own safeguards. Apple and Google may do likewise with cloud saves, and Meta with install measurement data.

## 8. Your choices and rights

**In the game.**
- **Settings > Privacy and ads > Delete my data** resets your progress on this device and replaces your cloud save with an empty one (this needs a connection and takes effect when it syncs).
- It also gives the game a new analytics identifier, so events sent before are no longer connected to events sent after. It does **not** clear the device identifier, the Remove ads note, your sound, vibration and minimap settings, or any choice you made in Google's form or Apple's tracking prompt. Those stay until you uninstall. It does **not** delete your Apple, Google or Play Games account, the purchase record, data Google holds for ads, or analytics events already sent.
- It also switches off Meta's install measurement (section 2d) for the rest of that launch. It does not delete what Meta already received.
- It also deletes any session recordings still waiting on this device and stops recording for the rest of that launch. It does not delete recordings already sent (they can't be linked to you).
- **Settings > Privacy and ads > Change** adjusts ad personalisation.

**Elsewhere.** To remove the saved game itself, use your iCloud storage settings or Play Games settings. To manage data Google holds for ads, use Google's own controls and, on iPhone, Apple's Tracking setting. To manage what Meta holds, use your Facebook or Instagram settings (section 2d).

**Access and correction.** We hold no profile that identifies you: the analytics events carry only a random identifier, and session recordings a different random identifier per session, that we cannot connect to a person, so we cannot look up or hand over "your" events. You can email us for help or to make a request. We may need to point you to Apple or Google where they hold the data.

### US state privacy rights

Some US states' laws treat personalised ads as "targeted advertising", "sharing" or "sale" of personal information. Personalised ads, and telling Meta about an install together with your advertising ID (on iPhone if you choose Allow tracking; on Android by default), may count as that, so these rights apply to you if you live in such a state:

- **Categories made available to Google AdMob:** identifiers (advertising ID, device identifiers, IP address); internet or other network activity (ad interactions, device and app information); approximate geolocation.
- **Categories made available to Google Analytics for Firebase:** identifiers (a random app-instance identifier, IP address); internet or other network activity (how you play and which screens you use, device and app information); approximate geolocation. We use it to measure and improve the game, not for advertising.
- **Categories made available to Meta (install measurement, section 2d):** identifiers (advertising ID where allowed, identifiers made by Meta's software, IP address); internet or other network activity (that the game was installed and opened, device and app information). Used to measure and deliver our own ads for the game.
- **Crash reports (Firebase Crashlytics):** device information, a random installation identifier, diagnostic data. Used to fix crashes, not for advertising, not sold or shared.
- **Session recordings (held by us, at Google):** internet or other network activity (how you played and which buttons you pressed); IP address at upload. Used to improve the game, not for advertising, not sold or shared.
- **Purposes:** showing and measuring ads, measuring our own advertising, and preventing fraud.
- **Sensitive data:** we collect none.
- **Under-16s:** we do not knowingly sell or share data of anyone under 16.
- **Your rights:** to know what we hold, to delete, to correct, to opt out of targeted advertising, sharing or sale, and not to be treated worse for using these rights.
- **How to use them (including "Do Not Sell or Share My Personal Information"):** switch off personalisation (**Change**, or "Ask App Not to Track" on iPhone, which also keeps your advertising ID from Meta; on Android, delete your advertising ID in Google's ad settings), use **Delete my data**, or email us. Where AdMob offers a US-states message, it gives a further opt-out.
- **Appeal:** if we decline a request, reply to our email to ask for a review, and you may then contact your state's attorney general.
- **Agents:** an authorised agent may write on your behalf; we may ask for proof.
- **Opt-out signals:** the game does not receive Global Privacy Control signals, so use the controls above.

## 9. Children

Paint Rumble is for people **16 and older**. It is not directed at, or intended for, anyone under 16, and we do not knowingly collect or solicit personal information from anyone under 16 or knowingly allow them to use our products. If you are under 16, you should not use our products or send us information about yourself, such as your name, address, telephone number or email address. If we learn that we have collected personal information from someone under 16, we will delete it. Parents and guardians can email paintrumble@gmail.com and we will help (section 8).

The game does not ask for your age or birthday. Its only age signal is Apple's Game Center child flag. It cannot detect a child's age in any other way, so it is **not a substitute for parental controls**. If a child may have access to your device, we recommend Family Link on Android, Screen Time and Game Center child accounts on iPhone.

## 10. Where the game is offered

Paint Rumble is not offered in the European Union, the European Economic Area, the United Kingdom or Switzerland. If you are in one of those places, please do not use it.

## 11. Changes to this policy

We may update this policy when the game or the law changes. The effective date at the top shows the current text. For material changes we will also tell you in the game.
