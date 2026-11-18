# Privacy Policy for Trace (Draft)

> **DISCLAIMER**: This document is a draft template provided for informational and product planning purposes only. It does not constitute formal legal advice. Developers should consult qualified legal counsel to ensure compliance with applicable data protection regulations (such as GDPR, CCPA/CPRA, and Google Play Store policies) before publication.

*Last Updated: November 2, 2026*

Welcome to **Trace**. We believe that mobile puzzle games should respect your privacy, work seamlessly offline, and never monetize your personal life. This Privacy Policy explains our commitment to transparency: what data we collect, how it is handled, and the choices available to you.

---

## 1. Summary of Principles

- **No Account or Registration Required**: You never need an account, email address, username, phone number, or social media login to play Trace.
- **Offline-First & Local Storage**: All your campaign progress, completed levels, star ratings, streaks, and settings are saved strictly on your local device.
- **Strictly Opt-In Telemetry**: By default, data collection is turned completely **OFF**. Zero analytics or telemetry events are transmitted unless you explicitly give consent.
- **No Personal Identifiers or Profiling**: We do not collect names, emails, IP addresses, device serial numbers, or advertising identifiers (Android Advertising ID / Apple IDFA). Advertising ID collection is deactivated at the native operating system level.
- **No Data Brokerage or Sale**: We do not sell, rent, or trade player data to third parties.

---

## 2. Information We Collect (Only With Your Consent)

If you explicitly choose to turn on **"Share anonymous usage data"** in the game intro or Settings, Trace transmits minimal, anonymous gameplay statistics to help us balance puzzle difficulties and improve the app:

### A. Gameplay Telemetry
- **Tutorial Completion**: Whether the introductory mechanics tutorial (levels 1–3) was finished or skipped.
- **Level Progress**: Level number (1–364) and pack identifier (`warm_up`, `easy_going`, `getting_tricky`, `brain_burners`, `masters`).
- **Level Performance**: Star rating earned (1–3 stars), number of resets on the level, whether a hint was used, and duration bucket (`<30s`, `30-120s`, `120-300s`, `>300s`).
- **Level Exits**: Whether a level was exited before completion (via Back navigation or app backgrounding) and the duration bucket.
- **Hint Usage**: High-level hint category selected (`next_steps`, `show_route`, `solve_it`, `gentle_nudge`).
- **Feature Engagement**: When the "Share" result card button is tapped or the initial difficulty choice (`new` or `challenge`) is made.
- **Aggregated Level Bucket**: Highest campaign level reached in broad brackets (`1-10`, `11-50`, `51-120`, `121-240`, `241-364`).

### B. What We NEVER Collect
- **NO Personal Data**: No names, email addresses, phone numbers, or account credentials.
- **NO Device Hardware Identifiers**: Advertising ID collection and ad-personalization signals are completely disabled.
- **NO Location Data**: No GPS, Wi-Fi location, or fine/coarse geographical tracking.
- **NO Puzzle Solution Paths**: We never record the exact board cells you drag or your specific tile movements.
- **NO Free-Form Text**: There are no chat rooms, open feedback boxes, or arbitrary text inputs transmitted.

---

## 3. Why We Collect This Data

We use anonymous gameplay metrics solely for:
1. **Difficulty Tuning**: Identifying puzzles with unusually high reset rates, prolonged completion times, or high abandonment rates to improve game balance.
2. **Onboarding Evaluation**: Verifying that new players understand the core drag-and-fill rules without encountering confusing bottlenecks.
3. **App Stability & Quality**: Ensuring levels and features perform reliably across supported mobile operating systems.

---

## 4. Third-Party Service Providers and Data Processors

When analytics consent is granted, data is processed by:

- **Google Firebase Analytics (Google LLC)**:
  - **Purpose**: Aggregated application performance and retention metrics.
  - **Data Retention & Security**: Transmitted securely over encrypted HTTPS connections (TLS). Google processes data according to Google Cloud data privacy terms.
  - **Retention Reports**: Retention (Day 1, Day 7) is computed in aggregate through Firebase Analytics without creating individual player profiles.

---

## 5. How to Opt Out or Change Your Choice

You have complete control over analytics collection at all times:

1. Open **Trace**.
2. Tap the **Settings** gear icon on the home screen.
3. Under the **About** section, toggle **"Share anonymous usage data"** on or off.

- **Instant Effect**: When you switch this setting to OFF, `setAnalyticsCollectionEnabled(false)` is invoked immediately and all telemetry transmission ceases instantly.
- **Equal Choice**: In-app consent prompts provide equally prominent options ("No thanks" and "Share data") with zero dark patterns or penalties for declining.

---

## 6. Children's Privacy

Trace does not knowingly collect personally identifiable information from children under the age of 13 (or under the age of 16 in the European Economic Area). The game is designed to be safe for general audiences with default-disabled telemetry and zero personal data collection.

---

## 7. Contact Us

If you have questions, feedback, or concerns regarding this draft policy or our privacy practices, please contact:

**Developer Contact Placeholder**:  
- **Email**: `privacy@example.com`  
- **Website**: `https://example.com/trace`  
*(Please replace these placeholders with your production support contact address prior to release).*

