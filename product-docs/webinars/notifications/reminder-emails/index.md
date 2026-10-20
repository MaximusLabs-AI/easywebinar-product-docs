# Webinar reminder emails

How EasyWebinar's Webinar Reminders work, how to time them relative to the session, how many to send, and how to tell from Analytics whether they are getting people to attend.

- Applies to: Every webinar, including recurring and evergreen schedules · set per webinar on the Notifications tab
- Status: Live
- Verified: 2026-10-16
- Canonical page: https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/webinars/notifications/reminder-emails/

**Webinar Reminders** are the emails EasyWebinar sends to registrants before the session starts. Each reminder has its own timing, set as a length of time before the webinar, so the same reminders work for a one-off session, a recurring schedule or an evergreen webinar. You can add as many as you need from the **Notifications** tab, and Analytics shows whether they are working: the gap between people who registered and people who attended is the reminders' job.

## At a glance {#at-a-glance}

| | |
|---|---|
| **What it does** | Emails registrants before the webinar starts |
| **Who receives it** | Registrants |
| **How timing works** | Set as time before the webinar, for example *1h 0m 0s before webinar* |
| **How many** | As many as you add with **Create New**; three is a common pattern |
| **Suggested pattern** | A day before, an hour before and fifteen minutes before |
| **Where you set it** | Webinar → **Notifications** → **Emails** → **Webinar Reminders** |
| **Schedules** | Works for recurring and evergreen schedules, because timing is relative |
| **Other channels** | **Reminder SMS** and WhatsApp **Reminder Message**, both in Beta |
| **How to measure it** | **Registered** to attended in the webinar's Analytics |

## What webinar reminders are {#what-it-is}

A reminder is an email in the **Webinar Reminders** group on the **Notifications** tab. It goes to people who registered, before the webinar starts, and its purpose is to turn a registration into an attendance.

What makes EasyWebinar's reminders work across webinar types is how their timing is set. A reminder isn't scheduled for a clock time like "Tuesday at 9am". It is set relative to the session, expressed as hours, minutes and seconds before the webinar, such as *0h 15m 0s before webinar*. A daily recurring webinar or an evergreen webinar has many sessions, and relative timing is why the same reminders work across all of them.

Reminders sit between two other email groups. The **Registration Confirmation** goes out the moment someone signs up, and **Webinar Follow-ups** go out after the session. Reminders cover the time in between, which is when most registrants forget.

## Why reminders matter {#why-it-matters}

### What it's for {#what-its-for}

Getting people to register is the easy part; getting them to turn up is what notifications are for. Reminders carry the date, the time and the way in back to the registrant at the points where they would otherwise drift away: the day before, when they can still plan around it, and the minutes before, when they need a prompt to click.

### How it helps {#how-it-helps}

- **It brings the session back into view.** A registration made days ago is easy to forget; a reminder an hour before puts it in front of the person again.
- **The last reminder does most of the work.** In EasyWebinar's guidance, the reminder fifteen minutes before is the one that matters most for attendance.
- **It runs on every session automatically.** Because timing is relative, there is nothing to reschedule when a recurring or evergreen webinar adds new sessions.
- **It is measurable.** **Registered** to attended in Analytics tells you whether the reminders are doing their job.

### What happens without it {#without-it}

Without reminders, attendance depends on people remembering a session they signed up for days or weeks earlier, and finding their confirmation email at the right moment. Analytics makes the cost visible: a large **Missed** count, people who registered and never showed up, with a registration page that was doing its job. EasyWebinar's own reading of a low registered-to-attended rate is that it's a notification problem, not a content one.

### Why buyers care {#why-buyers-care}

Every webinar result that matters to the business, offer clicks, purchases, booked calls, depends on people actually watching. A platform's reminders decide how many registrants make it into that group. Buyers look for reminders that need no manual scheduling, work on automated webinars, and can be added and timed freely.

## Set it up {#set-it-up}

### Find your reminders {#find-reminders}

1. Open your webinar and click the **Notifications** tab.
2. Stay on the **Emails** channel and find the **Webinar Reminders** group.

![The Notifications tab showing the Webinar Reminders group with three reminders timed 15 minutes, 1 hour and 24 hours before the webinar](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/images/notifications/step-01-emails.png)

