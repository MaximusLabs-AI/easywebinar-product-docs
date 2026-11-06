# Connect EasyWebinar to ChatGPT and Claude

How EasyWebinar's AI connector works in ChatGPT and Claude, what you can do with it, how to connect it, which actions wait for your approval, and how to check it's working.

- Applies to: Your EasyWebinar account · ChatGPT and Claude
- Status: Live
- Verified: 2026-11-04
- Canonical page: https://maximuslabs-ai.github.io/easywebinar-product-docs/product-docs/webinars/automated/connect-chatgpt-and-claude/

The **AI connector** links your EasyWebinar account to ChatGPT or Claude, so you can run your webinars by chatting instead of opening the dashboard. You add EasyWebinar from the assistant's settings and sign in with your EasyWebinar email and password. The assistant then works only in your account, with your permissions. It reads freely, and asks you before it creates, changes, publishes or deletes anything.

## At a glance {#at-a-glance}

| | |
|---|---|
| **What it does** | Lets ChatGPT or Claude work in your EasyWebinar account from a chat |
| **Where it's added** | ChatGPT: **Settings → Apps**. Claude: **Settings → Connectors → Browse connectors** |
| **How you sign in** | Your EasyWebinar email and password, then approve access |
| **What it covers** | Webinars, pages and emails, engagement, and analytics |
| **Reading** | Runs at once, with no approval step |
| **Changes** | Creating, changing, publishing or deleting asks you first |
| **Whose account** | Only the account you signed in with, with your permissions |
| **Sign-in length** | Renewed by the assistant for up to 30 days |
| **Turning it off** | Disconnect in the assistant's settings; access ends at once |
| **Also called** | MCP connector, ChatGPT app, Claude connector |

## What the AI connector is {#what-it-is}

Normally you manage a webinar by opening the dashboard, finding the webinar and working through its tabs. With the AI connector, you ask in plain words instead, and the assistant does the same work in your account.

Someone who asks *Show my upcoming webinar sessions* gets their own sessions back in the chat. Someone who asks *Create a live webinar called 'Spring Launch' next Thursday at 6 PM* sees what the assistant is about to create, and approves it.

