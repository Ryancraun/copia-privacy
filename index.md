---
title: Copia Privacy Policy
---

# Privacy Policy

**Effective date: September 23, 2026**

Copia is a grocery list and recipe app. This policy explains what the app collects, why, and what happens to it.

The short version: Copia collects the minimum needed to sign you in and sync your lists across your devices and with people you share lists with. There is no advertising, no tracking, no analytics SDK, and nothing is sold or shared with data brokers.

---

## Who we are

Copia is developed by Ryan Craun.

Contact: craunryan@gmail.com

---

## What we collect

### Account information

When you create an account, we collect your **email address**. This is used to sign you in, to verify your account, to let you reset your password, and to allow other people to invite you to a shared list.

If you sign in with Apple, you may choose to hide your email address. In that case we receive a private relay address from Apple rather than your real one, and that relay address is what we store.

During signup you may optionally opt in to receiving product update emails. This is off by default. You can change it at any time, and it has no effect on your ability to use the app.

### Your content

Copia stores the lists, items, quantities, categories, and saved recipes you create. If you use sync or share a list, this content is stored on our servers so it can reach your other devices and the people you have shared with.

### Shared list information

Copia lets you invite other people to a list by email address. If you do this, or if someone invites you:

- The other members of that list can see the list's contents and any changes you make to it.
- When you check an item off a shared list, your name is recorded and shown to the other members so they know it was handled.
- Being invited to a list does not require your approval. If someone knows the email address on your account and invites it to a list, that list will appear in your app. You can leave any shared list at any time, which removes your access and removes you from its member roster.

We only use an invited email address to deliver that specific invitation. We do not use it for marketing and we do not add it to any other list.

### Purchases

Copia offers optional paid subscriptions and a one-time lifetime option. **All payments are handled entirely by Apple.** We never see, receive, or store your payment card, billing address, or Apple ID credentials. We receive only a confirmation from Apple of whether your account currently has an active entitlement.

---

## What stays on your device

Some of the most sensitive processing in Copia never leaves your phone:

- **Recipe scanning.** When you photograph a recipe, the images are processed on your device. Text recognition and ingredient extraction — including any processing done through Apple Intelligence — happen locally. **The photographs themselves are never uploaded to our servers.** Only the resulting ingredient list, which becomes part of your list content, is stored and synced.
- **Dish photos.** When you photograph a dish for Ask Copia, Apple's Vision framework reads it on your device to work out what the dish is. The photo is not uploaded unless you have turned on smarter answers, have Copia Pro, and are using that photo to ask; see "AI features" below.
- **Camera and photo library access.** Copia requests access only when you use the scanning or dish-photo features, and uses it only for those purposes.

---

## AI features

Ask Copia is the assistant on the Recipes tab. It answers questions like "burgers tonight" by picking recipes from Copia's own catalogue and turning them into a list.

**By default it runs on your iPhone.** Where your phone has Apple's on-device model, that writes the answer; everywhere else, Copia searches its bundled recipe catalogue and answers from that. Nothing leaves the device.

**Smarter answers are optional and off until you say yes.** Some versions of Copia can send your question to a server for a better answer. Before the first such request, the app asks for your permission and explains exactly what will be sent. If you decline, Ask Copia keeps working using only your iPhone. You can turn smarter answers on or off at any time in Settings.

When smarter answers are on, each question sends:

- **What is sent:** the text of your question, the titles and ingredient lists of up to twelve matching recipes from Copia's catalogue, the last few turns of that conversation, and, only if you have Copia Pro and used a photo for that question, a reduced-size copy of the dish photo.
- **What is not sent:** your name, email address, account, lists, list contents, location, or any device identifier. The only extra value sent is a random number the app makes up once, used to limit how many requests a day one install can make. It is not linked to your account and you can reset it by reinstalling.
- **To whom:** Copia's own server (hosted on Supabase), which forwards the request to **Anthropic** (the Claude model) to write the reply. The request is sent under Copia's account with Anthropic, not yours. Under Anthropic's commercial API terms, Anthropic does not use this content to train its models.
- **Why:** to write the answer, choose which of the candidate recipes fit, and suggest follow-up questions. That is the only purpose.
- **Retention:** Copia's server does not store your questions, answers, or photos. It keeps a daily count of requests per random install number, which is discarded after the day ends.
- **Not tracking:** none of this is used for advertising, profiling, or tracking, and none of it is sold or shared beyond the provider that writes the answer.

**Recipes Copia writes.** When no recipe in the catalogue fits, the AI may write a new one. It is stored on Copia's server so others can find it, and it contains only the recipe: title, ingredients, steps and times. It is never linked to you, your question, or your device.

**Filtering and reporting.** Ask Copia answers only about recipes and grocery lists; questions or answers containing objectionable language are blocked. The flag at the top of each chat reports the conversation. A report sends only the identifiers of any recipes Copia wrote in that chat, never your messages; recipes that are reported repeatedly are hidden and reviewed. You can also reach us at craunryan@gmail.com.


Copia relies on a small number of third parties to function:

- **Supabase** — hosts our database and handles authentication. Your account and your synced content are stored there. Access is restricted by row-level security so that you and the members of your shared lists are the only people who can read your lists.
- **Apple** — handles Sign in with Apple, App Store purchases, and subscription management, under [Apple's own privacy policy](https://www.apple.com/legal/privacy/).
- **Recipe search providers** — when you search for a recipe, your search terms are sent to third-party recipe services to return results. Your account identity is not sent with these searches.
- **Anthropic (AI provider)** — only if you turn on smarter answers in Ask Copia. Your question and matching recipe titles are forwarded through Copia's server to Anthropic's Claude to write the reply, under Copia's own API account. See "AI features" above for exactly what is and is not sent.

We do not use advertising networks, analytics SDKs, or tracking frameworks. Copia does not track you across other apps or websites, and we do not sell or rent your information to anyone.

---

## How long we keep it

Your account and content are kept for as long as your account exists.

You can delete your account at any time from within the app, under Settings. Deleting your account removes your account record and your personal lists from our servers.

One exception worth understanding clearly: **a shared list belongs to its members, not to any one person.** If you delete your account while other people are still members of a list you shared with them, your membership is removed and your name stops appearing on it, but the list itself continues to exist for those remaining members. This is deliberate — deleting your account should not delete other people's lists out from under them.

---

## Security

Your session tokens are stored in the iOS Keychain. All communication between the app and our servers is encrypted in transit. Server-side access controls ensure your lists are readable only by you and by the members of lists you belong to.

No system is perfectly secure, but we do not collect data we do not need, which is the most reliable protection there is.

---

## Children

Copia is not directed at children under 13, and we do not knowingly collect information from children under 13. If you believe a child has provided us with personal information, contact us and we will delete it.

---

## Your rights

You can:

- **Access** your data — it is visible in the app, and you can request an export by contacting us.
- **Correct** it — edit your lists and account details directly in the app.
- **Delete** it — delete your account from within the app, as described above.
- **Withdraw marketing consent** — at any time, in the app or via the unsubscribe link in any email.

Depending on where you live, you may have additional rights under laws such as the GDPR or the CCPA. Contact us and we will honor them.

---

## Changes to this policy

If we make a material change to this policy, we will update the effective date at the top and, where the change is significant, notify you in the app.

---

## Contact

Questions about this policy or your data: craunryan@gmail.com
