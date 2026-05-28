# Privacy Policy — PUBDOM Cards

_Last updated: 28 May 2026_

This Privacy Policy describes how the PUBDOM Cards mobile application
("the app", "we", "our", "us") collects, uses, and shares information
about you when you use our application. By installing and using PUBDOM
Cards you agree to the practices described below.

## 1. Who we are

PUBDOM Cards is an independent mobile game distributed via the Google
Play Store. The developer can be contacted at the email address listed
at the bottom of this policy.

## 2. Information we collect

We collect the **minimum** information required to operate the game.

### 2.1 Account information (via Google Sign-In)
When you sign in with your Google account, we receive from Google:
- Your Google account identifier (the opaque `sub` claim)
- Your email address
- Your public display name (if any)
- Your public profile picture URL (if any)

We use this information solely to identify you across devices and to
restore your game progress when you reinstall the app.

### 2.2 Game progress
Your in-game state is saved to our servers so it can sync across
devices. This includes:
- Coin balance, owned cards, opened booster packs, mission progress,
  achievements
- Your chosen display name and avatar
- The Google `sub` identifier above (used as the primary key)

We do **not** collect chat messages, contacts, photos, location,
microphone audio, or any other sensor data.

### 2.3 Purchase information (via RevenueCat & Google Play Billing)
When you make an in-app purchase, the transaction is processed by
Google Play Billing. Our purchase verification provider, RevenueCat,
records:
- The product purchased and its price
- The Google Play transaction ID
- Your in-app identifier (the same `sub`-derived id above)

We do **not** see or store your credit card number, billing address, or
any other payment-instrument information. All such data is handled
exclusively by Google.

### 2.4 Technical data
The Google Play Store and our hosting provider may automatically
collect technical information such as device model, OS version, IP
address, and crash reports. We use this only to debug issues and
improve stability.

## 3. How we use your information

We use the information described above to:
- Authenticate you and keep your collection in sync across devices
- Process and verify in-app purchases
- Show leaderboards (your chosen display name and game stats; you can
  change your name in Settings at any time)
- Investigate fraud, refund disputes, and abuse
- Provide customer support when you contact us

We do **not** sell your information. We do **not** use it to send you
marketing emails. We do **not** show third-party advertising.

## 4. Third-party services

We share limited information with the following processors, strictly
to operate the game:

| Provider | Data shared | Purpose |
|---|---|---|
| **Google Sign-In** | Your Google ID token | Authenticate you |
| **Google Play Billing** | Purchase transactions | Process payments |
| **RevenueCat** | Your in-app user id + transactions | Verify purchases |
| **MongoDB Atlas / our backend** | Game progress + identifiers | Store cross-device save |

Each provider has its own privacy policy that governs their handling
of the data we share with them.

## 5. Children

PUBDOM Cards is intended for users aged 13 and older. We do not
knowingly collect personal information from children under 13. If you
believe a child has signed in to the app, please contact us so we can
delete the account.

## 6. Data retention

- **Account & game progress:** retained as long as you keep playing.
- **Purchase records:** retained for at least 7 years to comply with
  financial-record-keeping obligations.
- **Crash logs:** retained for up to 90 days.

## 7. Your rights

You may at any time:
- **Access** the data we hold about you — contact us at the address
  below.
- **Delete** your account and all associated game progress — contact
  us and we will erase your record within 30 days. Purchase records
  may be retained for the period stated above for legal reasons.
- **Export** your collection — contact us and we'll provide a JSON
  dump.

If you are in the EU, UK, or California, you also have the rights
afforded by GDPR / CCPA respectively (the rights above already cover
the substance of those laws).

## 8. Security

We use standard industry practices to protect data in transit (TLS)
and at rest (encrypted database). No system is perfectly secure, and
we cannot guarantee absolute protection.

## 9. Changes to this policy

We may update this policy from time to time. The "Last updated" date
at the top will change. Material changes will be announced in-app.

## 10. Contact

Questions, deletion requests, or anything else:

**support@pubdomcards.app** _(replace with your real address before publishing)_

---

_Hosted at https://pubdomcollect.github.io/privacy/ (or your equivalent
public URL). Submit this URL to the Google Play Console under
"Policy → App content → Privacy policy"._
