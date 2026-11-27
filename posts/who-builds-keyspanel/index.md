---
title: Who builds KeysPanel
description: Meet Codex, the developer behind the KeysPanel website, Telegram bots and reseller API, and how all the pieces connect.
date: 2026-11-27
category: Company
tags: [keyspanel, team, developer]
featured: true
cover: ./file_00000000791c82119d6d23b4e4f27966.png
pinned: 1
authors:
  - username: Codex
    handle: botdevfather
    handleUrl: https://t.me/botdevfather
---

Every time you open the store, tap a button in one of our bots or send a request to our API, you are using something one person built. His name is **Codex**, and on Telegram he is [@botdevfather](https://t.me/botdevfather).

## Meet Codex

Codex is the developer behind KeysPanel. He builds and looks after the parts you actually touch: the website, the Telegram bots and the reseller API, plus the connections that make them work as one system.

If [Jack Senpai and Avijit](/blog/who-is-behind-keyspanel) are the people who answer for every order, Codex is the one who makes sure those orders run smoothly.

## What he builds

### The website

The store at keyspanel.shop, where buyers browse products, pay and see their orders. It also includes the reseller panel, where resellers manage their balance, prices and order history.

### The Telegram bots

Our bots let you buy and get support without leaving Telegram. They follow the same rules as the website, so an order from a bot is handled the same way as an order from the store.

### The reseller API

The API at api.keyspanel.shop lets resellers sell from their own bots and websites automatically. It covers balance, products, orders and purchases, and it uses a simple API key.

```bash:terminal
curl -H "Authorization: Bearer YOUR_API_KEY" https://api.keyspanel.shop/api/v1/products
```

## How it all connects

The website, the bots and the API are not three separate products. They all talk to the same KeysPanel system underneath, so your balance, your orders and your prices are the same wherever you use them.

<Files
  items={[
    { type: "folder", name: "KeysPanel system", isOpen: true, children: [
      { type: "file", name: "Website and reseller panel", highlight: true },
      { type: "file", name: "Telegram bots", highlight: true },
      { type: "file", name: "Reseller API", highlight: true },
    ] },
  ]}
/>

<Note type="note" title="What this means for you">
  Top up your balance on the website and it is ready in the bot. Place an order through the API and it shows up in your order history on the panel. One account, one balance, everywhere.
</Note>

## Why one developer matters

When the same person builds every part, the pieces fit together. A fix or a new feature does not have to be passed between teams. It goes from idea to the website, the bots and the API in one go.

It also means there is a real person who knows exactly how the system works when something needs attention.

## Talk to Codex

You can reach Codex on Telegram at [@botdevfather](https://t.me/botdevfather).

<Note type="warning" title="Check the username">
  The only official account for Codex is @botdevfather. If someone else claims to be the KeysPanel developer, it is not us.
</Note>

For questions about an order, the fastest way is still the [contact page](/contact) or our [Telegram channel](https://t.me/KeyPanel).

@[button](/store "Browse the store")
