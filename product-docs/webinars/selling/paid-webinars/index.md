# Paid webinars and paid registration

Charge people to register for a webinar in EasyWebinar, take payment through Stripe, sell a live-plus-replay bundle, and track every paid registration and transaction.

- Applies to: Paid Webinars add-on · connected Stripe account · live, simulive and evergreen webinars
- Status: Live
- Verified: 2026-10-16
- Canonical page: https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/webinars/selling/paid-webinars/

A paid webinar asks people to pay before they are registered. In EasyWebinar you choose **Paid** when you create the webinar, set a price, and attendees pay through a Stripe checkout on their way to registering. The money goes straight to your own Stripe account, and every payment appears in the webinar's Overview and Analytics. Paid registration launched in **March 2026**.

## At a glance {#at-a-glance}

| | |
|---|---|
| **What it does** | Charges attendees to register for a webinar |
| **Webinar types** | Live, simulive and evergreen; each has the same **Free** or **Paid** pricing step |
| **What you need** | The **Paid Webinars** add-on and a connected **Stripe** account |
| **Price options** | One price, or a second **Live + Replay bundle** option with its own price |
| **Currency** | Set in US dollars; Stripe may show attendees outside the US their local currency |
| **How attendees pay** | Stripe checkout, by card, or Apple Pay or Link where available |
| **Where the money goes** | Directly to your Stripe account; EasyWebinar never holds your funds |
| **Where you see results** | **Overview** (registrants, revenue) and **Analytics → Revenue** (every transaction) |
| **Available since** | March 2026 |

## What paid registration is {#what-it-is}

Paid registration makes payment part of signing up. Instead of a free form that registers someone straight away, the registration page shows your price, the **Register Now** button opens a checkout, and the person is registered only once payment succeeds.

It is different from **selling an offer during a webinar**:

| | Paid registration | Selling an offer in the webinar |
|---|---|---|
| **What is sold** | Access to the webinar itself | Something separate: a course, a programme, a call, a product |
| **When payment happens** | Before the session, at registration | During or after the session |
| **Who pays** | Everyone who attends | Only those who buy |
| **Where it's set up** | The **Pricing** step when you create the webinar | An offer on the **CTAs** tab |
| **Where revenue shows** | **Analytics → Revenue → Paid Webinar** | **Analytics → Revenue → Paid Offer** |

A webinar can do both: charge for entry and sell a follow-on offer inside. EasyWebinar reports the two separately under **Revenue by Source**.

## Why paid webinars matter {#why-it-matters}

### What it's for {#what-its-for}

Paid registration is for webinars that are the product: workshops, masterclasses, paid trainings, seminars and ticketed live sessions. The value is in attending, so access is what you charge for.

### How it helps {#how-it-helps}

- **Payment and registration are one step.** Attendees pay and are registered in the same flow, with their join link on the thank-you page.
- **No separate checkout to stitch together.** You don't have to sell tickets in one tool and add buyers to the webinar by hand in another.
- **Revenue is tracked with the webinar.** Registrants, revenue and every transaction sit in the same place as attendance and engagement.
- **You can sell the replay too.** The **Live + Replay bundle** lets people buy access to the recording at the same time.
- **Payouts are yours.** Payments land in your Stripe account on Stripe's usual payout schedule.

### What happens without it {#without-it}

Without built-in paid registration, a paid event means a separate ticketing or payment page, then moving buyers into the webinar tool, then checking who paid before the session starts. Every handoff is a place where a paying customer can miss their join link, and where your revenue reporting splits away from your attendance data.

### Why buyers care {#why-buyers-care}

For educators, coaches, consultants and businesses that run ticketed sessions, paid registration decides whether a webinar is a cost or a revenue line. Buyers comparing webinar platforms check whether payment is built into registration, which processors are supported, and whether revenue is reported against each webinar.

## Before you begin {#before-you-begin}

