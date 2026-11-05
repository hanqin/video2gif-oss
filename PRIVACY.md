# Video2Gif privacy policy

Last updated November 6, 2026.

This policy covers the native Video2Gif app (`com.xzwr.app.video2gif`), from TestFlight build 202610291501 of version 1.6.0 through version 2.1.0. The optional online text-effects feature applies to builds that offer online generation. The [earlier policy](https://yourskills.top/privacy#video-2-gif) covers version 1.5.

Version 2.1.0 internal TestFlight build 202611060240 offers on-device text editing and GIF creation with test ads. Apple sign-in, credit purchases and online effect generation are disabled in this build.

## Your videos, photos and GIFs

Video selection, editing, preview and GIF export run on your device. You can use the included text styles and make GIFs without signing in. Your source videos, photos and exported GIFs stay on your device unless you choose to share them.

The system Photos and Files pickers give the app access to the items you select. Selected source files, settings and generated GIFs may be stored in the app's private storage. Saving a GIF to Photos requests permission to add it to your library. Sharing sends the file to the destination you choose. The app does not record camera footage or request microphone, contacts or precise-location access.

Your system or file provider may download cloud-stored items when you select them. iOS backups, iCloud Photos and destinations you choose have their own settings and privacy policies. Those services are separate from our local conversion process.

## Optional AI text effects

When you tap Generate, Video2Gif sends your prompt, the words in the selected text layer, its font settings, output dimensions, duration and frame rate to our service. We send those fields to Google’s Vertex AI to create editable animation instructions. Use a prompt and text that you are comfortable sharing with Google.

The app also sends our service a transparent image of the letters and their layout, including placement, outline, background and timing. Our service uses these to check whether the effect moves visibly before charging one credit. Only our verification service receives these images and layout details. It processes them in memory and discards them after verification.

Sign in with Apple links your AI balance to a Firebase account. Firebase App Check and Apple App Attest help verify that a request comes from our app. Apple processes purchases. Our service verifies the signed transaction and keeps the transaction reference, credits and refund status. It stores completed animation instructions and the identifiers needed to retrieve them under your account. Our task records omit the original prompt, text and letter images.

## Advertising and privacy choices

This version uses Google Mobile Ads (AdMob) and Google's User Messaging Platform (UMP). Native ads can appear while the app creates a GIF or generates an AI text effect. Internal TestFlight builds use test ads. This version does not show app-open, interstitial or rewarded ads. Advertising and consent requests use the network; local GIF creation does not depend on an ad being available.

Google may process IP addresses and approximate location inferred from them; device or app identifiers; ad impressions and interactions; and crash, performance and diagnostic data. These support ad delivery and measurement, analytics, fraud prevention and consent functionality. Some identifiers and ad interaction data can be linked to a device or user. Google processes this information under [Google's Privacy Policy](https://policies.google.com/privacy) and describes its SDK practices in its [iOS data-disclosure guide](https://developers.google.com/admob/ios/privacy/data-disclosure).

The app checks the UMP consent status before starting or requesting ads. Where Google requires a choice, its consent form is shown. When available, Settings → Ad privacy choices lets you review or change those choices. The app disables Google's publisher first-party ID feature and does not supply a developer-assigned user ID or your media to ad requests.

This version does not initiate an Apple App Tracking Transparency permission prompt. An earlier iOS permission choice can remain in effect after an update. Access to Apple's advertising identifier is subject to iOS authorization; you can review it under iOS Settings → Privacy & Security → Tracking. The absence of a new prompt does not mean the advertising SDK collects no data. Declining tracking does not disable GIF creation, saving or sharing.

## Keeping and deleting data

Local files remain on your device until removed by an available app control or by deleting the app. Unexported edits are not offered as saved drafts. Files left by older versions remain in the app's local storage; this version does not browse, migrate or export those old projects. Updating the app does not deliberately erase them.

Deleting the app removes its local data. Copies already saved to Photos, shared elsewhere or included in system backups must be managed separately through those services. Deleting the app or changing an ad preference does not automatically delete data Google already received; Google's policy explains its retention and privacy controls. For help deleting an AI account, use the contact address below. Removing the app from your phone leaves your AI account and credit balance in place. Account deletion removes the balance and saved online effects. We retain purchase references needed to prevent the same transaction being credited again. Apple manages its own purchase records.

## TestFlight, external links and contact

Apple handles TestFlight installation, diagnostics and feedback under its own terms and [privacy policy](https://www.apple.com/legal/privacy/). Feedback you choose to send can contain your description or attachments. Opening policy, support or source-code links makes a request to the corresponding website, which has its own privacy practices.

For privacy questions, contact [yourtopskills@gmail.com](mailto:yourtopskills@gmail.com). If you contact us, we receive the message and any attachments you send so we can respond. Please do not include private media unless you intend to share it. We will update this policy when this version's data practices change.
