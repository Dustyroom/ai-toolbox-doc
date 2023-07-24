---
layout: splash
permalink: /
header:
  overlay_color: "#351d59"
  overlay_filter: "0.0"
  overlay_image: /assets/images/landing/landing-prompt-code-result-1.png
  actions:
    - label: "Get on Unity Asset Store"
      url: "https://u3d.as/334o?aid=1101lHzQ"
#  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
excerpt: "ChatGPT, DALL•E and Google Bard inside your Unity project."
intro:
  - excerpt: 'Use the power of OpenAI GhatGPT in the Unity Editor and in your shipped games. It allows you to generate and edit C# scripts, seamlessly tiling images, shaders and UI documents from text descriptions, operate on new and existing scripts, freely chat with AI — right in your project.'
# Centered with `type="center"`

feature_video_1:
  - title: "Text to script. That simple."
#  excerpt: "duh"

feature_row:
  - image_path: /assets/images/landing/none.png
  #  alt: "placeholder image 1"
    title: "Generate scripts from text"
    excerpt: "Write a prompt, press 'Generate' and have a script."
    url: "/getting-started/#generating-a-script-with-chatgpt-prompt-window"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/landing/none.png
  #  alt: "placeholder image 2"
    title: "Edit any script with AI"
    excerpt: "Edit newly generated or any old scripts with ChatGPT."
    url: "/getting-started/#editing-the-script-with-chatgpt-prompt-window"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/landing/none.png
    title: "Generate images from text"
    excerpt: "Generate tileable images using DALL•E."
    url: "/getting-started/#generating-images-with-dalle"
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_freeform_chat:
  - image_path: /assets/images/landing/ai_toolbox_landing_chat_6.png
    alt: "placeholder image 2"
    title: "Freeform chat with AI"
    excerpt: 'Chat with AI in the Unity Editor about anything — ask it to explain code, where to find things in Unity, learn a delicious taco recipe.'
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
  - image_path: /assets/images/landing/ai_toolbox_runtime_inspector_1.png
    alt: "AI in Runtime"
    title: "Use AI in the shipped games, securely."
    excerpt: 'With AI Toolbox you can securely use and remotely control AI in the shipped games. It can be used for anything from NPC dialogue to generating game mechanics.'
    url: "/runtime/"
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_bard:
  - image_path: /assets/images/landing/google_bard_logo_2.svg
    alt: "Google Bard integration"
    title: "Google Bard in Unity"
    excerpt: 'Google Bard intgration expands the palette of the AI tools available in your Unity project.'
    url: "/getting-started/#google-bard"
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_misc_things:
  - image_path: /assets/images/landing/landing_icon_learn_1.svg
    title: "Learn to Code"
    excerpt: 'Understand C# and Unity concepts through generated scripts and freeform chat.'

  - image_path: /assets/images/landing/landing_icon_boost_productivity_1.svg
    title: "Boost Productivity"
    excerpt: 'Speed up development with quick script generation.'

  - image_path: /assets/images/landing/landing_icon_starting_point_1.svg
    title: "Starting Point"
    excerpt: 'Already know coding? Start with generated scripts as a base with boilerplate code.'

  - image_path: /assets/images/landing/landing_icon_rapid_prototyping_1.svg
    title: "Rapid Prototyping"
    excerpt: 'Test ideas and mechanics more efficiently.'

  - image_path: /assets/images/landing/landing_icon_iterative_development_1.svg
    title: "Iterative Development"
    excerpt: 'Generate scripts and iterate on them as needed by editing with the AI.'

  - image_path: /assets/images/landing/landing_icon_fix_errors_1.svg
    title: "Fix code errors with AI"
    excerpt: 'Ask ChatGPT or Google Bard to search for errors in the code and fix them.'
  #  url: "#test-link"
  #  btn_label: "Read More"
  #  btn_class: "btn--primary"

---

{% include feature_row id="intro" type="center" %}
<!--
{% include video_row.html url1='/assets/images/banners/landing-banner-1.mp4' url2='/assets/images/banners/landing-banner-1.mp4' url3='/assets/images/banners/landing-banner-1.mp4' %}
-->
{% include video.html url='/assets/images/banners/landing-banner-1.mp4' %}

{% include feature_row id="feature_video_1" type="center" %}

<div class="youtube-row">
  <div class="youtube-video-tile" width="33%">
    <iframe src="https://www.youtube.com/embed/cNq-uCBq5yU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  </div>
  <div class="youtube-video-tile" width="33%">
    <iframe src="https://www.youtube.com/embed/fedn7A9JTXA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  </div>
  <div class="youtube-video-tile" width="33%">
    <iframe src="https://www.youtube.com/embed/6HlO9LsTLW0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  </div>
</div>
{% include feature_row %}

{% include feature_row id="feature_freeform_chat" type="center" %}

{% include feature_row id="feature_testimonials" %}

{% include feature_row id="feature_runtime" type="center" %}

{% include feature_row id="feature_bard" type="center" %}

{% include feature_row id="feature_misc_things" %}

<div class="buttons-row">
<a href="https://u3d.as/334o?aid=1101lHzQ"><span class="button-landing-large">Get on Asset Store</span></a>
<a href="/overview/"><span class="button-landing-large">Documentation</span></a>
<a href="/contact-details/"><span class="button-landing-large">Contact</span></a>
</div>
