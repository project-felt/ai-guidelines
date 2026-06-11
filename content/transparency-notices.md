---
title: Transparency notices
description: Guidelines for communicating AI usage to users through visual and verbal indicators
category: ai
subcategory: guidelines
tags: [ai, transparency, disclosure, notices]
order: 3
last_updated: 2026-06-11
---


## It should always be clear when and how AI is being used

[User research](https://url.corp.redhat.com/ai-sentiment-survey) has shown that users want to clearly see when an action that they will take involves AI. When in doubt, communicate more about AI features, not less.

- Don't rely on just one form of indicator for AI-enabled experiences.
- At minimum use one visual and one verbal indicator, including options like icons, "with AI" button text, animations, and text disclaimers.
- Consider additional indicators for high-risk interactions. Consult with the AIA Reviewers during your AIA review process as needed.

## Transparency components for AI-related features

These components are used to notify users when they are interacting with AI-related features. They also inform users that generated responses may contain inaccuracies and advise them not to provide personal information, as AI systems may retain data for future improvements.

- Place the icon before the disclosure to help users notice and recognize the message.
- Tooltips are not included in these messages.
- The label and notification style may vary depending on the context in which the information appears.
- [Refer to the guidance](https://url.corp.redhat.com/notices-external-facing-ai-enabled-features) for more details on notification messages.

<figure data-type="example">
  <img src="../assets/images/warning-inline-alert-ai-related-features.png" alt="Inline alert warning component with &quot;[Feature name] uses AI. Check for mistakes. By using this feature, your [type of info] information will be used to create an AI-generated summary of your [type of info]...&quot; guidance" title="example" width="613">
  <img src="../assets/images/info-inline-alert-ai-related-features.png" alt="Inline alert info component with &quot;Important. This feature uses AI technology. Do not include any personal information or other sensitive information in your input...&quot; guidance" title="example" width="609">
  <img src="../assets/images/warning-modal-alert-ai-related-features.png" alt="Toast alert warning component with &quot;[Feature name] uses AI. Check for mistakes. By using this feature, your [type of info] information will be used to create an AI-generated summary of your [type of info]...&quot; guidance" title="example" width="389">
  <img src="../assets/images/info-modal-alert-ai-related-features.png" alt="Toast alert info component with &quot;Important. This feature uses AI technology. Do not include any personal information or other sensitive information in your input...&quot; guidance" title="example" width="389">
  <figcaption>

- Always review AI-generated content prior to use.
- AI-assisted search is for Red Hat product or support questions. Do not enter personal or sensitive information.
- Do not include any personal information or other sensitive information in your feedback. Feedback may be used to improve Red Hat's products or services.

  </figcaption>
</figure>

## Transparency notices for AI-assisted features

Some AI-assisted features may warrant more than an icon and text label. In these cases, a text notice can be placed at the beginning of an experience.

- You can tailor this text to the content.
- For external-facing AI features, [refer to this guidance](https://url.corp.redhat.com/notices-external-facing-ai-enabled-features) and work with your AIA Reviewers during the AIA review process.

<figure data-type="example landscape">
  <img src="../assets/images/warning-alert-ai-generated-content.png" alt="Inline alert info component shown above an AI case summary within a security application, with &quot;Important. This feature uses AI technology...&quot; guidance" title="example" width="1008">
  <img src="../assets/images/info-alert-ai-generated-content.png" alt="Inline alert warning component shown above an AI case summary within a security application, with &quot;Compliance case uses AI. Check for mistakes...&quot; guidance" title="example" width="1009">
  <figcaption>This notice is shown with the AI-generated content or AI-related tools.</figcaption>
</figure>

## Transparency notices for virtual assistants

- Include a notice at the beginning of an experience stating, at a minimum: "This feature uses AI technology. Do not include any personal information or other sensitive information in your input." (This notice is shown before a user interacts with the virtual assistant and before any content is generated.)
- Include a persistent notice under the 'i' icon: "Always review AI-generated content prior to use." (This is a persistent notice associated with the input/output box.)
- For external-facing AI features, [refer to this guidance](https://url.corp.redhat.com/notices-external-facing-ai-enabled-features).

<figure data-type="example">
  <img src="../assets/images/virtual-assistant-ai-icon-label.png" alt="Example: Ask Red Hat virtual assistant with the AI icon in the header bar as a visual indicator, and the AI tag/label is a verbal indicator" title="example" width="507">
  <img src="../assets/images/virtual-assistant-info-message.png" alt="Example: Ask Red Hat virtual assistant with an alert info component giving notice before a user interacts with the virtual assistant and before any content is generated. Persistent notice associated with input/output box" title="example" width="572">
  <figcaption>

- The AI icon serves as a visual indicator, and the "AI" tag/label is a verbal indicator.
- This notice is shown before a user interacts with the virtual assistant and before any content is generated, with a persistent notice associated with the input/output box.

  </figcaption>
</figure>

## Indicating AI-generated content

AI-generated content, like a search results summary, must include a label and icon showing users the content was AI-generated.

<figure data-type="do">
  <img src="../assets/images/search-results-label-sparkle-icon.png" alt="Example: AI-assisted results expandable section with the title indicating the use of AI both visually, with the sparkle icon, and verbally, by including &quot;AI-assisted&quot; in the results heading." title="do" width="871">
  <figcaption>The title indicates the use of AI both visually, with the sparkle icon, and verbally, by including "AI-assisted" in the results heading.</figcaption>
</figure>

## Indicating AI-generated images

Don't label AI-generated images or ads individually.

- Visually indicating each image would be distracting and could cause users to assume that entire images or pages are created without human influence, as seen in the responses to our AI sentiment survey.
- Instead, Red Hat is working on a site-wide notice that will outline when users will (and won't) encounter AI-generated images on Red Hat web properties.

<figure data-type="example">
  <img src="../assets/images/indicating-ai-generated-images.png" alt="Example: Desktop view of redhat.com showing an AI-generated laptop image, and Red Hat Developer ad with an AI-generated image of the &quot;Repo&quot; character with the birthday cake." title="example" width="1039">
  <figcaption>

- The laptop in this collage was generated with an Adobe Firefly custom model, but the rest of the elements and the page content are not genAI.
- The "Repo" character and the birthday cake in this ad were both generated using AI tools, but the logos, copy, and composition were created and composed by humans.

  </figcaption>
</figure>
