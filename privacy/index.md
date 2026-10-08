# Colla — Privacy Policy

**Effective date:** 8 October 2026

**Publisher / developer:** Hakan Gezmeli — Individual Developer

**Contact:** diagniq.app@gmail.com

---

## 1. What Colla is

Colla ("the app") is a photo collage editor for Android and iOS. You choose
photos already on your device, arrange them into a collage, and save or share
the result. The app has **no user account and no Colla-operated server**. All
photo editing happens on your device.

This policy explains the limited data involved in running the app and the one
third-party service the app uses (RevenueCat, for purchases).

## 2. Photo access

When you add photos to a collage, Colla opens your operating system's own
photo picker (the iOS photo picker / the Android photo picker). That picker
runs outside the app. Colla receives **only the specific image files you
select** and never gets ongoing or full access to your photo library.

Selected photos are read into memory for editing. Colla does **not** copy your
selected source photos into its own long-term storage, and does **not** upload
them anywhere.

## 3. Local photo processing

Cropping, positioning, backgrounds, borders, layout, and rendering are all
performed locally on your device. Your photos are not sent to Colla or to any
third party as part of editing or exporting.

## 4. Exported collages

When you tap Save, the finished collage image is written to your device's
operating-system photo library using the OS "add to photo library" function.
On iOS this uses add-only photo permission. Colla does not create albums and
does not read back your library.

A copy of each exported collage, plus a small thumbnail and a timestamp, is
also kept inside the app's private storage to populate the in-app "Recent
Creations" strip. This data never leaves your device. See section 10 for how
to remove it.

## 5. Local preferences and recents

Colla stores the following on your device only, using the platform's standard
key–value preference storage and the app's private file storage:

- appearance (theme) preference
- language preference
- default export resolution and format
- whether you have completed the first-run introduction
- the "Recent Creations" index described in section 4

None of this identifies you, and none of it is transmitted off the device by
Colla.

## 6. Android backup

On Android, Colla sets `android:allowBackup="false"`. The local data in
section 5 is **not** included in Android's cloud backup / restore. It stays on
the single device where it was created.

## 7. Purchases (Colla Pro)

Colla offers an optional one-time purchase that unlocks "Colla Pro" features.
It is not a subscription and does not renew. Purchases are processed by:

- **Apple** — App Store in-app purchase billing, on iOS.
- **Google** — Google Play Billing, on Android.

Colla never sees or stores your payment card details. Your relationship for
billing and refunds is with Apple or Google under their terms and privacy
policies.

### 7.1 RevenueCat

Colla uses **RevenueCat** (RevenueCat, Inc.) as its purchase-infrastructure
provider. For the data described in this section, Colla — the developer named
at the top of this policy — is the data controller, and RevenueCat is a data
processor acting on Colla's behalf.

The app contacts RevenueCat when it starts, to check whether "colla_pro" is
active, and again when you buy or restore Colla Pro. The start-up check
happens whether or not you have bought anything.

**Why this data is processed**

- to deliver your "colla_pro" entitlement and to restore it, for example on
  a new device or after a reinstall;
- to validate purchase receipts with Apple / Google and to prevent fraud;
- to give the developer purchase history and statistics through the
  RevenueCat dashboard. The dashboard shows the developer the purchases
  recorded against each anonymous App User ID, with the details listed below,
  as well as overall figures such as the number of purchases and revenue.

**What is processed**

- the Apple receipt or Google purchase token, and the purchase details that
  come with it — for example which product was bought, the purchase date,
  the store, the price and currency, and the country/region of the store
  account;
- the time the app last contacted RevenueCat ("last seen");
- device type and operating system, including its version, and the version
  of the app;
- the device's language / region setting (locale) and currency;
- a country derived from your IP address. Every request the app sends
  reaches RevenueCat's servers from your IP address, as with any internet
  connection. RevenueCat can work out a country from that address and shows
  it to the developer as the country you were last seen in. RevenueCat's
  documentation states that the IP address itself is not kept once the
  country has been determined.

**How the record is identified**

- Colla configures RevenueCat **anonymously**. Colla does not call any
  sign-in / account-linking function and does not send RevenueCat a name,
  email address, phone number, advertising identifier, or Colla account
  (there is no Colla account).
