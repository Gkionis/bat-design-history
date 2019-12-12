---
title: Onboarding wizard as a Google form
description: Capturing contact details, UCAS admin details and first location.
tags: publish-teacher-training-courses
---
An update on the [original onboarding wizard](/publish-teacher-training-courses/onboarding-wizard). This form is an accompaniment to an initial onboarding call, meaning we don’t have to ask and transcribe answers to these questions.

## Screenshots

{% from "gallery/macro.njk" import appGallery %}
{{ appGallery({
  path: page.filePathStem | replace("/posts", "/images"),
  items: [
    {text: "Who is adding this organisation?"},
    {text: "Organisation name"},
    {text: "Access to ucas"},
    {text: "First location"},
    {text: "Confirmation"}
  ]
}) }}