---
title: Who is behind KeysPanel
description: The people who run KeysPanel, what we actually do as a middleman, and how we keep every order safe for buyers and resellers.
date: 2026-11-27
category: Company
tags: [keyspanel, team, about]
featured: true
cover: ./file_0000000045d882119abadc3e22249f16.png
trending: true
pinned: 2
authors:
  - username: Jack Senpai
    handle: KeysPanel
    handleUrl: https://t.me/KeysPanel
  - username: Avijit
    handle: A_bhijeeeet
    handleUrl: https://t.me/A_bhijeeeet
---

People often ask us one simple question before their first order: **who is actually running this?** Fair question. When you buy a digital key or an account online, you want to know there are real people on the other side. So here is the honest answer.

## Two people, one rule

KeysPanel is run by two people: **Jack Senpai** (the founder, on Telegram as [@KeysPanel](https://t.me/KeysPanel)) and **Avijit** (the co-founder, on Telegram as [@A_bhijeeeet](https://t.me/A_bhijeeeet)). We built it because buying cheap keys and accounts online usually means trusting a stranger and hoping for the best. We wanted a place where that trust problem is solved by a middleman who answers for every order.

That is the one rule we run by: **if an order goes wrong, it is our problem, not yours.**

<Note type="note" title="Why a middleman">
  Sellers and resellers list products on KeysPanel. Buyers pay KeysPanel, not the seller directly. We only release the order when it checks out, and we handle the support if something breaks.
</Note>

## What we actually do

KeysPanel is more than a website. Behind it there are a few connected pieces:

- **The store** at keyspanel.shop, where anyone can buy keys and accounts.
- **The reseller panel**, where resellers get their own prices, balance and order history.
- **The reseller API** at api.keyspanel.shop, so resellers can sell from their own bots and sites automatically.
- **Telegram bots**, for people who prefer to buy and get support right inside Telegram.

<Files
  items={[
    { type: "folder", name: "KeysPanel", isOpen: true, children: [
      { type: "file", name: "Store (keyspanel.shop)", highlight: true },
      { type: "file", name: "Reseller panel" },
      { type: "file", name: "Reseller API (api.keyspanel.shop)" },
      { type: "file", name: "Telegram bots" },
    ] },
  ]}
/>

## How an order works

<Stepper>
  <StepperItem title="You place the order">
    Pick a product and pay through the store, the API or a bot.
  </StepperItem>
  <StepperItem title="We hold the payment">
    Your money stays with KeysPanel. The seller does not get it yet.
  </StepperItem>
  <StepperItem title="You get your key or account">
    Delivery is shown on your orders page, with everything you need to use it.
  </StepperItem>
  <StepperItem title="We stay on the hook">
    If something does not work, contact us. We sort it out with the seller so you do not have to.
  </StepperItem>
</Stepper>

## For resellers

Resellers get their own balance, their own price list and full API access. Prices for resellers can be shown in dollars, while balances stay safely stored in rupees, and every order keeps the exact rate it was placed at, so your history never changes on you.

<Tabs defaultValue="panel">
  <TabsList>
    <TabsTrigger value="panel">Panel</TabsTrigger>
    <TabsTrigger value="api">API</TabsTrigger>
  </TabsList>
  <TabsContent value="panel">
    Log in, add balance, and order from the reseller catalog at your own prices.
  </TabsContent>
  <TabsContent value="api">
    Use your API key to check your balance, list products and place orders from your own bot or website.

    ```bash
    curl -H "Authorization: Bearer YOUR_API_KEY" https://api.keyspanel.shop/api/v1/balance
    ```
  </TabsContent>
</Tabs>

## Our official links

These are the only official KeysPanel accounts. If this list ever changes, we will update it here first.

| What | Where |
| --- | --- |
| Telegram channel | [t.me/KeyPanel](https://t.me/KeyPanel) |
| Telegram bot | [@KeysPannelBot](https://t.me/KeysPannelBot) |
| Jack Senpai (founder) | [@KeysPanel](https://t.me/KeysPanel) |
| Abhjeet (co-founder) | [@A_bhijeeeet](https://t.me/A_bhijeeeet) |
| Order proofs | [@KeysPanelProofs](https://t.me/KeysPanelProofs) |
| Website | [keyspanel.shop](https://keyspanel.shop) |

<Note type="warning" title="Watch out for fakes">
  We will never message you first from an account that is not on this list. If someone claims to be KeysPanel, Jack Senpai or Avijit from any other username, it is not us. Check the handle carefully before you pay anyone.
</Note>

You can see real orders and deliveries from our customers in the [@KeysPanelProofs](https://t.me/KeysPanelProofs) channel.

## Talk to us

We read every message. If you have a question about an order, want to become a reseller, or just want to say hello, reach out from the [contact page](/contact) or join our [Telegram channel](https://t.me/KeyPanel).

@[button](/become-a-reseller "Become a reseller")

<Note type="success" title="Thank you">
  Every order, every reseller and every piece of feedback is the reason KeysPanel keeps getting better. Thank you for trusting us.
</Note>