- Because Colla supplies no App User ID of its own, RevenueCat generates a
  random **anonymous App User ID** for the app install and uses it to
  associate the records above. It is not tied to your name, email, or any
  Colla account.

**Requests about this data**

Send any request about the purchase data RevenueCat processes for Colla —
access, correction, or deletion — to Colla at **diagniq.app@gmail.com**, not
to RevenueCat. RevenueCat's own privacy policy refers end users to the app
developer for such requests. Because the record is anonymous, we need a way
to find it. The order number on your App Store or Google Play receipt is one
option; if you do not have it, write to us anyway and we will look for
another way to match your record.

RevenueCat's privacy policy is at <https://www.revenuecat.com/privacy>.

## 8. Analytics, advertising, and tracking

- **Analytics:** Colla contains no analytics or product-measurement SDK.
- **Advertising:** Colla contains no advertising SDK and shows no ads.
- **Tracking:** Colla does not track you across apps or websites owned by
  other companies, and does not use the iOS App Tracking Transparency prompt
  because there is nothing to track. No advertising identifier is requested.

Purchase data is the one thing the developer does receive. RevenueCat makes
the data in section 7.1 available to the developer through its dashboard:
the purchase history recorded against each anonymous App User ID, and
statistics built from it, such as the number of purchases and revenue.

The only network activity caused by the app is its communication with
RevenueCat and the app stores described in section 7.

## 9. Data retention

- Local preferences and the recents index: kept on your device until you
  delete them or uninstall the app (section 10).
- Exported collages saved to your photo library: controlled by you, in your
  photo library, indefinitely, until you delete them.
- Purchase data that RevenueCat processes for Colla (section 7.1): kept for
  as long as it is needed to deliver and restore purchases, and deleted on
  request (section 10).
- Purchase records held by Apple and Google: retained by those providers
  under their own policies.

## 10. Deleting local app data

- **Recent Creations:** remove individual items from the in-app "Recent
  Creations" strip, or clear them by uninstalling the app.
- **Preferences and all other local app data:** uninstalling Colla removes the
  app's private storage from your device. On Android you can also use
  Settings → Apps → Colla → Storage → Clear data.
- **Collages already saved to your photo library:** delete them from your
  photo library like any other photo.
- **Purchase data processed by RevenueCat:** email Colla at
  **diagniq.app@gmail.com** and we will delete your record from RevenueCat.
  Section 7.1 explains how we match a request to a record. Deleting the
  record does not cancel or refund the purchase. If you use Restore purchase
  afterwards, a new record is created.
- **Purchase records held by Apple / Google:** contact Apple or Google;
  Colla cannot delete records it does not hold.

## 11. Children's privacy

Colla is a general-audience utility and is not directed to children. It does
not knowingly collect personal information from children. Colla has no
account and no profile; RevenueCat holds an anonymous purchase record
(section 7.1). Colla does not present itself as a child-directed app in
either store.

## 12. Security

Colla keeps app data in the operating system's per-app private storage.
Purchase and entitlement calls to RevenueCat and to the app stores are made
over encrypted (HTTPS/TLS) connections provided by those SDKs. No system is
perfectly secure, and the app cannot secure data held by Apple, Google, or
RevenueCat.

## 13. International processing

Colla itself performs no server-side processing and operates no data centre.

RevenueCat states that it stores the data it processes on Amazon Web Services
(AWS) data centres in the **United States**. The data in section 7.1 is
therefore sent to and stored in the United States, wherever you live.

Where Apple or Google process purchase data, that processing may occur in
countries other than yours, under those providers' own safeguards.

## 14. Your rights

Depending on where you live, you may have rights to access, correct, or delete
personal data, or to object to certain processing.

- **Purchase data processed by RevenueCat:** Colla is the data controller
  and RevenueCat the data processor (section 7.1). Send these requests to
  Colla at **diagniq.app@gmail.com**; we act on them in RevenueCat on your
  behalf.
- **Data held by Apple or Google** about your store account and purchases:
  those companies are responsible for it; direct such requests to them.
- **Everything else** stays on your device and is under your control
  (section 10).

## 15. Changes to this policy

If this policy changes, the updated version will be posted at its published
location with a new effective date. Material changes will be indicated there.

## 16. Contact

For privacy questions or requests relating to Colla, contact
**diagniq.app@gmail.com**.
