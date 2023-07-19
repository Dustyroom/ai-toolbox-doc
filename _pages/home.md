---
# title: "Splash Page"
layout: splash
permalink: /splash-page/
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/banners/test-banner.png
  actions:
    - label: "Buy"
      url: "https://u3d.as/334o?aid=1101lHzQ"
#  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
excerpt: "ChatGPT, DALL•E and Google Bard inside your Unity project."
intro:
  - excerpt: 'Use the power of AI both in the Unity Editor and in your shipped games. It allows you to generate C# scripts from text descriptions, and generate images from text descriptions, including seamlessly tiling ones, right in your project.'
# Centered with `type="center"`
feature_row:
  - image_path: /assets/images/landing/foo-image-1.png
    alt: "placeholder image 1"
    title: "Generate scripts from text"
    excerpt: "Write a prompt, press 'Generate' and have a script."
    url: "/getting-started/#generating-a-script-with-chatgpt-prompt-window"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/landing/foo-image-2.png
    # image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "placeholder image 2"
    title: "Edit new and existing scripts with AI"
    excerpt: "Edit newly generated or any old scripts with ChatGPT."
    url: "/getting-started/#editing-the-script-with-chatgpt-prompt-window"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/landing/foo-image-3.png
    title: "Generate images from text"
    excerpt: "Generate tileable images using DALL•E."
    url: "/getting-started/#generating-images-with-dalle"
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_row2:
  - image_path: /assets/images/landing/foo-image-4.png
    alt: "placeholder image 2"
    title: "Freeform chat with AI"
    # excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    excerpt: 'With AI Toolbox you can chat with AI in the Unity Editor about anything — ask it to explain code, where to find things in Unity, learn a delicious taco recipe.'
    url: "/getting-started/#chat-with-ai"
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_testimonials:
  - image_path: /assets/images/landing/landing_quotation.png
    alt: "quote 1"
    title: "Quote 1"
    excerpt: User 1"

  - image_path: /assets/images/landing/landing_quotation.png
    image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "quote 2"
    title: "Quote 2"
    excerpt: "User 2"

  - image_path: /assets/images/landing/landing_quotation.png
    alt: "quote 3"
    title: "Quote 3"
    excerpt: "User 3"


feature_row3:
  - image_path: /assets/images/landing/foo-image-5.png
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_row4:
  - image_path: /assets/images/landing/foo-image-6.png
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_row5:
  - image_path: /assets/images/landing/foo-image-8.png
    alt: "placeholder image 1"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}

{% include feature_row id="feature_row5" type="center" %}

{% include feature_row id="feature_testimonials" type="center" %}
