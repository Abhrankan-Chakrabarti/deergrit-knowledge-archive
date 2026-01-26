# DEERGRIT — Knowledge Archive

DEERGRIT is a **static, read-only knowledge archive** designed to be hosted as a **Tor onion service**.
Its purpose is to explain how modern digital systems work, in a calm, factual, and accessible way.

The project focuses on topics that are often misunderstood or left unexplained, such as how the internet functions, how data is collected, how attention is shaped online, how digital infrastructure concentrates power, and how to think critically in digital spaces.

DEERGRIT does **not** aim to persuade, campaign, or promote any ideology.
It exists purely as an educational resource.

---

## What DEERGRIT Is

* A static HTML website (no backend, no JavaScript)
* Onion/Tor-friendly by design
* Read-only and privacy-respecting
* Focused on digital literacy and understanding systems
* Intended as a long-lived public archive

---

## What DEERGRIT Is Not

* Not a personal blog
* Not a political platform
* Not a whistleblowing or leak site
* Not a data-collecting service
* Not interactive or user-tracking

---

## Project Structure

```

deergrit/
├── index.html
├── about.html
├── topics.html
├── disclaimer.html
└── pages/
├── how-the-internet-works.html
├── how-data-is-collected.html
├── how-attention-is-engineered.html
├── surveillance-basics.html
├── digital-infrastructure-and-power.html
└── thinking-critically-online.html

```

All pages are written in plain HTML with inline CSS and include a disclaimer link in the footer.

---

## Deployment (Tor Onion Service)

DEERGRIT is designed to be deployed as a Tor hidden service using any standard web server (e.g., Apache or Nginx).

Basic steps:

1. Place the `deergrit/` directory inside your web server’s document root
2. Configure a Tor onion service pointing to that directory
3. Restart Tor and your web server
4. Access the site using Tor Browser

No additional dependencies are required.

---

## License

This project is released under **Creative Commons Zero v1.0 Universal (CC0)**.

You are free to copy, modify, distribute, and use this work for any purpose, without asking permission.
