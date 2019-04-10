---
title: "Built-in Contact Form"
subtitle: "Form to email feature powered by Formspree"
excerpt: "This theme has a form-to-email feature built in, thanks to the simple Formspree integration. All you need to activate the form is a valid recipient email address saved in the form front matter."
date: 2019-03-06T08:31:07-06:00
author: "Eric Anderson"
draft: false
images:
  - /blog/assets/built-in-contact-form-thumbnail.png
  - /blog/assets/built-in-contact-form-feature.png
series:
  - Getting Started
tags:
  - hugo-theme
categories:
  - Theme Features
layout: single-sidebar
---

## [Formspree is a form backend, API and email service for HTML forms](https://formspree.io).

### It is a simple and easy way to collect submissions from contact us forms, order forms, or email capture forms on a static site.

---

This theme has a **form-to-email** feature built in, thanks to the simple
Formspree integration. All you need to activate the form is a valid recipient
email address saved in the front matter of the form
(`/content/forms/contact.md`), replace `YOUREMAILHERE` with your uh, email
address.

```toml
# please replace with a valid email address
submission_email_recipient: YOUREMAILHERE
```

Update that file and you're ready to begin receiving submissions. Just submit
the active form for the first time, and complete the email address verification
step with Formspree, and your contact form is live, and the next time someone
fills it out, the submission will land in your inbox.

The files included with the theme have a contact page ready for copy/paste, or
you can type `hugo new forms/contact.md` and you're off to the races. There are two
layouts for `forms` – `split-right`, and `split-left` – you guessed it, one puts
the form on the right and the other on the left. You just fill out the Front
Matter, and the rest is automatic.

```toml
# layout options: split-right or split-left
layout: split-right
```

![Contact Form Split Right Layout Screenshot](/blog/assets/built-in-contact-form-feature.png)

Both layouts display the page title and description opposite the form, and you
can also choose to show your social icon links if you have those configured in
the `config.toml` file.
