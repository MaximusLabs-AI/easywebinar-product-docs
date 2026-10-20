# Create an evergreen webinar

Build an evergreen webinar in EasyWebinar that plays a recording on a continuous schedule, with just-in-time sessions, On Demand viewing and recurring daily or weekly times your registrants choose from.

- Applies to: Evergreen webinars
- Status: Live
- Verified: 2026-10-16
- Canonical page: https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/product-docs/webinars/getting-started/create-an-evergreen-webinar/

An evergreen webinar plays a recording on a schedule that keeps running, instead of on one fixed date. A visitor to the registration page picks a session that suits them, and the recording plays for them at that time. You set up the schedule once, with any combination of just-in-time sessions, On Demand viewing and recurring daily or weekly times, and EasyWebinar generates the sessions from it.

**Expected result:** an evergreen webinar with its schedule, pricing and recording set, a list of [upcoming sessions generated on its **Overview** tab](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/product-docs/webinars/setup/overview-tab/#evergreen-scheduling), and a registration page ready to publish.

## At a glance {#at-a-glance}

| | |
|---|---|
| **What it is** | A [recorded webinar that runs continuously](https://easywebinar.com/evergreen-webinars/), with timing personalised to each registrant |
| **Ways to watch** | **Just-in-time Registration**, **On Demand** and **Recurring Schedule**, in any combination |
| **Just-in-time interval** | Every 2, 15, 30, 45 or 60 minutes |
| **Recurring frequency** | **Daily** or **Weekly**, with **Add Time** for more than one slot a day |
| **Run dates** | A **Start Date**, and an **End Date** or **No end date** |
| **Timezone** | Just-in-time sessions follow each attendee's local time; recurring sessions use the webinar's timezone |
| **Video** | Uploaded and hosted by EasyWebinar, or imported from YouTube, Vimeo, Wistia or a direct MP4 link |
| **Changing the video later** | **Webinar Video** panel on the **Content** tab, without disturbing schedule or registrations |
| **Also called** | [Automated webinar](https://easywebinar.com/automated-webinars/) |

## Before you begin {#before-you-begin}

- **Have the recording to hand.** Every session plays it. You can upload or import it during setup if it isn't in your library yet.
- **Decide how people should be able to watch.** Soon after registering, straight away, at set times, or a mix. The schedule step is built around that choice.
- **Know your audience's hours.** Recurring sessions run in the webinar's timezone, so pick times that work for the people you expect.
- **Charging for access?** Paid registration needs a connected Stripe account. See [Paid webinars](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/product-docs/webinars/selling/paid-webinars/).
- **Confirm the type.** A webinar's type can't be changed after creation. If you have a live webinar you want to run this way, see [Clone a webinar](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/product-docs/webinars/getting-started/clone-a-webinar/) instead.

## Step 1: Start a new webinar {#start-new-webinar}

1. Click **My Webinars** in the sidebar.
2. Click **Create a Webinar**, then **Create Manually**.

**Create with AI** also supports evergreen: set **Type** before generating, then choose the video afterwards. See [Create with AI](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/product-docs/ai/create-with-ai/).

## Step 2: Name it and choose Evergreen {#name-and-type}

1. Enter the **Webinar Name** your registrants will see.
2. Choose the **Evergreen Webinar** card. It reads: pre-recorded content available 24/7, with viewers watching on their own schedule.
3. Click **Continue to Schedule**.

## Step 3: Build the schedule {#build-schedule}

The schedule step is where an evergreen webinar differs from every other type. It offers three ways for people to watch, plus controls for when the schedule runs.

![The evergreen schedule step with Just-in-time Registration and On Demand switched on, a daily recurring schedule, availability dates and schedule preferences](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/images/evergreen/step-01-schedule.png)

*1 Just-in-time Registration · 2 On Demand · 3 Recurring Schedule · 4 Availability · 5 Schedule Preferences.*

| | Option | What your registrant gets |
|---|---|---|
| 1 | **Just-in-time Registration** | A session starting a few minutes from now |
| 2 | **On Demand** | Playback straight away, with no session to wait for |
| 3 | **Recurring Schedule** | Fixed session times, daily or weekly |
| 4 | **Availability** | Not a viewing option: the date the schedule starts, and an optional end date |
| 5 | **Schedule Preferences** | Not a viewing option: how many choices a registrant sees, and blackout dates |

Switch on as many of the three viewing options as you like. Each one you enable shows on the registration page as a choice.

### Just-in-time Registration {#just-in-time}

Turn it on and the registration page offers a session that starts shortly. **Interval** controls how often these sessions come round, from every 2 minutes to every 60, and **Exclude specific time** keeps chosen hours clear. Just-in-time sessions run in each attendee's own local time. Settings, timezone behaviour and testing are covered in [Just-in-time webinars](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/product-docs/webinars/automated/just-in-time/).

### On Demand {#on-demand}

Turn it on and registrants can start watching as soon as they register. **Instant replay text** sets the wording of the button they click, which reads *Watch instant replay* until you change it. On Demand is the same thing as instant replay, and it is not the replay page on the **Replay** tab. See [On Demand](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/product-docs/webinars/on-demand/).

### Recurring Schedule {#recurring-schedule}

1. Set **Schedule Frequency** to **Daily** or **Weekly**.
2. Set the time sessions should start.
3. Click **Add Time** for another slot on the same day.

Recurring sessions play at the times you enter, in the webinar's timezone. A session set for 2:00 AM starts at 2:00 AM in that timezone for everyone who picked it.

### Availability {#availability}

**Start Date** is the day the schedule begins. Leave **End Date** on **No end date** if the webinar should keep running indefinitely, or set a date for a campaign with a finish.

### Schedule Preferences {#schedule-preferences}

**Schedule Preferences** decides how many session choices a registrant sees. With just-in-time and On Demand both enabled, it reads **Display Just-in-time & Instant-replay**. Turn on **Blackout Dates** and pick the days the webinar shouldn't run, such as holidays.

When the schedule is set, click **Continue to Pricing**.

> **About the timezone message on this step**
> The schedule step shows a message saying attendees will see times in their local time based on the selected timezone. On an evergreen webinar that applies to just-in-time sessions only. Daily and weekly sessions run at the times you set, in the webinar's timezone.


## Step 4: Choose free or paid {#pricing}

1. Choose **Free** or **Paid**.
2. Click **Continue to Video Selection**.

If you choose **Paid**, you'll need a connected Stripe account. See [Paid webinars](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/product-docs/webinars/selling/paid-webinars/).

## Step 5: Choose the video {#choose-video}

The video you pick here is the recording every session plays, whichever way a registrant chooses to watch.

![The Video Selection step for an evergreen webinar, with filters, search, Add Video, the upload area and the library](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/images/evergreen/step-02-video-selection.png)

*1 All · Videos · Recordings · 2 Search and sort · 3 Add Video · 4 Drag and drop · 5 Your library.*

| | Control | What it does |
|---|---|---|
| 1 | **All · Videos · Recordings** | Shows everything, only videos you have added, or only recordings of past webinars |
| 2 | **Search and sort** | Looks a video up by name |
| 3 | **Add Video** | Adds a video from inside this step |
| 4 | **Drag and drop** | Uploads a file dropped on the page |
| 5 | **Your library** | Selects the video you click |

Select a video and click **Continue to Registration Template**.

If the video isn't in your library, **Add Video** gives you **Local import**, where EasyWebinar hosts the file, or **Import from URL** for YouTube, Vimeo, Wistia or a direct MP4 link. An imported video needs its length as well as its link. Uploads can be MP4, MOV or WebM, up to 4 GB. See [Video hosting](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/product-docs/webinars/media/video-hosting/) for both routes in detail.

A recording of a webinar you have already run sits under **Recordings**. Choosing it turns that session into the content of the evergreen webinar.

## Step 6: Choose a template {#template}

Pick a registration template, or click **Skip & Create Webinar** and choose one later. Edit and publish the page in the builder before you send anyone to it. See [Registration page builder](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/product-docs/webinars/registration/registration-page-builder/).

## Verify the result {#verify}

Open the webinar's **Overview** tab.

![An evergreen webinar's Overview tab, with Scheduling Options showing a daily frequency, start date, the attendee's local timezone and the chosen preference, and a Sessions panel listing generated sessions](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/images/evergreen/step-02-overview.png)

*1 Scheduling Options · 2 Sessions.*

| | Panel | What to check |
|---|---|---|
| 1 | **Scheduling Options** | Frequency, start date, timezone and the preference you chose |
| 2 | **Sessions** | The sessions generated from your schedule |

Three things confirm the setup worked:

- **The timezone reads Attendee's local timezone** when just-in-time is on, because those sessions start shortly after each person registers, in their own time.
- **The Sessions list fills itself.** A daily schedule produces a long run of upcoming sessions with no manual entry.
- **There is a Live tab** in the Sessions panel next to **Upcoming**, **Past** and **Cancelled**. Evergreen webinars have it; it shows sessions on air at that moment.

### Watch a session as an attendee {#test-a-session}

To see your evergreen webinar the way attendees do, register on your own registration page. With just-in-time on and the interval at 2 minutes, the shortest option, a session starts within minutes. When a session is running, it appears on the **Live** tab of the Sessions panel marked *Live now*, with **Enter room**.

## What an evergreen webinar is {#what-it-is}

An evergreen webinar is one of EasyWebinar's three types. Live webinars are presented in real time; simulive webinars broadcast a recording at times you set, with everyone watching together. Evergreen also plays a recording, but the schedule repeats and each registrant chooses their own time.

| Question | Evergreen answer |
|---|---|
| Who chooses the session time? | The registrant, from the options your schedule offers |
| Do attendees watch together? | Not necessarily; each registrant watches the session they picked |
| Does it need you present? | No |
| Do pages, emails, polls, offers and analytics differ? | No; only the delivery differs |

For the scheduled-broadcast version, see [Create a simulive webinar](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/product-docs/webinars/getting-started/create-a-simulive-webinar/).

## Why evergreen webinars matter {#why-it-matters}

### What it's for {#what-its-for}

An evergreen webinar usually [belongs to a funnel](https://easywebinar.com/blog/evergreen-sales-funnel/): a product demo, an onboarding session, or an offer that runs all year. Visitors reach it from ads, emails and links at any hour. It has to be ready when they are, whether or not you're free.

### What happens without it {#without-it}

A common approach is to present every session live, or to set up each recorded session as a dated event. Both tie the funnel to your calendar. A visitor who arrives the day after the last session has nothing to register for. The gap between interest and watching is where many drop away.

### How EasyWebinar helps {#how-it-helps}

Once the recording exists, a session no longer needs you, so the schedule can repeat on its own. EasyWebinar builds every session from one schedule you set once, with three ways to watch in any combination.

- **Soon.** **Just-in-time Registration** offers a session starting a few minutes after someone registers.
- **Now.** **On Demand** lets registrants start watching straight away.
- **At set times.** A **Daily** or **Weekly** recurring schedule, with **Blackout Dates** for days off.
- **One recording, hosted for you.** EasyWebinar can host the video itself, and you can replace it later without touching the schedule or registrations.

### Why buyers care {#why-buyers-care}

Left on **No end date**, a daily schedule keeps generating upcoming sessions without you adding any. That matters most to SaaS, customer success and course teams who run a webinar as a standing channel rather than a launch-day event.

## How evergreen webinars work with other features {#works-with}

### Just-in-time and On Demand {#with-jit-and-on-demand}

Just-in-time and On Demand are both switched on in Step 3 above. Both can run alongside a recurring schedule, and the registration page shows each one you enable as a choice.

### Chat Simulation {#with-chat-simulation}

On an automated webinar, people arrive at different times, so a shared live conversation isn't possible. Turn on **Chat Simulation** on the **Engagement** tab to fill the chat with an AI-generated or CSV-scripted conversation. See [Chat simulation](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/product-docs/webinars/engagement/chat-simulation/).

### Chat choices for recorded webinars {#with-chat-options}

Evergreen webinars can use **Easywebinar Chat**, [embed an external chat tool](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/product-docs/webinars/engagement/live-chat/#third-party-chat) with **Third party**, or turn chat off with **No Chat** while keeping the **EW Contact Box** for questions sent by email.

### AI Moderator (Beta) {#with-ai-moderator}

The **AI Moderator** answers attendee questions from documents you upload and keeps the chat civil. It is in Beta. It's aimed at large webinars and automated ones running without you.

### Emails and reminders {#with-notifications}

Reminder timing on the **Notifications** tab is relative to the webinar, so reminders follow evergreen schedules rather than one fixed date. See [Reminder emails](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/product-docs/webinars/notifications/reminder-emails/) and [Confirmation emails](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/product-docs/webinars/notifications/confirmation-emails/).

### Replay page {#with-replay-page}

The replay page on the **Replay** tab is for people who missed a session that has already happened. It is separate from On Demand. See [Replay pages](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/product-docs/webinars/media/replay-pages/).

### Analytics and People {#with-analytics}

Chat, Q&A, polls, offers, emails and analytics behave as on any other webinar. In **People**, filtering by **Webinar → Evergreen** shows how the automated funnel performs against your live sessions. See [Webinar analytics](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/product-docs/webinars/analytics/webinar-analytics/) and [People](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/product-docs/webinars/analytics/people/).

### Plan usage {#with-plan-usage}

People watching evergreen sessions count towards the **Automated attendees** meter on the **Plan** tab.

## Who uses evergreen webinars, and how {#who-uses-it}

These are typical patterns, shown to illustrate how the type is used.

### Course creators {#course-creators}

A creator runs a teaching webinar that ends with an [enrolment offer](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/product-docs/webinars/engagement/timed-offers/), on a daily schedule with just-in-time sessions. The webinar sells the course while the course itself stays on the creator's own platform. See [Selling online courses with webinars](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/product-docs/use-cases/sell-courses/).

### SaaS and product teams {#saas-teams}

A product team puts a [recorded demo](https://easywebinar.com/use-cases/product-demos/) behind its "see it in action" link. With just-in-time on, a visitor who registers can be watching within minutes, while the details are still fresh in their mind.

### Customer success teams {#customer-success}

A customer success team turns its [onboarding walkthrough](https://easywebinar.com/use-cases/onboard-train-customers/) into an evergreen webinar with On Demand switched on, so new customers can watch the moment they sign up instead of waiting for a scheduled session.

### Small businesses and solo operators {#small-business}

A solo operator who can't present every day records a single webinar and runs it on a weekly schedule, with blackout dates over holidays and Chat Simulation keeping the room from looking empty.

## How evergreen webinars compare {#compare}

In EasyWebinar, one evergreen webinar can offer just-in-time sessions, On Demand viewing and set daily or weekly times, all on one page. It can host the video itself, or reuse the recording of a webinar you ran live. Some tools go further on how often sessions repeat, and on running them at each viewer's local time.

Evergreen scheduling in each platform's public documentation:

| Platform | Offers it | What it does | Notes |
|---|---|---|---|
| **EasyWebinar** | Yes | Just-in-time, On Demand and **Daily** or **Weekly** recurring sessions, in any combination | Hosts an uploaded video or imports one from YouTube, Vimeo, Wistia or an MP4 link; recurring sessions run in the webinar's timezone |
| **EverWebinar** | Yes | Specific dates or a daily or weekly recurring schedule, with just-in-time sessions and instant watch replay | Help centre says an external video source is required; live webinars run in its sister product WebinarJam |
| **eWebinar** | Yes | Recurring, one-time, specific-date and on-demand-only event types; just-in-time can be added to any | Scheduled sessions can show at the same local clock time for every visitor; recurrence includes every two weeks and monthly |
| **StealthSeminar** | Yes | Just In Time, Daily Repeat Schedule and Watch Yesterday's Replay | Automated events run in each attendee's local time by default |
| **Demio** | Yes | Automated Events with recurring times and On-Demand availability | Just-in-time sessions: not in public docs |
| **Livestorm** | Partly | On-demand events that stay open for registration; recurring events with added sessions | On-demand can't be combined with recurring sessions; just-in-time: not in public docs |

### Where EasyWebinar's version is stronger {#compare-stronger}

- **All three ways to watch in one webinar.** EasyWebinar offers just-in-time, On Demand and set times together on one page. Livestorm says recurring events can't be set up on-demand, and Demio's public docs show no just-in-time option. See [EasyWebinar vs Livestorm](https://easywebinar.com/compare/easywebinar-vs-livestorm/) and [EasyWebinar vs Demio](https://easywebinar.com/compare/easywebinar-vs-demio/).
- **Video hosting in the same flow.** With **Local import**, EasyWebinar hosts the video itself, so you don't need a YouTube or Vimeo account. EverWebinar's help centre says an external video source is required. See [EasyWebinar vs EverWebinar](https://easywebinar.com/compare/easywebinar-vs-everwebinar/).
- **From live to evergreen in one product.** EasyWebinar lists recordings of your past webinars under **Recordings** when you pick the video. EverWebinar can import a past WebinarJam session only if the same account has an active WebinarJam subscription.

### Where other platforms go further {#compare-further}

- **Local clock time for set sessions.** eWebinar can show a 10am session at 10am wherever the visitor is. StealthSeminar's automated events run in each user's local time by default. EasyWebinar's daily and weekly sessions run in the webinar's timezone; only just-in-time sessions follow local time. See [EasyWebinar vs eWebinar](https://easywebinar.com/compare/easywebinar-vs-ewebinar/) and [EasyWebinar vs Stealth Seminar](https://easywebinar.com/compare/easywebinar-vs-stealth-seminar/).
- **More ways to repeat.** eWebinar can repeat every two weeks or once a month. Demio's recurring times include every other day and monthly. EasyWebinar's schedule repeats daily or weekly.

*Competitor details checked against each vendor's public documentation on 20 October 2026. Features and plans change, so confirm with the vendor before you decide.*

## Limits and things to know {#limits}

- **The type is fixed.** To change an evergreen webinar into another type, or a live one into evergreen, clone it.
- **A recording is required.** Every session plays the video chosen at creation or later on the **Content** tab.
- **Only just-in-time sessions use local time.** Recurring daily and weekly sessions run in the webinar's timezone, despite the message on the schedule step.
- **The interval options are fixed:** 2, 15, 30, 45 or 60 minutes.
- **Imported videos need an accurate duration.** It's how EasyWebinar knows how long each session runs.
- **Chat Simulation runs one mode at a time:** AI or manual, not both.
- **The AI Moderator is in Beta.**

## Common questions {#common-questions}

#### What is the difference between evergreen and simulive? {#faq-vs-simulive}

Both play a recording. Simulive broadcasts it at times you set, so everyone in a session watches together. Evergreen repeats on a schedule and each registrant picks the session that suits them.

#### Can one evergreen webinar offer just-in-time, On Demand and set times together? {#faq-all-three}

Yes. Enable all three and the registration page presents each as a choice.

#### What does a just-in-time session do? {#faq-jit}

It starts a few minutes after someone registers rather than at a fixed future time.

#### Is On Demand the same as the replay page? {#faq-on-demand-vs-replay}

No. On Demand lets a registrant watch straight away. The replay page shows the recording of a session that has already happened.

#### Do my attendees see times in their own timezone? {#faq-timezone}

For just-in-time sessions, yes. Daily and weekly sessions run in the webinar's timezone.

#### How do I stop sessions on certain days? {#faq-blackout}

Turn on **Blackout Dates** in **Schedule Preferences** and choose the dates.

#### Does the webinar ever stop running? {#faq-end-date}

Only if you set an **End Date**. Left on **No end date**, the schedule runs indefinitely.

#### Do I need YouTube or Vimeo to host the recording? {#faq-video-host}

No. Upload it with **Local import** and EasyWebinar hosts it. Importing a link is optional.

#### Can I replace the recording once the webinar is running? {#faq-replace-video}

Yes, from the **Webinar Video** panel on the **Content** tab. The schedule and registrations stay as they are.

#### I've already run this webinar live. Do I start from scratch? {#faq-from-live}

No. Clone the live webinar, choose **Evergreen** for the copy, and select the live session's recording. See [Clone a webinar](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/product-docs/webinars/getting-started/clone-a-webinar/).

## Related {#related}

- [Just-in-time webinars](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/product-docs/webinars/automated/just-in-time/): choosing an interval and testing a session that starts minutes after registering.
- [On Demand](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/product-docs/webinars/on-demand/): wording the instant replay button and how it differs from the replay page.
- [Create a simulive webinar](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/product-docs/webinars/getting-started/create-a-simulive-webinar/): the other recorded type, with everyone watching at set times.
- [Chat simulation](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/product-docs/webinars/engagement/chat-simulation/): keeping the chat active when registrants watch at different times.
- [Video hosting](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-v2/easywebinar-product-docs/pilot-v2/product-docs/webinars/media/video-hosting/): uploading or importing the recording every session plays.
