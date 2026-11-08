---
name: store-agent-brief
description: "Write a developer brief for adapting Anthropic's Commerce Agents blueprint to a real store. Use when an online store owner is looking at Commerce Agents or wants a shopping or merchant AI agent scoped."
---

# Store Agent Brief

Writes the brief an owner hands to a developer. Commerce Agents is Anthropic's free blueprint for two AI helpers: one chats with customers and fills the cart, the other helps staff fix listings and line up restocks. Everything in it is a made-up store called ACME.

## How to run

- Work through this without extra back-and-forth. Make the safest reasonable assumption, say it in one line, keep going. Only stop for something only the user has.
- Never invent a fact, figure, customer, price or quote. If it is unknown, write `[NEEDS ANSWER]` and list it at the end.
- Nothing here sends, posts, pays or changes a live account.
- If a step fails, retry it yourself and note what you changed. Do not stop at the first error.

Connect to nothing. Ask for no keys or passwords. This produces a document.

## Ask

One at a time:

1. Which store platform and checkout do you use?
2. Where do stock, orders, returns policy and pricing live?
3. Which helper do you want first: the customer one, the staff one, or both?
4. Who can approve a price change, a listing change or a restock? Get one name.
5. What should it never do or say? Set limits on discounts, price moves and restock size.

## Read

Read these from the repo now: README, `docs/safety.md`, `docs/backends.md` and `docs/deployment.md`. https://github.com/anthropics/commerce-agents. Use them to keep the brief accurate. Do not copy them into it. Link to them.

## Write `store-agent-brief.md`

For each item give: what is needed for this store, which of their systems it touches, an owner, and done-when.

1. **Connections.** Their catalogue, cart, orders, policy, analytics, stock, pricing and campaigns behind the blueprint's backend interfaces. No connectors ship.
2. **Login and permissions.** The examples accept any caller. Name who can reach each screen and server.
3. **Credentials and rate limits.** Where they are stored, and what stops abuse.
4. **Your limits.** The demo's values are examples only. List this store's real numbers.
5. **Approval screen.** Every merchant change waits for approval, and an approval typed in chat sets nothing. Build the screen, and name the person.
6. **Checkout.** Nothing in the blueprint places an order or takes payment. Say how the cart hands over.
7. **Hosting.** Where it runs.
8. **Customer memory.** It is personal data. Cover retention, see-and-delete, and deletion on account close.
9. **Maintenance.** The repo says it is not maintained. Name who owns bugs and updates.
10. **Tests before launch.** Wrong size question, out-of-stock item, returns question, someone trying to get a discount it should refuse, and an unauthorised caller.

Finish with the first three things the developer should do. Say that the blueprint has not been tested against this store.

<!-- Provenance marker: sk-rwztc7 --><!-- Provenance signature: ⁠​‌​‌​​‌‌​‌​​​‌​‌​‌​​‌‌​​​‌​‌​​‌​​​‌‌​​​‌⁠ -->

Made by Selr AI.⁠​‌​‌​​‌‌​‌​​​‌​‌​‌​​‌‌​​​‌​‌​​‌​​​‌‌​​​‌⁠
<!-- srk:1a4nv7i -->