*1 Channel tabs · 2 Email Settings · 3 An email group · 4 Create New.*

Each entry shows its **trigger**, the audience it goes **to**, and its **subject**, so the group reads as a timeline of what registrants will receive.

### Edit a reminder {#edit-reminder}

1. Open the reminder you want to change.
2. Change its subject, content and timing.
3. Set the timing as time before the webinar, in hours, minutes and seconds.
4. Save your changes.

### Add another reminder {#add-reminder}

1. Click **Create New** in the **Webinar Reminders** group.
2. Set its timing before the webinar.
3. Write the subject and content.

### A sensible schedule {#sensible-schedule}

| Reminder | Timing before the webinar | What it's for |
|---|---|---|
| A day before | One day before the session | Lets people plan their day around the session |
| An hour before | *1h 0m 0s before webinar* | Brings the session back to mind while there's still time to prepare |
| Fifteen minutes before | *0h 15m 0s before webinar* | The prompt to join now; the one that does most of the work |

Three is a sensible default. Webinars built with **Create with AI** arrive with exactly this pattern already drafted: **Reminder — 1d**, **Reminder — 1h** and **Reminder — 15m**, with merge tags already in place so dates, times and join links fill themselves in.

### Check who the reminders come from {#check-sender}

Reminders use the webinar's **Email Settings**: the **Sender name** registrants see and the **Reply-to email** where replies go. Set the sender to a name registrants will recognise from their confirmation. See [Registration confirmation emails](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/webinars/notifications/confirmation-emails/) for the full settings.

## Text and WhatsApp reminders (Beta) {#sms-whatsapp}

Both Beta channels have a reminder of their own on the **Notifications** tab: **Reminder SMS** on the **SMS** tab and **Reminder Message** on the **Whatsapp** tab, each sent before the webinar starts. They work alongside email rather than replacing it, and suit the final reminder before a session, when an email may sit unread.

In short:

- **They need a phone number.** Add the **Phone** field to your registration form, or there is nobody to message.
- **They come from an EasyWebinar number**, not your own.
- **You build them from templates** grouped by tone, then edit the words.
- **You can test first.** **Send Test SMS** and **Send Test Message** send the selected template to your own number. Pick your country from the flag dropdown rather than typing a dialling code.
- **Keep them short.** A reminder needs the time and the link.

Pick whichever channel your audience actually uses. Sending both tends to irritate people.

## How it works with other features {#works-with}

### Registration confirmation {#with-confirmation}

The confirmation starts the sequence and carries the join link; reminders bring the registrant back to it. Both are on the same tab and share the same sender settings. See [Registration confirmation emails](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/webinars/notifications/confirmation-emails/).

### Evergreen and just-in-time sessions {#with-evergreen}

An evergreen webinar generates a long run of sessions from one schedule, and can add just-in-time sessions that start shortly after someone registers. Reminders are timed relative to the webinar rather than to a clock, which is why they work for recurring and evergreen schedules without being set session by session. See [Create an evergreen webinar](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/webinars/getting-started/create-an-evergreen-webinar/) and [Just-in-time sessions](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/webinars/automated/just-in-time/).

### Analytics {#with-analytics}

The webinar's **Analytics** tab shows the funnel from **Visitors** to **Registered**, **Live Attended**, **Total Attended** and **Missed**. Two gaps tell you different things:

| Gap | What a low number means |
|---|---|
| **Visitors** to **Registered** | A registration page problem: the headline, the form, the promise |
| **Registered** to attended | A notification problem, not a content one |

Change your reminders, run the next session, and compare. See [Webinar analytics](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/webinars/analytics/webinar-analytics/).

### Follow-ups for people the reminders didn't reach {#with-follow-ups}

**Missed** counts people who registered and never showed up. Add a **Webinar Follow-up** with its audience set to no-shows and include the replay link. In **People**, filter by **Behavior** for no-shows to see exactly who they are, then **Export** the list if you need it elsewhere. See [People](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/webinars/analytics/people/) and [Replay pages](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/webinars/media/replay-pages/).

### Reminders from your own CRM {#with-crm}

If you would rather send reminders from your CRM or email tool, map the **Webinar Join Link** into one of its custom fields. Each contact then holds their own working link, which is what lets your system send the reminder instead of EasyWebinar. See [Connect a CRM and map your webinar data](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/integrations/map-webinar-data/).

