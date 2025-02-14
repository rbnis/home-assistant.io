---
title: Speech-to-Text (STT)
description: Instructions on how to set up Speech-to-Text (STT) with Home Assistant.
ha_release: '0.102'
ha_codeowners:
  - '@home-assistant/core'
  - '@pvizeli'
ha_domain: stt
ha_quality_scale: internal
ha_category: []
ha_integration_type: entity
---

A speech to text (STT) entity allows other integrations or applications to stream speech data to the STT API and get text back.

The speech to text entities cannot be implemented manually, but can be provided by integrations.

## The state of a speech to text entity

Every speech to text entity keeps track of the timestamp of when the last time
the speech to text entity was used to process speech.
