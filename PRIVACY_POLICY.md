<div align="center">

# 📅 Name Days — Privacy Policy

**Last updated: 29 September 2026**

[![App](https://img.shields.io/badge/Name%20Days-Download-brightgreen?style=for-the-badge&logo=google-play)](https://play.google.com/store/apps/details?id=com.namedaysdc)
[![Ads](https://img.shields.io/badge/Ads-Google%20AdMob-yellow?style=for-the-badge)](https://play.google.com/store/apps/details?id=com.namedaysdc)

</div>

---

> **Related:** [Terms of Use](./TERMS_OF_SERVICE.md) · [Back to README](./README.md)

---

**Effective date:** 8 August 2026  

**Last updated:** 29 September 2026  

**Developer:** Denis Casian  

**Package:** com.namedaysdc  

**Contact:** [bugs.rdcapps.com](https://bugs.rdcapps.com/)

This Privacy Policy explains how the **Name Days** mobile application (“App”) handles information on Android. By using the App, you acknowledge this policy.

**Advertising:** Name Days includes Google AdMob advertising, subject to applicable privacy choices. Supporter and active Monthly Supporter purchases remove ads; Premium Lifetime does not.

## 1. Privacy summary

- Name-day calendars are bundled with the App and processed locally.

- Favorites, selected and tracked countries, theme, reminder settings, widget customization, and selected Supporter icon are stored locally on your device.

- The App does not require an account for its core functionality.

- The developer does not receive your contacts, precise location, reminder content, favorites, or tracked-country list.

- Google Play and RevenueCat process limited purchase information to sell, verify, restore, and manage optional purchases and subscriptions.

- The developer does not sell personal information. Google AdMob processes advertising-related data as described below; personalized advertising depends on applicable consent and privacy choices.

## 2. Information handled by the App

### 2.1 Information stored locally

The following information may be stored in app storage or SharedPreferences:

- Selected country and tracked countries;

- Favorite names;

- Theme preference;

- Notification status and preferred reminder time;

- Whether the notification explanation has been shown;

- Selected launcher icon;

- Widget color, text size, and country-display preference;

- Ad-display counters, request cooldown timestamps, and consent choices used to manage advertising;

- Temporary cached purchase-entitlement status, used to avoid incorrect interface flicker while purchase status is refreshed.

Local calendar preferences and widget settings are used to provide App functionality and are not intentionally uploaded to the developer, Google Play, or RevenueCat. SDK-managed consent choices may be processed by Google to apply your advertising preferences, as described in section 2.5. The App is configured not to request Android cloud backup for its private app data. Local data is normally removed when you clear app data or uninstall the App.

### 2.2 Name-day calendar data

Name-day calendar files are included in the App. Date lookup, search, favorites, Upcoming lists, widgets, and reminder text are generated on your device. The developer does not operate a reminder server and does not receive the names or countries shown in your reminders.

### 2.3 Purchases and subscriptions

Optional purchases are processed through Google Play and managed with RevenueCat. Depending on the transaction and device, Google Play and RevenueCat may process:

- An anonymous RevenueCat App User ID;

- App package, app version, device/platform information, IP address, and technical diagnostics;

- Product identifiers, purchase tokens, transaction dates, subscription status, renewal status, expiration dates, refunds, and restorations;

- Store country and currency information;

- Information needed for fraud prevention and purchase validation.

The developer does not receive your full payment-card details. Purchases are subject to the policies and terms of Google Play and RevenueCat:

- [Google Privacy Policy](https://policies.google.com/privacy)

- [RevenueCat Privacy Policy](https://www.revenuecat.com/privacy)

### 2.4 Information we do not intentionally collect

- No account name, email address, or phone number is required by the App;

- No contacts are read or uploaded;

- No precise GPS location is requested;

- No microphone, camera, photos, SMS, or call history access is requested;

- The core calendar features do not need an advertising identifier; Google AdMob may process advertising identifiers when ads are enabled, as described in section 2.5;

- No personal data is sold by the developer.

### 2.5 Google AdMob advertising and privacy choices

Name Days includes adaptive banner, native, interstitial, and app-open advertisements delivered by Google AdMob. The Google Mobile Ads SDK may collect and share IP addresses (which can indicate approximate location), device or account identifiers such as the Android Advertising ID and app set ID, app and ad interactions, and performance diagnostics. Google uses this information for ad delivery, measurement, analytics, and fraud prevention. The App does not request precise GPS location for advertising or send your favorites, tracked-country list, or reminder text to AdMob.

The App uses Google's User Messaging Platform (UMP) to check applicable consent requirements and present a consent message where required. Ad requests begin only when UMP indicates that ads can be requested. Where required, consent is requested before personalized advertising. Declining personalization does not necessarily remove all ads; non-personalized or limited ads may be available depending on your choices and Google's configuration.

When available for your region, **Settings → Privacy options (GDPR / ads)** opens Google's privacy-options form so you can review or change your choices. Android's privacy/ad settings also provide advertising-ID controls. A verified Supporter entitlement disables ad requests and removes ad placements; the Mobile Ads SDK is not initialized at startup when an ad-removal entitlement is already recognized. If purchased after ads were initialized, the SDK cannot be unloaded, but further app-managed requests and ad displays are disabled. The in-app advertising privacy-options entry is hidden while ad removal is active.

**Premium Lifetime does not remove ads.** One-Time Supporter removes ads while its non-consumable entitlement remains valid; Monthly Supporter removes ads while the subscription entitlement is active. Ads may return after a refund, revocation, or subscription expiration once the updated purchase status is verified, subject to privacy choices.

For provider-specific details, see the [Google Privacy Policy](https://policies.google.com/privacy), [Google advertising privacy information](https://policies.google.com/technologies/ads), and [Google Mobile Ads SDK data disclosure](https://developers.google.com/admob/android/privacy/play-data-disclosure).

## 3. Permissions and system access

- **Internet and network state** — RevenueCat purchase verification, Google AdMob ad delivery, UMP privacy messages, and opening user-selected web links;

- **Notifications** — optional local daily name-day reminders;

- **Boot completed, alarms, exact alarms, and wake lock** — scheduling and recovering local reminders after restart, time changes, or device sleep;

- **Advertising ID** — the advertising SDK may access the Android Advertising ID when available and permitted by applicable privacy choices;

- **Billing** — optional Google Play purchases and subscriptions;

- **Battery-optimization settings** — opening Android settings at your request to improve reminder reliability;

- **Launcher component state** — changing the launcher icon when an eligible Supporter icon is selected.

## 4. Notifications

Daily reminders are generated locally. The App does not send reminders from a remote server. Android notification permission is requested only after an explanation and user action. You can disable reminders at any time in the App or Android settings.

Android and device manufacturers may delay or suppress background work. The App uses redundant local scheduling methods, but no mobile application can guarantee delivery at an exact minute on every device.

## 5. Purchase status, restoration, cancellation, and refunds

The App requests current CustomerInfo from RevenueCat at launch and when returning to the foreground. Purchase results are applied immediately after a successful transaction. A Restore Purchases option is provided, and an automatic restoration attempt may be made after a new installation when no active entitlement is found.

Subscriptions can be managed or cancelled through the Google Play subscription-management page opened by the App. Cancellation normally stops renewal while access continues until the paid period expires. Refunds, revocations, expirations, billing issues, and other store changes may remove the associated entitlement after Google Play and RevenueCat report the updated status. An internet connection may be required for the latest status.

## 6. Legal bases

Where GDPR, UK GDPR, or similar law applies, processing may rely on:

- **Performance of a contract** — providing purchased Premium or Supporter benefits;

- **Legitimate interests** — security, fraud prevention, troubleshooting, and reliable app operation;

- **Consent or user request** — advertising consent where required, notifications, opening system settings, changing the launcher icon, and opening external links;

- **Legal obligations** — tax, accounting, consumer-protection, and payment requirements handled by applicable providers.

## 7. US state privacy disclosures

The App includes Google AdMob. Advertising-related disclosures and choices are described in section 2.5. The developer does not sell personal information for money; some advertising-related sharing may be considered a sale or sharing under applicable US state privacy laws. Where applicable, use Google's privacy-options form to exercise available opt-out choices. Depending on your jurisdiction, you may have rights to request access, correction, deletion, or information about processing. Purchase records controlled by Google Play or RevenueCat must generally be addressed through those providers.

## 8. Children

The App is a general-audience utility and is not designed to collect personal information from children. It does not require a profile. Google AdMob advertising is subject to applicable consent and privacy choices. Parents or guardians with concerns about advertising-related processing should contact the developer. Optional purchases are controlled by Google Play and device or family payment settings.

## 9. Retention

- Local preferences remain until changed, app data is cleared, or the App is uninstalled;

- Purchase and subscription records are retained by Google Play and RevenueCat according to their legal obligations, service terms, and retention policies;

- Advertising and consent-related data processed by Google are retained according to Google's policies; stopping ads does not automatically delete previously processed provider records;

- Technical support information voluntarily submitted through the bug-report website is handled according to that site’s policy.

## 10. International processing

Google and RevenueCat may process purchase-related, advertising-related, consent, and technical information in countries other than your own. They are responsible for applying the safeguards described in their respective privacy documentation.

## 11. Your choices and rights

- Use the App without creating an account;

- Keep tracked countries and favorites empty;

- Disable notifications in the App or Android settings;

- Manage or cancel subscriptions through Google Play;

- Use Restore Purchases for eligible purchases;

- Review advertising privacy choices in Settings when the Google privacy-options form is available, and manage the advertising identifier in Android settings;

- Choose Supporter or active Monthly Supporter to remove ads; Premium Lifetime does not remove them;

- Clear app data or uninstall the App to remove local preferences;

- Exercise applicable privacy rights by contacting the relevant data controller or service provider.

## 12. Security

Reasonable technical measures are used to limit unnecessary data handling. However, no device, network, store, or online service can be guaranteed completely secure.

## 13. External links

The App may open the Privacy Policy, Terms of Use, bug-report website, Google Play pages, RevenueCat/Google subscription pages, or other user-selected links. Those services have their own terms and privacy practices.

## 14. Changes to this policy

This policy may be updated when App functionality, providers, or legal requirements change. The “Last updated” date will identify the current version.

## 15. Contact

Privacy questions or requests: [https://bugs.rdcapps.com/](https://bugs.rdcapps.com/)  

Developer page: [Google Play developer page](https://play.google.com/store/apps/dev?id=7430316407711724691)  

Terms: [https://terms.rdcapps.com/namedays.html](https://terms.rdcapps.com/namedays.html)

**Note:** This policy describes the current App configuration with Google AdMob and UMP privacy messaging. If you are viewing an older installed version, update through Google Play.
