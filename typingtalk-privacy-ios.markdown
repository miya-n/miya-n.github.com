---
layout: default
title: TypingTalk Privacy Policy (iOS)
permalink: /typingtalk-privacy-ios/
---

<style>
    .rounded {
        border-radius: 8px;
    }
</style>

# <img src="/assets/images/speaking-assist-icon.png" width="70" height="70" class="rounded"> &nbsp;TypingTalk AAC Privacy Policy (iOS)

When using the “System” and “Personal Voice” voice types on the app, no data of any kind is collected, shared, or stored on our servers. Usage of these voices is completely local to the device.

When connecting to the “Google Text-to-Speech” voice type for the first time, an anonymous ID is randomly generated for the user and stored on our servers. This ID is used to authenticate the user, allowing them to use the Cloud Text-to-Speech services.

When pressing the “speak” button with Google Text-to-Speech, a transient request is sent to Google Cloud containing the text and chosen voice settings, which is processed according to the [Google Cloud Platform Privacy Policy](https://cloud.google.com/terms/cloud-privacy-notice). This information is used only long enough to process the input, generate and return the speech audio output, and is immediately discarded afterwards.

After every Google Text-to-Speech request, the length in characters of the input text is subtracted from the user’s remaining characters value in our database. Only the length of text is used for this process, not the content or any other details. This is to prevent malicious users from sending too many long requests in a single day. This data is not shared with any third party, or used for any other purpose. Additionally, the remaining characters value is reset for all users daily at 12:00 AM GMT.

While using Google Text-to-Speech, an AdMob banner ad is displayed at the bottom of the screen. These ads do not use the device's IDFA (identifier for advertisers), and are not personalized. The ads may use other contextual information, such as coarse geo-targeting based on city-level location, or other content relating to the app.

To delete your anonymous user ID and data from our servers, simply do not open Google Text-to-Speech in the app for at least 30 days. Uninstalling the app works for this purpose, but is not necessary; you can keep using the "System" and "Personal Voice" types as long as you do not open a Google voice. After 30 days, your data is automatically deleted from our servers.