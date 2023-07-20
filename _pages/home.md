---
# title: "Splash Page"
layout: splash
permalink: /splash-page/
header:
  overlay_color: "#351d59"
  overlay_filter: "0.0"
  overlay_image: /assets/images/landing/landing_header_1.png
  actions:
    - label: "Get"
      url: "https://u3d.as/334o?aid=1101lHzQ"
#  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
excerpt: "ChatGPT, DALL•E and Google Bard inside your Unity project."
intro:
  - excerpt: 'Use the power of OpenAI GhatGPT in the Unity Editor and in your shipped games. It allows you to generate and edit C# scripts, seamlessly tiling images, shaders and UI documents from text descriptions, operate on new and existing scripts, freely chat with AI — right in your project.'
# Centered with `type="center"`
feature_video_1:
  - video: "/assets/images/banners/landing-banner-1.mp4"
    title: "Text to script. That simple."

feature_row:
  - image_path: /assets/images/landing/foo-image-1.png
    alt: "placeholder image 1"
    title: "Generate scripts from text"
    excerpt: "Write a prompt, press 'Generate' and have a script."
    url: "/getting-started/#generating-a-script-with-chatgpt-prompt-window"
    btn_label: "Watch Video"
    btn_class: "btn--primary"
    url: "/getting-started/#generating-a-script-with-chatgpt-prompt-window"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/landing/foo-image-2.png
    alt: "placeholder image 2"
    title: "Edit any script with AI"
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

feature_freeform_chat:
  - image_path: /assets/images/landing/foo-image-4.png
    alt: "placeholder image 2"
    title: "Freeform chat with AI"
    excerpt: 'With AI Toolbox you can chat with AI in the Unity Editor about anything — ask it to explain code, where to find things in Unity, learn a delicious taco recipe.'
    url: "/getting-started/#chat-with-ai"
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_testimonials:
  - image_path: /assets/images/landing/landing_quotation.png
    alt: "quote 1"
    title: "The most impressive aspect is how questions raised in the Discord community evolve into new features. With user feedback shaping its development, we've seen the integration of different Al sources like Google Bard, and the inclusion of the new Extended Context models such as GPT-3.5 16k. This real-time evolution is a testament to the asset's commitment to innovation and user-centricity."
    excerpt: — Swyfft
  - image_path: /assets/images/landing/landing_quotation.png
    alt: "quote 2"
    title: "Al Toolbox has made it easy for me to get stuff done in my project for an amateur game developer. It's very easy to quickly prototype scripts and generate textures for walls or items needed in games. I use it to intergrade other templates and tools together in Unity. It's a great tool set at a affordable price!"
    excerpt: — @CyberDeliaStudios
  - image_path: /assets/images/landing/landing_quotation.png
    alt: "quote 3"
    title: "They are continually improving, and constantly ready to help support with any of their other products."
    excerpt: — Asset Store User

feature_runtime:
  - image_path: /assets/images/landing/foo-image-6.png
    alt: "AI in Runtime"
    title: "Embed AI into the shipped games, securely."
    excerpt: 'With AI Toolbox you can securely embed and control AI into the shipped games.'
    url: "/runtime/"
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_bard:
  - image_path: /assets/images/landing/foo-image-5.png
    alt: "Google Bard integration"
    title: "Google Bard in Unity"
    excerpt: 'Google Bard intgration expands the palette of the AI tools available in your Unity project.'
    url: "/getting-started/#google-bard"
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_row5:
  - image_path: /assets/images/landing/foo-image-7.png
    title: "What you can do with AI Toolbox"
    excerpt: 'These are the things you can do with AI Toolbox.'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include video.html url='/assets/images/banners/landing-banner-1.mp4' %}{: .image-rounded}
{% include feature_row id="feature_video_1" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_freeform_chat" type="left" %}

{% include feature_row id="feature_testimonials" %}

{% include feature_row id="feature_runtime" type="center" %}

{% include feature_row id="feature_bard" type="right" %}

{% include feature_row id="feature_row5" type="center" %}

{% include video id="cNq-uCBq5yU" provider="youtube" %}
<!-- Video about generation -->

{% include video id="fedn7A9JTXA" provider="youtube" %}
<!-- Video about edits -->

{% include video id="6HlO9LsTLW0" provider="youtube" %}
<!-- Video about image generation -->
