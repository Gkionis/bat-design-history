---
title: Iteration 28 June 2018
description: Add character counts and refine preview.
date: 2018-06-28
---
As with the [previous iteration](/publish-teacher-training-courses/iteration-june-26), we ran an unmoderated research session with this design where we asked providers to complete a course listing, the user recorded their input to a [session on Lookback](https://lookback.io/watch/ACpaee3SkiuGxS5CD).

In this iteration we:

* added character counts
* made interview process optional
* hid incomplete optional fields from preview
* added fields for international course fees

Based on the first submission, which was mostly copy and pasted text, we quickly added word counts to each field. We expect character counts to limit input and to trigger users into editing their text down.

[Feedback from the first session](https://docs.google.com/document/d/19zLJb1fplLHmrxZ2VlPsWCfdhqfK0DuoyKjCog8eeAE/edit?usp=sharing) indicated that details of an involved interview process may discourage users from applying.

We clarified which fields were optional and refined the preview to hide incomplete optional fields.

{% from "screenshots/macro.njk" import appScreenshots with context %}
{{ appScreenshots({
  items: [{
    text: "PGCE with QTS course option",
    img: { src: "pgce-with-qts-course-option.png" }
  }, {
    text: "QTS with salary course option",
    img: { src: "qts-with-salary-course-option.png" }
  }, {
    text: "About your organisation",
    img: { src: "about-your-organisation.png" }
  }, {
    text: "Requirements and eligibility",
    img: { src: "requirements-and-eligibility.png" }
  }, {
    text: "Preview",
    img: { src: "preview.png" }
  }]
}) }}
