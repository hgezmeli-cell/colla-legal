# Colla — Privacy Policy

**Effective date:** 27 August 2026

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

Colla offers an optional one-time purchase and optional auto-renewing
subscriptions that unlock "Colla Pro" features. Purchases are processed by:

- **Apple** — App Store in-app purchase and subscription billing, on iOS.
- **Google** — Google Play Billing, on Android.

Colla never sees or stores your payment card details. Your relationship for
billing, renewals, and refunds is with Apple or Google under their terms and
privacy policies.

### 7.1 RevenueCat

Colla uses **RevenueCat** (RevenueCat, Inc.) as its purchase-infrastructure
provider. RevenueCat validates purchase receipts with Apple/Google and tells
the app whether your "colla_pro" entitlement is active.

- Colla configures RevenueCat **anonymously**. Colla does not call any
  sign-in / account-linking function and does not send RevenueCat a name,
  email address, or Colla account (there is no Colla account).
- Because Colla supplies no App User ID of its own, RevenueCat generates a
  random **anonymous App User ID** for the app install and uses it to
  associate purchase and entitlement records. It is not tied to your name,
  email, or any Colla account.
- **Purchase history:** purchase and subscription transaction data — for
  example which product was bought, the purchase and expiration dates, the
  store, and the country/region of the store account — is processed by
  RevenueCat as Colla's service provider, to deliver and restore your
  "colla_pro" entitlement.
- **RevenueCat technical information:** RevenueCat's general privacy policy
  separately states that it processes certain "End User Technical
  Information", such as device type and operating system, to operate its
  service. Per RevenueCat's current Apple App Privacy guidance, RevenueCat
  does **not** collect app diagnostics data and does **not** collect your
  precise or approximate location.

RevenueCat's own retention periods, sub-processors, and process for handling
data-subject / deletion requests are set by RevenueCat, not by Colla — see
<https://www.revenuecat.com/privacy>.

## 8. Analytics, advertising, and tracking

- **Analytics:** Colla contains no analytics or product-measurement SDK.
- **Advertising:** Colla contains no advertising SDK and shows no ads.
- **Tracking:** Colla does not track you across apps or websites owned by
  other companies, and does not use the iOS App Tracking Transparency prompt
  because there is nothing to track. No advertising identifier is requested.

The only network activity caused by the app is RevenueCat's purchase and
entitlement calls described in section 7.

## 9. Data retention

- Local preferences and the recents index: kept on your device until you
  delete them or uninstall the app (section 10).
- Exported collages saved to your photo library: controlled by you, in your
  photo library, indefinitely, until you delete them.
- Purchase / entitlement data held by RevenueCat, Apple, and Google: retained
  by those providers under their own policies.

## 10. Deleting local app data

- **Recent Creations:** remove individual items from the in-app "Recent
  Creations" strip, or clear them by uninstalling the app.
- **Preferences and all other local app data:** uninstalling Colla removes the
  app's private storage from your device. On Android you can also use
  Settings → Apps → Colla → Storage → Clear data.
- **Collages already saved to your photo library:** delete them from your
  photo library like any other photo.
- **Purchase records held by RevenueCat / Apple / Google:** contact those
  providers; Colla cannot delete records it does not hold. For RevenueCat
  data-subject requests, see RevenueCat's privacy page.

## 11. Children's privacy

Colla is a general-audience utility and is not directed to children. It does
not knowingly collect personal information from children, and it has no
account system, no profile, and no analytics. Colla does not present itself as
a child-directed app in either store.

## 12. Security

Colla keeps app data in the operating system's per-app private storage.
Purchase and entitlement calls to RevenueCat and to the app stores are made
over encrypted (HTTPS/TLS) connections provided by those SDKs. No system is
perfectly secure, and the app cannot secure data held by Apple, Google, or
RevenueCat.

## 13. International processing

Colla itself performs no server-side processing and operates no data centre.
Where RevenueCat, Apple, or Google process purchase data, that processing may
occur in countries other than yours, under those providers' own safeguards.

## 14. Your rights

Depending on where you live, you may have rights to access, correct, or delete
personal data, or to object to certain processing. Because Colla holds no
account and no server-side profile, most such requests concern data held by
RevenueCat, Apple, or Google and should be directed to them. For anything
Colla can address, contact us (section 16).

## 15. Changes to this policy

If this policy changes, the updated version will be posted at its published
location with a new effective date. Material changes will be indicated there.

## 16. Contact

For privacy questions or requests relating to Colla, contact
**diagniq.app@gmail.com**.
