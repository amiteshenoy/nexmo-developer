---
title: Overview
---

# Nexmo Comms SDKs Overview

Nexmo Comms SDKs is a conversation-centric product consisting of SDKs for iOS, Android, and JavaScript and a [REST API](/api/conversation).

Stitch enables communications across multiple channels including:

* In-app messaging over IP
* In-app voice over IP
* In-app voice to PSTN
* PSTN to in-app voice
* In-app video

Enable chat or voice in your mobile or web application with our SDKs so that your users can seamlessly communicate no matter which device they are on.

## Contents

* [Developer Preview](#developer-preview)
* [Supported features](#supported-features)
* [Getting started](#getting-started)
* [Concepts](#concepts)
* [SDK Documentation](#sdk-documentation)
* [References](#references)

## Developer Preview

This API is currently in Developer Preview.

Nexmo always welcomes your feedback. Your suggestions help us improve the product. If you do need help, please email [support@nexmo.com](mailto:support@nexmo.com) and include Conversation API in the subject line. Please note that during the Developer Preview period support times are limited to Monday to Friday.

If you want communicate with Nexmo during the developer preview you can:

* Join the [Nexmo community slack](https://developer.nexmo.com/community/slack/) and check out the [#comms-sdks](https://nexmo-community.slack.com/messages/C9H152ATW) channel.
* Email [ea-support@nexmo.com](mailto:ea-support@nexmo.com) directly.

## Supported features

### In-App Messaging

Build a feature rich chat experience that includes typing indicators and sent, delivered and read receipts.

Some features include:

* Offline Sync – With built-in caching, messages are saved and sent or received once their device is back online.
* Push Notifications – Keep users aware of important alerts by sending notifications to their device.
* Text and Image Support – Users can quickly send and receive texts and images from your application.

[Overview](/comms-sdks/in-app-messaging/overview)

### In-App Voice

Nexmo In-App Voice uses WebRTC and includes all the essentials you need to build a feature rich voice experience.

Some features include:

* User Control – Users can control whether their audio stream is muted or unmuted.
* Notifications  – Users can be notified when they receive a call or when participants are muted.
* Group Calls – Configure call settings so users can start a group call by adding participants in real time.

[Overview](/comms-sdks/in-app-voice/overview)

### In-App Video

Nexmo In-App Video uses WebRTC and includes all the essentials you need to build a feature rich video experience.

Some features include:

* User Control – Users can control whether their video stream is muted or unmuted.
* Notifications  – Users can be notified when other members have enabled a video channel.
* Group Calls – Configure conversations so users can start a group video call by adding participants in real time.
* Screen Sharing – Allow users to share their screens.

[Overview](/comms-sdks/in-app-video/overview)

## Concepts

You can read more about Stitch key concepts in the following topics:

```concept_list
product: conversation
```

## SDK Documentation  

<div class="row">
  <div class="columns small-12 medium-4">
    <a href="/sdk/stitch/javascript/" target="_blank" class="card spacious card--image card--javascript">
      <h2>JavaScript</h2>
    </a>
  </div>
  <div class="columns small-12 medium-4">
    <a href="/sdk/stitch/android/" class="card spacious card--image card--android">
      <h2>Android</h2>
    </a>
  </div>
  <div class="columns small-12 medium-4">
    <a href="/sdk/stitch/ios/" class="card spacious card--image card--ios">
      <h2>iOS</h2>
    </a>
  </div>
</div>

## References

* [API Reference](/api/conversation)
* [Nexmo CLI](https://github.com/nexmo/nexmo-cli/tree/beta)
* [Node.JS and Angular Demo](https://github.com/Nexmo/stitch-demo) with an [Android](https://github.com/Nexmo/stitch-demo-android) client demo