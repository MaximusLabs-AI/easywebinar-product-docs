# Just-in-time webinars

How Just-in-time Registration works on EasyWebinar's evergreen webinars, which interval to choose, how it handles each attendee's local time, and how to test it.

- Applies to: Evergreen webinars
- Status: Live
- Verified: 2026-10-16
- Canonical page: https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/product-docs/webinars/automated/just-in-time/

**Just-in-time Registration** is an evergreen schedule option that offers each visitor a session starting a few minutes after they register, rather than at a fixed future time. You choose how often these sessions come round, from every 2 minutes to every hour, and each just-in-time session runs in the attendee's own local time. It is the setting that lets someone who finds your registration page be watching your webinar shortly afterwards.

## At a glance {#at-a-glance}

| | |
|---|---|
| **What it does** | Offers a session starting shortly after someone registers |
| **Where it's set** | The schedule step of an evergreen webinar |
| **Webinar types** | Evergreen |
| **Interval options** | 2, 15, 30, 45 or 60 minutes |
| **Keeping hours clear** | **Exclude specific time** |
| **Timezone** | Each attendee's local time; the Overview shows **Attendee's local timezone** |
| **Combines with** | **On Demand** and **Recurring Schedule** on the same webinar |
| **Also called** | JIT |

## What just-in-time is {#what-it-is}

A conventional webinar session sits at a time you chose in advance. A just-in-time session is generated around the person registering: EasyWebinar offers them a session that begins shortly, on a cycle set by the **Interval**.

Someone who arrives at your page at 2:07 can be watching by 2:15, instead of waiting until tomorrow. The recording is the same one your other evergreen sessions play; only the start time changes.

Just-in-time is one of three ways an evergreen webinar can be watched:

| Option | When the registrant watches | Timezone |
|---|---|---|
| **Just-in-time Registration** | A few minutes after registering | The attendee's local time |
| **On Demand** | Immediately, with no session | Not tied to a session time |
| **Recurring Schedule** | At set daily or weekly times | The webinar's timezone |

You can run all three together, and the registration page offers each as a choice.

## Why just-in-time matters {#why-it-matters}

### What it's for {#what-its-for}

