# Changes for *Siri AI Visual Bible*

This page lists changes to Siri AI, Apple Intelligence, and related features that have happened since the book was published on October 21, 2026. Each entry says what changed, what it means for readers, and where the information comes from. Entries are listed in chronological order with the most recent at the top.

> **Last updated:** 30 October 2026

- [Changes for *Siri AI Visual Bible*](#changes-for-siri-ai-visual-bible)
- [5 November 2026 – Siri AI opens to all developers (Developer Preview)](#5-november-2026--siri-ai-opens-to-all-developers-developer-preview)
- [26 October 2026: iOS 27.2 released](#26-october-2026-ios-272-released)
  - [New: Excluded Apps setting](#new-excluded-apps-setting)
  - [New: Siri AI recalls past conversations](#new-siri-ai-recalls-past-conversations)
  - [New: More sources of personal context](#new-more-sources-of-personal-context)
  - [New: Select part of a Siri response](#new-select-part-of-a-siri-response)
  - [New: Five more languages](#new-five-more-languages)
  - [Related Apple Intelligence changes](#related-apple-intelligence-changes)
- [13 October 2026: What you can do with Siri AI on the new Apple HomeView and Apple TV 4K](#13-october-2026-what-you-can-do-with-siri-ai-on-the-new-apple-homeview-and-apple-tv-4k)
  - [Apple HomeView](#apple-homeview)
  - [Apple TV 4K (2026)](#apple-tv-4k-2026)
  - [Not at launch](#not-at-launch)
- [Unchanged since publication](#unchanged-since-publication)
- [Not yet confirmed](#not-yet-confirmed)

---

# 5 November 2026 – Siri AI opens to all developers (Developer Preview)

**Source:** Apple Developer News, [*Siri AI is now open to all developers*](https://developer.apple.com/news/?id=gdk2umrf), 3 November 2026

On 3 November 2026, Apple released a **Developer Preview** that lets *any* developer integrate their app with Siri AI. Before this, Siri integration was limited to existing Siri capabilities and Apple's own apps. The preview ships with the **27.3 betas** of iOS, iPadOS, macOS, and visionOS.

Key points:

- **App Intents is the integration route.** Apps expose their content and custom actions to Siri AI through the App Intents framework. Siri AI can then run those actions in response to natural-language requests, for example checking a delivery, booking a reservation, or placing an order.
- **Apps get Siri AI's newer abilities.** Integrated apps can benefit from personal context understanding, onscreen awareness, and natural-language handling.
- **New: skills.** Developers can define *skills* that teach Siri AI how to chain several actions into one experience for more complex requests.
- **Broader Spotlight reach.** Siri AI can now surface any entity in the Spotlight semantic index, not only entities that match an existing schema.
- **Apple's own apps are being updated as reference examples.** Apple has started rolling out the new capabilities across apps including Calendar, Files, Finder, Journal, Mail, Maps, Messages, Music, Notes, Photos, Preview, Reminders, Safari, Shortcuts, and Weather. Apple's examples include finding a coffee shop you visited last week and archiving files not opened in over a year.
- **Timeline.** App Store submission of Siri AI integrations opens in Spring 2027.

---

# 26 October 2026: iOS 27.2 released

Apple released iOS 27.2 on Monday 26 October 2026 as the first major update to iOS 27, alongside matching updates for iPadOS, macOS, watchOS, and tvOS. It is a free update for any device that can run iOS 27, but Siri AI itself still requires an iPhone 15 Pro or later.

To update: **Settings** > **General** > **Software Update**.

## New: Excluded Apps setting

iOS 27.2 adds a single setting that controls which apps Siri AI can access. Apple's release notes say it covers Siri, Search, and suggestions, all from one place, and you can exclude several apps at once.

At launch in iOS 27.0, blocking Siri AI from an app meant changing several separate toggles, or turning Siri AI off and reverting to Siri Classic. The new setting replaces that with one list.

To exclude apps:

1. Update to iOS 27.2.
2. Navigate to **Settings** > **Siri** > **Excluded Apps**.
3. Tap **Add Apps**, and then select the apps that Siri AI should not access.

**What you give up:** Excluding an app is meant to cost you features, and that is how you know it is working. For example:

- If you exclude **Messages**, Siri AI can no longer read or reply to messages for you.
- **Onscreen awareness** stops working inside an excluded app. If you exclude Signal and then ask Siri about what is on screen in Signal, Siri will tell you it cannot help.

**Why it matters to you:** Many Siri AI requests are processed in the cloud. For end-to-end encrypted apps such as Signal and WhatsApp, that means message content could otherwise leave your device. The Electronic Frontier Foundation (EFF) had asked for exactly this kind of per-app control in its *Encrypt It Already* campaign, and has welcomed the change. The EFF would still like Apple to go further and offer an "on-device only" mode, similar to the one Samsung offers for Galaxy AI.

**Siri Classic** is still available if you would rather not use Siri AI at all.

**For comparison, on Android:** Gemini's per-app control is less straightforward. In the Gemini app, tap your user photo, and then navigate to **Settings** > **Personal Intelligence** > **Connected Apps** to revoke access. Gemini cannot set screen context per app, and it can still read notifications through the **Device Assistance** connected app unless you turn that off.

> **Book update:** Wherever the book describes limiting Siri AI's access to apps by toggling multiple settings, readers on iOS 27.2 or later should use **Excluded Apps** instead.

Sources:
- [Victory! You Can Now Exclude Apps from Siri AI – EFF, 28 October 2026](https://www.eff.org/deeplinks/2026/10/victory-you-can-now-exclude-apps-siri-ai)
- [How to Limit What Apple's New Siri AI Can Access in iOS 27 – EFF, 18 September 2026](https://www.eff.org/deeplinks/2026/09/how-limit-what-apples-new-siri-ai-can-access-ios-27)
- [Apple releases iOS 27.2, here's what's new – 9to5Mac](https://9to5mac.com/2026/10/26/apple-releases-ios-27-2-heres-whats-new/)

## New: Siri AI recalls past conversations

Siri AI can now remember earlier conversations. You can ask about something it told you before (for example, a restaurant it recommended last week), and it can use what it remembers to give better answers in a new chat.

Source: [iOS 27.2 Features: Everything New in iOS 27.2 – MacRumors](https://www.macrumors.com/2026/10/26/ios-27-2-features/)

## New: More sources of personal context

Siri AI can now draw on:

- Photos attached in Messages
- Calendar event attendees
- Voicemails

Apple also says results from Safari history and Reading List are improved.

Source: [Apple releases iOS 27.2, here's what's new – 9to5Mac](https://9to5mac.com/2026/10/26/apple-releases-ios-27-2-heres-whats-new/)

## New: Select part of a Siri response

You can now select and copy just part of a Siri response, instead of the whole thing.

Source: [Apple releases iOS 27.2, here's what's new – 9to5Mac](https://9to5mac.com/2026/10/26/apple-releases-ios-27-2-heres-whats-new/)

## New: Five more languages

Siri AI is no longer English-only. iOS 27.2 adds:

- French
- Japanese
- Korean
- Portuguese
- Spanish

This is the language expansion Apple promised for October when iOS 27 launched. TechCrunch reports that support for these languages is itself in beta.

Siri AI is **still not available in the EU or mainland China**.

Sources:
- [iOS 27.2 Features – MacRumors](https://www.macrumors.com/2026/10/26/ios-27-2-features/)
- [Apple rolls out iOS 27.2 with new Siri AI languages and security fixes – TechCrunch](https://techcrunch.com/2026/10/27/apple-rolls-out-ios-27-2-with-new-siri-ai-languages-and-security-fixes/)

## Related Apple Intelligence changes

These are not Siri AI features, but readers may come across them alongside Siri AI:

- **Suggestions in Messages:** Messages can suggest actions based on the conversation, such as adding a dinner plan as a Calendar event or a Reminder.
- **SynthID watermarking:** Images created with Image Playground, and large AI edits in Photos, now carry a SynthID watermark that helps identify generated or modified images.

Sources:
- [Apple releases iOS 27.2, here's what's new – 9to5Mac](https://9to5mac.com/2026/10/26/apple-releases-ios-27-2-heres-whats-new/)
- [24 New Features in iOS 27.2 for iPhone – iThinkDifferent](https://www.ithinkdiff.com/ios-27-2-everything-new-features/)

---

# 13 October 2026: What you can do with Siri AI on the new Apple HomeView and Apple TV 4K

At its "Welcome Home" event on 13 October 2026, Apple announced two devices with Siri AI support at launch. Both are available to pre-order and ship on 13 November 2026. Siri AI is available in English in the US, Australia, Canada, India, New Zealand, Singapore, South Africa and the UK.

## Apple HomeView

HomeView is Apple's new smart display and home hub. With Siri AI, you can:

- **Get answers and get things done by voice or touch.** HomeView has no physical buttons, so you talk to it or use the touchscreen.
- **Get a personalized experience.** HomeView recognizes who is in front of it, up to six people, and shows that person's own notifications, calendar and apps, drawing on data from their iPhone or iPad.
- **Continue conversations across devices.** Start a Siri AI conversation on HomeView and carry on with it on another Apple device.
- **Cook with help.** Open a recipe in Safari's new recipe mode and ask Siri AI to add ingredients or set timers.
- **Control your smart home.** Manage connected accessories, including the new Apple Home Collection cameras, doorbell, lock and thermostats, and view live camera feeds.

## Apple TV 4K (2026)

With Siri AI and built-in far-field microphones, you can:

- **Talk to Siri hands-free**, without picking up the remote.
- **Find something to watch using personal context.** Because Siri AI can draw on your iPhone, you can ask for a show a family member texted you about. It can suggest ways to refine a search and show answers on screen.
- **Control your smart home** from the sofa.
- **Find a lost remote** with a voice command that makes the Siri Remote play a sound.

Siri AI is also coming in **beta** to the 2021 and 2022 Apple TV 4K models.

## Not at launch

The new HomePod mini 2 goes on sale on 30 October but **without** Siri AI. Apple says it will arrive in "a future software update", with no date given.

---

# Unchanged since publication

The following points are still accurate as of 30 October 2026:

- Siri AI is still labelled **beta**. Apple has not announced when it will leave beta.
- Access still goes through a **waitlist**: **Settings** > **Siri** > **Try Siri AI (Beta)**.
- Siri AI requires an Apple Intelligence-capable device (iPhone 15 Pro or later on iPhone).
- Siri AI is not available to users under 13.

Sources:
- [iOS 27 – Apple](https://www.apple.com/os/ios/)
- [How Long Does The New Siri AI Take To Activate On iOS 27? – BGR](https://www.bgr.com/2269478/how-long-does-it-take-to-activate-siri-ai-on-ios-27/)

---

# Not yet confirmed

In line with the book's accuracy rule, the following are reported but **not confirmed**:

- **Siri AI on Apple TV:** Reports expected tvOS 27.2 to bring Siri AI to the second-generation Apple TV 4K and later, but Macworld found it was not yet active in the tvOS 27.2 release candidate. It may need a separate update, possibly around the new Apple TV's release on 13 November.

Source: [These iOS 27.2 features will make you want to download the latest updates right away – Macworld](https://www.macworld.com/article/3269963/these-ios-27-2-features-will-make-you-want-to-download-the-latest-updates-right-away.html)

