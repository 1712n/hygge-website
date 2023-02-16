---
title: "Security"
authors: ["ev"]
date: 2022-03-21T12:00:00Z
menu:
  sidebar:
    parent: tools
weight: -100
tags:
  - tools
  - "first steps"
---

![Security](/img/tools/security.png)

Nothing will make you 100% safe. The goal is to make the attack prohibitively expensive. Below are the collection of simple tools and steps you can take to make yourself much safer.

To start, use dedicated devices for work or, at least, create a different user profile to isolate work resources from your personal account.

## VPN

Whether you live in a country that likes to filter traffic or just want to use non-secure WiFi networks, a good VPN is a must. Unlike what you read on the internet, most of the commercial VPN IP addresses are known to network monitoring tools and reputation-based security systems. Reach out to your admins and ask them to set you up with a dedicated WireGuard tunnel that won't mix your traffic with hackers and dissidents.

## Passwords

Avoid them if you can. Always opt-in for "Sign-in with Google" or other identity providers. They tend to have much better operational security and have much more to lose in case of a breach than just your data.

### LastPass

For situations when you have to generate, store, and possibly share credentials, use one of the more known password managers, such as [LastPass](https://www.lastpass.com/). When setting up various account credentials, don't forget to opt-in for multifactor authentication option and install LastPass Authenticator app to generate time codes. No, SMS is not a reliable second factor.

## NoScript

Whitelisting JavaScript through [NoScript](https://noscript.net/) browser extensions is a free and extremely powerful layer of security when browsing the web.