Just-in-time is for [evergreen webinars that sit in a funnel](https://easywebinar.com/automated-webinars/): a [demo behind a website button](https://easywebinar.com/use-cases/product-demos/), a teaching session in front of an [offer](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/product-docs/webinars/engagement/timed-offers/), an [onboarding session](https://easywebinar.com/use-cases/onboard-train-customers/) new customers reach from an email. In each case the visitor is interested now, and the webinar should be available now.

### How it helps {#how-it-helps}

- **It removes the wait.** A session is always a few minutes away, so a visitor doesn't have to plan to come back.
- **It catches interest at its peak.** The person registering has just decided they want to watch; a short interval lets them do so while that's still true.
- **It suits a spread-out audience.** Because sessions follow each attendee's local time, you don't have to pick slots region by region.
- **It keeps a scheduled feel.** Unlike On Demand, there is still a start time, so attendees turn up for a session that begins at a set moment.

### What happens without it {#without-it}

With only recurring times, a visitor who arrives just after a session has started faces a wait until the next slot, which may be hours or a day away. The [gap between interest and watching](https://easywebinar.com/blog/improve-webinar-attendance/) is where people disappear: they close the tab meaning to return, and many don't.

### Why buyers care {#why-buyers-care}

For teams who [measure an evergreen webinar by how many registrants actually watch](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/product-docs/webinars/analytics/webinar-analytics/#read-the-funnel), the time between registering and the session starting matters. Just-in-time shrinks it to minutes, using the same recording and the same funnel.

## Set it up {#set-it-up}

### On a new evergreen webinar {#set-up-new}

1. On **My Webinars**, click **Create a Webinar**, then **Create Manually**.
2. Name the webinar, choose **Evergreen Webinar** and click **Continue to Schedule**.
3. Switch on **Just-in-time Registration**.
4. Choose an **Interval**: 2, 15, 30, 45 or 60 minutes.
5. Set **Exclude specific time** if there are hours when no session should start.
6. Set up any other options you want alongside it: **On Demand**, **Recurring Schedule**, **Availability** and **Schedule Preferences**.
7. Click **Continue to Pricing** and finish the remaining steps.

![The evergreen schedule step with Just-in-time Registration switched on and its Interval and Exclude specific time settings, next to On Demand, Recurring Schedule, Availability and Schedule Preferences](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/images/evergreen/step-01-schedule.png)

*1 Just-in-time Registration · 2 On Demand · 3 Recurring Schedule · 4 Availability · 5 Schedule Preferences.*

The full creation walkthrough, including pricing, video selection and templates, is in [Create an evergreen webinar](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/product-docs/webinars/getting-started/create-an-evergreen-webinar/).

### On an existing evergreen webinar {#set-up-existing}

Open the webinar's **Overview** tab and use the options menu on the **Scheduling Options** panel. That menu changes the schedule for the whole webinar rather than for a single session.

### Settings {#settings}

| Setting | Options | What it controls |
|---|---|---|
| **Just-in-time Registration** | On or off | Whether the registration page offers a session starting shortly |
| **Interval** | 2, 15, 30, 45 or 60 minutes | How often just-in-time sessions come round |
| **Exclude specific time** | Hours you want kept clear | Hours kept free of just-in-time sessions |
| **Schedule Preferences** | Depends on what's enabled | How many choices registrants see; with On Demand also on, it reads **Display Just-in-time & Instant-replay** |

### Choosing an interval {#choosing-an-interval}

Shorter intervals mean less waiting. The interval is the longest a new registrant waits for the next just-in-time session, so 2 minutes keeps the wait to a couple of minutes and 60 minutes can mean close to an hour.

Two minutes is also the setting to use when you want to check the webinar yourself, because a session starts almost as soon as you register. See Test a just-in-time session, below.

## Timezones: who sees which time {#timezones}

Just-in-time is the only kind of session in EasyWebinar that follows each attendee's own local time. Everything else runs in the webinar's timezone:

| Session | Runs in |
|---|---|
| Just-in-time sessions on evergreen webinars | The attendee's local time |
| Recurring daily or weekly evergreen sessions | The webinar's timezone |
| [Simulive sessions](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/product-docs/webinars/getting-started/create-a-simulive-webinar/#set-schedule) | The webinar's timezone |
| [Live sessions](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/product-docs/webinars/getting-started/create-a-live-webinar/#timezone) | The webinar's timezone |

When just-in-time is on, the **Scheduling Options** panel on the Overview tab shows the timezone as **Attendee's local timezone**.

![An evergreen webinar's Overview with Scheduling Options showing Attendee's local timezone and Display Just-in-time & Instant-replay, above the generated Sessions list](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/images/evergreen/step-02-overview.png)

*1 Scheduling Options · 2 Sessions.*

> **The schedule step's timezone message**
> On the schedule step, EasyWebinar shows a message saying attendees will see times in their local time based on the selected timezone. On an evergreen webinar, that's true of just-in-time sessions only. Recurring daily and weekly sessions run at the times you set in the webinar's timezone.


## Test a just-in-time session {#test-it}

A recorded webinar has no live room for you to enter, so you check it by joining a running session. The quickest way to get one is to register yourself.

1. Set the **Interval** to 2 minutes, the shortest option.
2. Open your [registration page link](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/product-docs/webinars/registration/sharing-links/#registration-page-link) and register as an attendee.
3. On the webinar's **Overview**, open the **Live** tab in the **Sessions** panel. A session on air appears there marked *Live now*, with **Enter room**.
4. Join as an attendee to see what your audience sees.

Set the interval back to your chosen value once you're done.

## How just-in-time works with other features {#works-with}

### On Demand {#with-on-demand}

**On Demand** lets registrants watch immediately, with no session at all. Pair it with just-in-time and registrants choose between "now" and "in a few minutes". See [On Demand](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/product-docs/webinars/on-demand/).

### Recurring Schedule {#with-recurring}

A daily or weekly **Recurring Schedule** can run alongside just-in-time, for registrants who prefer to book a set time. Those sessions use the webinar's timezone.

### Sessions on the Overview tab {#with-sessions}

Evergreen webinars have a **Live** tab in the Sessions panel, alongside **Upcoming**, **Past** and **Cancelled**, showing sessions currently on air. See [The Overview tab](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/product-docs/webinars/setup/overview-tab/).

### Chat Simulation {#with-chat-simulation}

Just-in-time attendees arrive at different moments, so there's no shared conversation to join. **Chat Simulation** on the **Engagement** tab fills the chat with an AI-generated or CSV-scripted conversation timed against the video. See [Chat simulation](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/product-docs/webinars/engagement/chat-simulation/).

### AI Moderator (Beta) {#with-ai-moderator}

The **AI Moderator**, in Beta, answers attendee questions from documents you upload and keeps the chat civil. On an automated webinar running at 3am, it can answer a question that would otherwise wait for someone on your team.

### Emails and reminders {#with-notifications}

Reminders on the **Notifications** tab are timed relative to the webinar, not to a fixed clock time, so they work with evergreen schedules. See [Reminder emails](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/product-docs/webinars/notifications/reminder-emails/) and [Confirmation emails](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/product-docs/webinars/notifications/confirmation-emails/).

### Analytics and People {#with-analytics}

Polls, offers and analytics behave as on any webinar. In **People**, filter by **Webinar → Evergreen** to compare your automated funnel with your live sessions. See [People](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/product-docs/webinars/analytics/people/).

### Plan usage {#with-plan-usage}

People watching evergreen sessions, including just-in-time ones, count towards the [**Automated attendees** meter](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/product-docs/reference/limits-and-defaults/#attendee-capacity) on the **Plan** tab.

## Who uses just-in-time, and how {#who-uses-it}

These are typical patterns, shown to illustrate how the setting is used.

### SaaS and product teams {#saas-teams}

A product team links its "watch the demo" button to an evergreen registration page with just-in-time on a short interval. A visitor registers and is watching the recorded demo within minutes, in their own local time.

### Course creators {#course-creators}

A creator's teaching webinar runs on just-in-time alongside a daily recurring time. New visitors from ads take the next just-in-time session; people who'd rather plan ahead book the daily slot. See [Selling online courses with webinars](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/product-docs/use-cases/sell-courses/).

### Small businesses and solo operators {#small-business}

A solo consultant can't keep a calendar of live sessions. A just-in-time evergreen webinar means an enquiry from the website can be watching the consultant's explainer within minutes, with **Exclude specific time** keeping chosen hours clear.

### Customer success teams {#customer-success}

A customer success team sends new customers to an onboarding webinar with just-in-time sessions, so each customer starts onboarding in their own timezone shortly after signing up.

## Limits and things to know {#limits}

- **Evergreen only.** Just-in-time is part of the evergreen schedule step. Live and simulive webinars use dated sessions in the webinar's timezone.
- **Fixed interval choices.** 2, 15, 30, 45 or 60 minutes.
- **Local time applies to just-in-time sessions only.** Other sessions on the same webinar use the webinar's timezone.
- **The schedule step's timezone message is broader than the behaviour.** Rely on the table above, not the in-app message.
- **The type is fixed.** To use just-in-time with a webinar that is currently live or simulive, clone it as **Evergreen**. See [Clone a webinar](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/product-docs/webinars/getting-started/clone-a-webinar/).

## Common questions {#common-questions}

#### What is a just-in-time webinar? {#faq-what-is-jit}

A session that starts a few minutes after someone registers, instead of at a fixed future time. In EasyWebinar it's an option on evergreen webinars.

#### How often do just-in-time sessions start? {#faq-how-often}

As often as you set with **Interval**: every 2, 15, 30, 45 or 60 minutes.

#### What's the shortest interval? {#faq-shortest}

Two minutes.

#### Do attendees see just-in-time sessions in their own timezone? {#faq-local-time}

Yes. Just-in-time sessions start shortly after each person registers, in their own local time.

#### Do my daily and weekly sessions follow local time too? {#faq-recurring-timezone}

No. Recurring sessions run at the times you set, in the webinar's timezone.

#### Can I stop just-in-time sessions at certain hours? {#faq-exclude}

Yes. Use **Exclude specific time** to keep those hours clear.

#### Can I offer just-in-time and instant viewing together? {#faq-with-on-demand}

Yes. Turn on **On Demand** as well; **Schedule Preferences** then reads **Display Just-in-time & Instant-replay**.

#### Can I use just-in-time on a live or simulive webinar? {#faq-other-types}

No. It's an evergreen option. Clone the webinar as **Evergreen** to use it.

#### How do I check it's working? {#faq-test}

Set the interval to 2 minutes, register on your own page, and watch for the session on the **Live** tab of the Sessions panel.

#### Is just-in-time the same as JIT? {#faq-jit-name}

Yes. JIT is the common short name for **Just-in-time Registration**.

## Related {#related}

- [Create an evergreen webinar](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/product-docs/webinars/getting-started/create-an-evergreen-webinar/): the full setup that just-in-time is one step of.
- [On Demand](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/product-docs/webinars/on-demand/): the option for registrants who want to watch now rather than in a few minutes.
- [Chat simulation](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/product-docs/webinars/engagement/chat-simulation/): a chat for attendees who each arrive at a different moment.
- [The Overview tab](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/product-docs/webinars/setup/overview-tab/): where the Live tab shows a just-in-time session on air.
- [Clone a webinar](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/product-docs/webinars/getting-started/clone-a-webinar/): how a live or simulive webinar gets just-in-time sessions.
- [Limits and defaults](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/product-docs/reference/limits-and-defaults/): the interval options and other evergreen settings in one place.