![How EasyWebinar's AI connector works: you ask ChatGPT or Claude, the assistant uses the connector, and the connector works on your account with your permissions; reading runs at once and changes ask you first](https://maximuslabs-ai.github.io/easywebinar-product-docs/product-docs/images/ai-connector/diagram-01-how-it-works.svg)

*You ask, the assistant uses the connector, and the connector works in your account as you.*

There are three parts to every request:

| Part | What it does | Who controls it |
|---|---|---|
| **You** | Ask for something in a chat | You |
| **ChatGPT or Claude** | Picks the EasyWebinar action that fits, and shows you the answer | Your AI provider, under its own terms |
| **The AI connector** | Signs in as you and runs the action in your account | EasyWebinar, with your permissions |

The connector is built on the Model Context Protocol (MCP), the open standard both assistants use to connect to other apps.

## Why the AI connector matters {#why-it-matters}

### What it's for {#what-its-for}

The connector is for doing webinar work where you already think and write: in a chat. Ask for this week's sessions, last week's attendance or a full reminder sequence, without clicking through tabs. It suits anyone who already drafts in ChatGPT or Claude and then copies the result into EasyWebinar.

### How it helps {#how-it-helps}

- **Faster setup.** One request creates and schedules a webinar. The next writes its emails.
- **Answers in plain words.** Ask how a webinar did and get registrations, attendance and attendance rate back, ready to compare.
- **No copying between tools.** What the assistant writes is saved straight to the webinar, so dates and links can't be pasted wrong.
- **Changes stay in your hands.** Reading runs at once. Anything that would go live waits for your approval.

### What happens without it {#without-it}

Every question about a webinar means opening the dashboard, finding the webinar and the right tab, and copying numbers into wherever you're writing. Emails and pages drafted in an assistant have to be pasted into EasyWebinar one by one. Each copy is a chance to paste the wrong date, the wrong link or last month's version.

### Why buyers care {#why-buyers-care}

Webinars convert when they run often and are followed up well. When scheduling a session, writing its reminders and checking its attendance each take one sentence, teams run more webinars and react to the numbers sooner. Learn how [automated webinars](https://easywebinar.com/automated-webinars/) keep that cycle running.

## The EasyWebinar approach to the AI connector {#approach}

Take a typical case. A business coach runs a live webinar every other week and an [evergreen webinar](https://easywebinar.com/evergreen-webinars/) that sells her programme around the clock. She spends Monday mornings in the dashboard: checking registrations, writing reminders and setting up the next session.

A common setup has her drafting in ChatGPT, then copying text into her webinar tool and checking figures on a separate analytics screen. That probably works when there's time. On a busy week, a reminder goes out with last session's date, or a new webinar is set up an hour off.

The webinars themselves don't need to change. What matters is the gap between where she writes and where the webinar lives.

EasyWebinar closes that gap with the AI connector. She asks Claude: *How did last Thursday's webinar do? Then set up the next one for the same time in two weeks.* Claude reports registered, attended and attendance rate, then shows the new webinar it's about to create. She approves it, asks for three reminders, reads them and approves those too. Everything lands in EasyWebinar as if she'd made it in the dashboard.

The illustrations under Set it up show both assistants' connect steps. How other webinar platforms connect to ChatGPT and Claude is covered in How the AI connector compares, below.

## Set it up {#set-it-up}

### In ChatGPT {#set-up-chatgpt}

1. Open ChatGPT and go to **Settings → Apps**.
2. Search for **EasyWebinar** and click **Connect**.
3. Sign in on the EasyWebinar login page with your email and password.
4. Approve access, then return to ChatGPT.
5. Start a new chat and try a prompt.

![Connecting EasyWebinar to ChatGPT in five steps: open Settings and Apps, find EasyWebinar and click Connect, sign in to EasyWebinar, approve access, start a new chat](https://maximuslabs-ai.github.io/easywebinar-product-docs/product-docs/images/ai-connector/diagram-03-connect-chatgpt.svg)

*1 Settings → Apps · 2 Connect · 3 Sign in · 4 Approve · 5 New chat. Your screens may look slightly different.*

### In Claude {#set-up-claude}

1. Open Claude and go to **Settings → Connectors**.
2. Click **Browse connectors**, search for **EasyWebinar** and click **Connect**.
3. Sign in with your EasyWebinar email and password.
4. Approve access, then return to Claude.
5. Start a new chat and try a prompt.

![Connecting EasyWebinar to Claude in five steps: open Settings and Connectors, browse connectors and click Connect on EasyWebinar, sign in, approve access, start a new chat](https://maximuslabs-ai.github.io/easywebinar-product-docs/product-docs/images/ai-connector/diagram-04-connect-claude.svg)

*1 Settings → Connectors · 2 Browse connectors → Connect · 3 Sign in · 4 Approve · 5 New chat.*

You can connect both assistants to the same EasyWebinar account.

### Before you connect {#before-you-connect}

| Check | Why |
|---|---|
| **The right login** | The assistant works in the account you sign in with. If you have more than one, use the one it should work in |
| **Brand and business profile saved** | The assistant writes pages and emails from what's saved in EasyWebinar, the same profile [Create with AI](https://maximuslabs-ai.github.io/easywebinar-product-docs/product-docs/ai/create-with-ai/) uses |
| **Your role** | The assistant gets your permissions. See [Team members and roles](https://maximuslabs-ai.github.io/easywebinar-product-docs/product-docs/account/team-members/) |

## What you can do from the chat {#what-you-can-do}

The connector covers four areas of your account. Each comes with a prompt to try.

![What you can do from the chat: Webinars, Pages and emails, Engagement, and Analytics, each with its actions and an example prompt](https://maximuslabs-ai.github.io/easywebinar-product-docs/product-docs/images/ai-connector/diagram-02-what-you-can-do.svg)

*Four areas of your account, each with a prompt to try.*

| Area | What you can ask for | Try |
|---|---|---|
| **Webinars** | List webinars and upcoming sessions; create and schedule [live](https://maximuslabs-ai.github.io/easywebinar-product-docs/product-docs/webinars/getting-started/create-a-live-webinar/), [simulive](https://maximuslabs-ai.github.io/easywebinar-product-docs/product-docs/webinars/getting-started/create-a-simulive-webinar/) and [evergreen](https://maximuslabs-ai.github.io/easywebinar-product-docs/product-docs/webinars/getting-started/create-an-evergreen-webinar/) webinars; show [registration links](https://maximuslabs-ai.github.io/easywebinar-product-docs/product-docs/webinars/registration/sharing-links/) and details | *Create a live webinar called 'Spring Launch' next Thursday at 6 PM.* |
| **Pages and emails** | Write and publish [registration](https://maximuslabs-ai.github.io/easywebinar-product-docs/product-docs/webinars/registration/registration-page-builder/), thank-you and waiting-room pages; write [reminder](https://maximuslabs-ai.github.io/easywebinar-product-docs/product-docs/webinars/notifications/reminder-emails/) and follow-up emails | *Write the welcome email, three reminders and two follow-ups for my next webinar.* |
| **Engagement** | Add [polls](https://maximuslabs-ai.github.io/easywebinar-product-docs/product-docs/webinars/engagement/polls/) and [offers](https://maximuslabs-ai.github.io/easywebinar-product-docs/product-docs/webinars/engagement/timed-offers/) to a webinar; teach your AI Moderator your FAQs | *Add a poll to my next webinar asking which topic attendees want covered first.* |
| **Analytics** | See registrations, attendance and attendance rate; compare how your webinars performed | *How many people registered for my last webinar, and how many attended?* |

Name the webinar when you can. *Add a poll to Spring Launch* works better than *add a poll to my webinar*.

## Approvals: what runs at once and what waits {#approvals}

The assistant can read your account freely. Every action that creates, changes, publishes or deletes something is marked, so the assistant shows you what it's about to do and waits for your approval.

| Request | What happens |
|---|---|
| List webinars, sessions or registration links | Runs at once |
| Report registrations, attendance or attendance rate | Runs at once |
| Create or schedule a webinar | Asks you first |
| Publish a page or save an email | Asks you first; once approved, it goes live and reaches your registrants |
| Add a poll or an offer | Asks you first |
| Delete anything | Asks you first |

![A change in the chat: the assistant summarises the live webinar it will create and waits for Approve or Deny; reading runs at once and creating, publishing, changing or deleting asks first](https://maximuslabs-ai.github.io/easywebinar-product-docs/product-docs/images/ai-connector/diagram-05-approval.svg)

*Your request, what the assistant will create, then Approve or Deny. Each assistant shows its own approval prompt.*

Finish one change before you ask for the next, so each approval covers one clear change.

## Test the connector {#test-it}

The quickest check is a question the assistant can only answer from your account.

1. Start a new chat in ChatGPT or Claude.
2. Ask *Show my upcoming webinar sessions.*
3. Check the list against the **Sessions** panel on each webinar's [Overview tab](https://maximuslabs-ai.github.io/easywebinar-product-docs/product-docs/webinars/setup/overview-tab/#sessions).
4. Ask *How many people registered for my last webinar, and how many attended?* and compare it with that webinar's [analytics](https://maximuslabs-ai.github.io/easywebinar-product-docs/product-docs/webinars/analytics/webinar-analytics/).

![Two example answers: a list of upcoming sessions with type, time and registrations, and a last-webinar summary with registered, attended and attendance rate](https://maximuslabs-ai.github.io/easywebinar-product-docs/product-docs/images/ai-connector/diagram-06-example-answers.svg)

*Illustrative answers. The assistant shows your own webinars and figures.*

If the assistant says it can't reach EasyWebinar, check it's still listed under **Settings → Apps** in ChatGPT or **Settings → Connectors** in Claude, and connect again.

## How the AI connector works with other features {#works-with}

### Create with AI {#with-create-with-ai}

[Create with AI](https://maximuslabs-ai.github.io/easywebinar-product-docs/product-docs/ai/create-with-ai/) builds a whole webinar inside EasyWebinar from a description. The connector does similar work from ChatGPT or Claude, one request at a time. Both use the brand and business profile saved in your account.

### Evergreen and just-in-time webinars {#with-evergreen}

The assistant can create and schedule [evergreen webinars](https://maximuslabs-ai.github.io/easywebinar-product-docs/product-docs/webinars/getting-started/create-an-evergreen-webinar/). Options such as [Just-in-time Registration](https://maximuslabs-ai.github.io/easywebinar-product-docs/product-docs/webinars/automated/just-in-time/) are set on the webinar's schedule, so check them on the **Overview** tab after the assistant creates it.

### AI Moderator (Beta) {#with-ai-moderator}

The **AI Moderator**, in Beta, answers attendee questions in the webinar chat. Ask the assistant to teach it your FAQs, and it adds them to what the moderator knows. The AI Moderator is part of EasyWebinar AI.

### Emails and pages {#with-emails-and-pages}

Emails and pages the assistant saves are the same ones you'd edit on the webinar's tabs, including [confirmation emails](https://maximuslabs-ai.github.io/easywebinar-product-docs/product-docs/webinars/notifications/confirmation-emails/). Change them later in the dashboard or in the chat.

### Registrants' data {#with-registrants}

If you ask, the assistant can read your registrants' and attendees' names, email addresses and attendance. That data is then processed by the AI provider you chose, under its own privacy policy. See [Using EasyWebinar with AI assistants](https://easywebinar.com/privacy/#ai-assistants).

### Your CRM {#with-your-crm}

The connector works inside EasyWebinar. Registrants still reach your CRM through your [integrations](https://maximuslabs-ai.github.io/easywebinar-product-docs/product-docs/integrations/map-webinar-data/), so tags and fields keep working as before.

## Who uses the AI connector, and how {#who-uses-it}

These are typical patterns, shown to illustrate how the connector fits different teams.

### Coaches and consultants {#coaches}

A [coach](https://easywebinar.com/webinar-platform-for-coaches-course-creators/) asks ChatGPT for her upcoming sessions on Monday morning and has it write the reminders for the next one.

### Course creators {#course-creators}

A [course creator](https://easywebinar.com/solutions/course-creator/) asks Claude to schedule an evergreen webinar and add an offer for his course, then approves both.

### Marketing teams {#marketing-teams}

A [marketing team](https://easywebinar.com/solutions/marketing-teams/) compares attendance across this quarter's webinars in one chat, and pastes the answer into its weekly report.

### Agencies {#agencies}

An [agency](https://easywebinar.com/solutions/marketing-agencies/) manager has Claude write a client's registration page, reads it in the chat, and approves it to publish.

## How the AI connector compares {#compare}

EasyWebinar is listed in both ChatGPT and Claude, and you connect it by signing in with your normal login. Some webinar tools need an admin role or a developer setup first.

Connecting a webinar platform to ChatGPT and Claude, from each vendor's public documentation:

| Platform | ChatGPT and Claude | How you connect | Who can connect |
|---|---|---|---|
| **EasyWebinar** | Yes (listed in both) | Search *EasyWebinar*, click **Connect**, sign in | Anyone with an EasyWebinar login, with their own permissions |
| **Livestorm** | Yes ([Claude directory; server URL in ChatGPT](https://support.livestorm.co/article/livestorm-mcp)) | Claude's directory, or a server URL in ChatGPT | Partly ([admins and workspace owners only](https://support.livestorm.co/article/livestorm-mcp)) |
| **Zoom** | Partly ([custom connector; ChatGPT Developer Mode](https://developers.zoom.us/docs/mcp/servers/connect-to-zoom-mcp-servers/)) | Build a Zoom Marketplace app, then add its OAuth details | Partly ([admin or developer authorisation](https://developers.zoom.us/docs/mcp/servers/connect-to-zoom-mcp-servers/)) |

*Yes: documented and built in. Partly: documented with a limit, shown in brackets.*

### Why EasyWebinar is the stronger choice for AI assistants {#compare-stronger}

- **No setup beyond signing in.** EasyWebinar is listed in ChatGPT and Claude. [Zoom's developer docs](https://developers.zoom.us/docs/mcp/servers/connect-to-zoom-mcp-servers/) describe building a Marketplace app, adding OAuth credentials and using ChatGPT Developer Mode. Compare [EasyWebinar vs Zoom](https://easywebinar.com/compare/easywebinar-vs-zoom/).
- **Every user, not just admins.** Each person signs in with their own login and keeps their own permissions. [Livestorm's help centre](https://support.livestorm.co/article/livestorm-mcp) says only admins and workspace owners can use its connector. Compare [EasyWebinar vs Livestorm](https://easywebinar.com/compare/easywebinar-vs-livestorm/).
- **From setup to follow-up in one chat.** The connector covers webinars, pages and emails, engagement and analytics, including evergreen webinars and the AI Moderator.

*Competitor details checked against each vendor's public documentation on 4 November 2026. Features and plans change, so confirm with the vendor before you decide.*

## Limits and things to know {#limits}

- **Approved changes go live.** Pages and emails you approve are published and sent to your registrants. Review them before you approve.
- **One account per sign-in.** To use another EasyWebinar account, disconnect and connect again with that account's login.
- **Sign-in renews for up to 30 days.** Disconnect at any time to end access at once.
- **Request logs.** EasyWebinar keeps technical logs of requests for 30 days, recording which action ran, when, and whether it succeeded.
- **Your conversations aren't stored.** EasyWebinar doesn't store your conversations with the assistant or use your data to train AI models.
- **Your AI provider's terms apply.** What the assistant reads from EasyWebinar is processed by OpenAI or Anthropic under their own privacy policies.

## Common questions {#common-questions}

#### How do I connect EasyWebinar to ChatGPT? {#faq-chatgpt}

In ChatGPT, go to **Settings → Apps**, search for **EasyWebinar**, click **Connect**, sign in with your EasyWebinar email and password, and approve access.

#### How do I connect EasyWebinar to Claude? {#faq-claude}

In Claude, go to **Settings → Connectors**, click **Browse connectors**, search for **EasyWebinar**, click **Connect**, sign in and approve access.

#### What can the assistant do in my account? {#faq-what}

It can list, create and schedule webinars, show registration links, write and publish pages, write emails, add polls and offers, teach your AI Moderator your FAQs, and report registrations and attendance.

#### Will the assistant change anything without asking? {#faq-approval}

No. Reading runs at once, but every action that creates, changes, publishes or deletes something asks for your approval first.

#### Can it reach other people's accounts? {#faq-other-accounts}

No. It works only in the account you signed in with, and with your permissions.

#### I have more than one EasyWebinar account. Which one does it use? {#faq-multiple-accounts}

The one you sign in with when you connect. To switch, disconnect and connect again with the other login.

#### Does EasyWebinar store my conversations? {#faq-conversations}

No. EasyWebinar doesn't store your conversations with the assistant or use your data to train AI models.

#### How do I disconnect? {#faq-disconnect}

In ChatGPT, go to **Settings → Apps → EasyWebinar → Disconnect**. In Claude, go to **Settings → Connectors → EasyWebinar → Disconnect**. Access ends at once.

#### Do emails the assistant writes get sent? {#faq-emails-sent}

Yes, once you approve them. Emails and pages saved through the assistant go live and reach your registrants, just like ones made in the dashboard.

#### Is the AI connector the same as an MCP server? {#faq-mcp}

Yes. The connector is built on the Model Context Protocol (MCP), the standard ChatGPT and Claude use to connect to other apps. You don't need to enter a server address: search for EasyWebinar in the assistant's settings.

#### How do I get better results? {#faq-tips}

Save your brand and business profile in EasyWebinar first, name the specific webinar, review pages, emails and schedules before you approve, and finish one edit before asking for the next.

## Related {#related}

- [Just-in-time webinars](https://maximuslabs-ai.github.io/easywebinar-product-docs/product-docs/webinars/automated/just-in-time/): evergreen sessions that start minutes after someone registers.
- [Create with AI](https://maximuslabs-ai.github.io/easywebinar-product-docs/product-docs/ai/create-with-ai/): build a whole webinar inside EasyWebinar from a description.
- [Create and schedule a live webinar](https://maximuslabs-ai.github.io/easywebinar-product-docs/product-docs/webinars/getting-started/create-a-live-webinar/): the dashboard steps behind *create a live webinar*.
- [Webinar analytics](https://maximuslabs-ai.github.io/easywebinar-product-docs/product-docs/webinars/analytics/webinar-analytics/): the figures the assistant reports.
- [Limits and defaults](https://maximuslabs-ai.github.io/easywebinar-product-docs/product-docs/reference/limits-and-defaults/): the AI connector's sign-in length next to every other limit.