- **Add the Paid Webinars add-on.** It's listed under **Settings → Plan → Add-ons** as "Selling access to webinars, with checkout". Charging for a webinar needs it.
- **Connect a Stripe account.** Payments run through Stripe. You can connect it during the pricing step or from **Integrations → Payment**.
- **Choose Paid when you create the webinar.** The price block is added to your registration page at creation. See [Choose Paid at creation](#choose-paid-at-creation).

## Set your price {#set-your-price}

Create a webinar as usual: **My Webinars → Create a Webinar → Create Manually**, name it and choose a type. On **Step 3 of 4: Pricing**, choose **Paid**.

![Step 3 of Create Webinar with Paid selected](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/images/paid-registration/step-01-set-a-price.png)

| | Setting | What to do |
|---|---|---|
| 1 | **Paid** | Charge attendees to register |
| 2 | **Pricing title** and **description** | What the attendee is buying, for example "General Admission". Both appear on your registration page and at checkout |
| 3 | **Live webinar price** | The price in US dollars |
| 4 | **Payments** | The Stripe account that receives the money. Shows **connected** once linked |
| 5 | **Live + Replay bundle** | Turn on to sell a second option that includes the replay recording, with its own price |

If Stripe isn't connected yet, a **Payments · Action required** panel appears with **Connect with Stripe**.

Continue to choose a registration template and click **Create Webinar**. The template you pick includes the price automatically. You can switch back to **Free** at any point before creating the webinar.

### Pricing on simulive and evergreen webinars {#pricing-recorded-webinars}

Simulive and evergreen webinars have the same **Free** or **Paid** choice. On those types, the pricing step comes after the schedule and before **Continue to Video Selection**, where you pick the recording the sessions will play.

### Sell the replay with a bundle {#live-replay-bundle}

Turn on **Live + Replay bundle** to offer two choices on the registration page: the live webinar alone, or the webinar plus its recording, each at its own price. It suits people who want to attend but also keep the session to watch again, and people who can't make the live time.

If you sell replay access, set how long the replay stays open on the **Replay** tab: **Always Available**, **Expire after days** or a **Specific date**. Make sure the bundle's description matches that setting.

## What attendees see {#what-attendees-see}

### The registration page {#registration-page}

The registration page shows the price above the form.

![A paid registration page](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/images/paid-registration/step-02-registration-page.png)

| | Area | What it does |
|---|---|---|
| 1 | **Price option** | The pricing title, description and price, selected by default. With a Live + Replay bundle there are two options to choose from |
| 2 | **Register Now** | Takes the attendee to checkout instead of registering them straight away |

### Checkout {#checkout}

The attendee lands on a Stripe checkout page showing your business name and the webinar as the item. They can pay by card, or by Apple Pay or Link where available. Their email is carried over from the registration form, so they don't type it twice.

Attendees outside the US may be offered the price in their own currency alongside the dollar price. Stripe handles the conversion.

### Confirmation and calendar invites {#confirmation-and-calendar}

Once payment goes through, the attendee is registered and sent to your thank-you page.

![The thank-you page after a successful payment](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/images/paid-registration/step-04-thank-you.png)

| | Area | What it shows |
|---|---|---|
| 1 | **Webinar join link** and **Join Room** | The attendee's personal link to the webinar |
| 2 | **Date** and **Add to Calendar** | The session they booked, with Google, Outlook and Apple calendar buttons |

They also receive your **Registration Confirmation** email, which carries their join link, and your reminders before the session.

## See what you've earned {#see-what-youve-earned}

### On the Overview tab {#earned-on-overview-tab}

![The Overview tab of a paid webinar](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/images/paid-registration/step-05-overview.png)

| | Area | What it shows |
|---|---|---|
| 1 | **Registrants** | Everyone who has registered and paid |
| 2 | **Revenue** | Total taken for this webinar |
| 3 | **Registration Pricing** | Your pricing title and price. The pencil edits them |
| 4 | **Payment Gateway** | The connected Stripe account. **Manage** opens your payment settings |

### In Analytics {#earned-in-analytics}

Open the webinar's **Analytics** tab, then **Revenue**.

![Analytics, Revenue view](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/images/paid-registration/step-06-revenue.png)

| | Area | What it shows |
|---|---|---|
| 1 | **Revenue** | The revenue view for this webinar |
| 2 | **Total Revenue** and **Paid Registrations** | Everything earned, and the part that came from registrations |
| 3 | **Revenue by Source** | The split between paid registrations and offers sold in the room |
| 4 | **Paid Webinar** | Switches the section below to registration payments: completed, pending and abandoned checkouts, and every transaction |

The transaction list shows each buyer's name, email, session, registration date, amount and status. You can search it and filter by status.

#### Transaction statuses {#transaction-statuses}

Each transaction shows one of these statuses: **Pending**, **Processing**, **Success**, **Failed**, **Canceled**, **Refunded** or **Partially Refunded**. An attendee is registered once their payment succeeds.

#### Abandoned checkouts {#abandoned-checkouts}

**Checkout abandoned** counts people who reached checkout but didn't pay. They aren't registered. It is a useful number to watch: a high count points to the price, the checkout step, or a mismatch between the registration page and what checkout shows.

## How paid webinars work with other features {#works-with}

### Offers inside a paid webinar {#with-offers}

A paid webinar can still sell. Add offers on the **CTAs** tab, with an optional price and [countdown timer](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/webinars/engagement/countdown-timers/), and offer sales are reported under **Paid Offer**, separately from registration revenue. Buyers of an offer receive the **Paid Offer — Transaction Success** email.

### Replays {#with-replays}

With the replay page set to **Webinar Replica**, the recording shows the same video, offers, polls and chat replay as the session. Replay availability is set on the **Replay** tab, and **After the replay ends** under Redirects can send viewers to your next offer.

### Emails {#with-emails}

Paid registrants get the same **Registration Confirmation**, **Webinar Reminders** and **Webinar Follow-ups** as everyone else, all set on the **Notifications** tab. Reminders are timed relative to the webinar, so they work for recurring and evergreen schedules too.

### CRM and email tools {#with-crm}

A connected CRM or email tool can tag paid registrants as they sign up (the **Registered** event), and tag what they did in the session, from **Attended** and **Missed** to **Watched full** and **Clicked offer**. Map the **Webinar Join Link** into a CRM field if you want to send reminders from your own system. See [Connect a CRM and map your webinar data](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/integrations/map-webinar-data/).

### People view {#with-people-view}

**People** in the sidebar lists every registrant across your webinars. Filter by webinar, behaviour or source, then **Export** to work with a list of paid attendees elsewhere.

### Create with AI {#with-create-with-ai}

Webinars built with **Create with AI** have the same pricing step and behave like any other once created. Include who the webinar is for and what you are selling in your prompt so the pages and emails it writes fit a paid event, and read the generated copy before you publish, especially around price and what's included.

## Who uses paid webinars, and how {#who-uses-it}

These patterns show how paid registration fits different kinds of webinars.

### Paid workshops and masterclasses {#paid-workshops}

A coach or educator runs a live, ticketed workshop. The registration page sells a general admission ticket, the **Live + Replay bundle** sells the recording to people who can't attend live, and the confirmation page gives each buyer their join link and calendar buttons.

### Course creators {#course-creators}

A creator charges a small fee for a live training that previews a full course, then presents the course itself as an offer inside the session. Registration revenue and course sales appear separately under **Revenue by Source**. See [Course creators](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/use-cases/sell-courses/).

### Evergreen paid trainings {#evergreen-paid}

A recorded training is sold on an evergreen schedule, so people pay and watch at a session time that suits them. The same pricing step applies, and every purchase lands in **Analytics → Revenue**.

### Professional education {#professional-education}

Educators in fields such as real estate, finance or wellness run paid seminars. Paid registration keeps the attendee list limited to people who paid, and the transaction list gives a record of every purchase.

## Choose Paid at creation {#choose-paid-at-creation}

> **Choose Paid when you create the webinar**
> The Overview tab has a **Convert to paid** button for free webinars. If you convert an existing free webinar to paid, its registration page keeps the free form, so people can still register without paying. Create a new webinar and choose **Paid** on the pricing step instead.


## Limits and things to know {#limits}

- **Prices are set in US dollars.** Stripe may present a local-currency price to attendees outside the US.
- **Stripe is the payment processor** for paid registration.
- **Payouts follow Stripe's schedule.** EasyWebinar doesn't hold or pay out funds.
- **An abandoned checkout isn't a registration.** Only a successful payment registers someone.
- **You can change the price later** with the pencil on **Registration Pricing** in the Overview tab.
- **Registration and offer revenue are reported separately**, under **Paid Webinar** and **Paid Offer**.

## Common questions {#common-questions}

#### Which payment provider does EasyWebinar use for paid registration? {#faq-payment-provider}

Stripe. Connect your Stripe account on the pricing step or from **Integrations → Payment**.

#### Do I need an add-on? {#faq-add-on}

Yes. Charging for a webinar needs the **Paid Webinars** add-on as well as a connected Stripe account. If the paid option isn't behaving as expected, check **Settings → Plan → Add-ons** first.

#### When do I get the money? {#faq-payouts}

Payments go straight to your Stripe account, and Stripe pays out to your bank on its usual schedule.

#### Can I sell access to the replay as well? {#faq-replay-bundle}

Yes. Turn on **Live + Replay bundle** on the pricing step and set a second price.

#### What currency are prices in? {#faq-currency}

You set the price in US dollars. Stripe may show attendees outside the US the price in their local currency.

#### How can attendees pay? {#faq-payment-methods}

By card, or by Apple Pay or Link where available, on Stripe's checkout page.

#### Can I change the price later? {#faq-change-price}

Yes. Use the pencil on **Registration Pricing** in the Overview tab.

#### Is someone registered if they close checkout without paying? {#faq-abandoned}

No. They appear under **Checkout abandoned**, not as a registrant.

#### Where can I see who has paid? {#faq-who-paid}

**Analytics → Revenue → Paid Webinar** lists every transaction with its status. The Overview tab shows the total registrants and revenue.

#### Can I charge for an evergreen or simulive webinar? {#faq-recorded}

Yes. Both have the same **Free** or **Paid** pricing step when you create them.

#### Can I sell something else during a paid webinar? {#faq-offers-in-paid}

Yes. Add an offer on the **CTAs** tab. Offer sales are reported under **Paid Offer**, separately from registration revenue.

#### What do attendees get after paying? {#faq-after-paying}

The thank-you page shows their personal join link, a **Join Room** button, the session date and **Add to Calendar** buttons for Google, Outlook and Apple. They also get your confirmation email.

#### Can I make a free webinar paid later? {#faq-convert}

The Overview tab has a **Convert to paid** button, but the registration page of a converted webinar keeps the free form. Create a new webinar and choose **Paid** on the pricing step instead.

## Related {#related}

- [Countdown timers](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/webinars/engagement/countdown-timers/)
- [Offers](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/webinars/engagement/timed-offers/)
- [Course creators](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/use-cases/sell-courses/)
- [Create and schedule a live webinar](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/webinars/getting-started/create-a-live-webinar/)
- [Limits and defaults](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/reference/limits-and-defaults/)
- [Connect a CRM and map your webinar data](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/integrations/map-webinar-data/)