### Cloning {#with-cloning}

**Email notifications** can come across when you clone a webinar, so a reminder schedule you have tuned carries into the copy. See [Clone a webinar](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/webinars/getting-started/clone-a-webinar/).

## Who uses it, and how {#who-uses-it}

These are typical patterns, shown to illustrate how reminders fit different kinds of webinar.

### SaaS and product teams {#product-teams}

A product team runs a weekly live demo. The three-reminder pattern goes out before every session without anyone touching it, and the team watches **Registered** to attended week by week to see whether a subject-line change made a difference.

### Course creators {#course-creators}

A creator's evergreen webinar runs daily. Because reminder timing is relative to the webinar, the same three emails serve the whole schedule. The creator adds a Beta **Reminder SMS** as the final nudge for an audience that reads texts faster than email. See [Course creators](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/use-cases/sell-courses/).

### Customer success teams {#customer-success}

A customer success team runs onboarding webinars for new customers. Their reminders restate what to have ready before the session, and the fifteen-minute reminder carries the link and nothing else.

### B2B marketing teams {#b2b-marketing}

A marketing team already runs its nurture emails from its own system, so it maps the **Webinar Join Link** into a CRM field and sends one of the reminders from there, keeping EasyWebinar's reminders for the final hour.

## Limits and things to know {#limits}

- **Timing is relative to the webinar**, not a fixed clock time. Set it in hours, minutes and seconds before the session.
- **Reminders are set per webinar.** Use cloning to carry a schedule to a new webinar.
- **Reminders go to registrants.** They are written once per webinar and sent to the people who registered for it.
- **SMS and WhatsApp reminders are in Beta** and only reach people who gave a phone number on your registration form.
- **SMS and WhatsApp come from an EasyWebinar number**, so replies don't reach your phone.
- **Email stays the main channel.** Text and WhatsApp reminders work alongside email, not instead of it.

## Common questions {#common-questions}

#### How many reminders should I send? {#faq-how-many}

Three is a sensible default: a day before, an hour before, and fifteen minutes before. The last one does most of the work.

#### Can I add more than one reminder? {#faq-add-more}

Yes. Click **Create New** in the **Webinar Reminders** group, and set the timing for each.

#### How is a reminder's timing set? {#faq-timing}

As time before the webinar, in hours, minutes and seconds, for example *1h 0m 0s before webinar*.

#### Do reminders work on recurring and evergreen webinars? {#faq-evergreen}

Yes. Timing is relative to the webinar, not a fixed clock time, so it works for recurring and evergreen schedules.

#### Can I change what a reminder says? {#faq-edit}

Yes. Open the reminder to change its subject, content and timing.

#### How do I know if my reminders are working? {#faq-measure}

Compare **Registered** with attendance in the webinar's Analytics. A low registered-to-attended rate points to your notifications, not your content.

#### Can I send reminders by text or WhatsApp? {#faq-sms-whatsapp}

Both are in Beta. **Reminder SMS** and the WhatsApp **Reminder Message** send before the webinar starts, and both need the **Phone** field on your registration form.

#### Should I test a text or WhatsApp reminder first? {#faq-test}

Yes. **Send Test SMS** and **Send Test Message** send the selected template to your own number so you see exactly what registrants receive.

#### Does a webinar built with AI include reminders? {#faq-ai}

Yes. **Create with AI** drafts reminders for a day, an hour and fifteen minutes before, with merge tags for dates, times and join links.

#### What about people who still didn't turn up? {#faq-no-shows}

Add a **Webinar Follow-up** with its audience set to no-shows and include the replay link.

#### Can I send reminders from my CRM instead? {#faq-crm}

Yes. Map the **Webinar Join Link** into a custom field in your CRM so each contact has their own working link.

## Related {#related}

- [Registration confirmation emails](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/webinars/notifications/confirmation-emails/)
- [Webinar analytics](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/webinars/analytics/webinar-analytics/)
- [Replay pages](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/webinars/media/replay-pages/)
- [Create an evergreen webinar](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/webinars/getting-started/create-an-evergreen-webinar/)
- [Create a webinar with AI](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/ai/create-with-ai/)
- [Connect a CRM and map your webinar data](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/integrations/map-webinar-data/)
