# Webinar CRM Email Setup: Verify a Domain or Address and Choose a Sending Provider

How to set up sending so CRM broadcasts and workflows go out from your own domain or address: pick an email service, verify a domain or business address, choose where replies go, and check sending before your first send.

- Applies to: EasyCRM broadcasts and workflows · set once under Configurations · a webinar's own emails have separate settings
- Status: Live
- Verified: 2026-11-02
- Canonical page: https://maximuslabs-ai.github.io/easywebinar-product-docs/product-docs/easycrm/sending-setup/

Webinar CRM email sending has to be set up before a single broadcast or workflow can leave your account. The job has three parts: choose an email service, verify the domain or business address you send as, and decide where replies go. In EasyWebinar you do all of it once, on the **Configurations** screen of its built-in CRM, [EasyCRM](https://easywebinar.com/easycrm/). A webinar's own confirmation and reminder emails aren't part of this setup, because each webinar has separate settings for them.

## At a glance {#at-a-glance}

| | |
|---|---|
| **What you set up** | The email service, sending identity and reply address for CRM broadcasts and workflows |
| **Where you set it** | EasyCRM → **Configurations** → **Email Integration** |
| **To send from your own domain** | Complete **Domain Configuration**, which takes more setup and gives better deliverability |
| **To send from one address** | Validate a single business email address, which is quicker and suits lower volume |
| **Email services on the screen** | **EasyCRM Mail**, marked **Default**, or your own Amazon SES, SendGrid or Mailgun account |
| **When to do it** | Once, before you build any broadcast or workflow |
| **Also on this screen** | **Call Integration** and **SMS Integration** (Beta) |
| **What sends count against** | Your monthly **Wallet** allowance |
| **What it leaves alone** | A webinar's own emails, set under **Email Settings** on its **Notifications** tab |

## What webinar CRM email setup covers {#what-it-is}

Webinar CRM email setup is the step between having contacts and being able to message them. People arrive in the CRM from your webinars, and [broadcasts and workflows handle the communication](https://easywebinar.com/blog/how-to-automate-webinar-follow-ups-with-crm-tools/) after that. Neither can send until this step is finished.

The setup rests on two separate decisions, and it helps to keep them apart. The **email service** is the system that carries your mail out of the CRM. The **sending identity** is the domain or address your mail comes from, verified so the CRM will send as you. Choosing a service doesn't verify your identity, and verifying your identity doesn't choose a service.

### What you see on the screen {#what-you-see}

**Configurations** opens on a row of channel tabs, one for each way the CRM can reach someone:

| Tab | What it connects |
|---|---|
| **Email Integration** | Your email service, sending identity and reply settings |
| **Call Integration** | Calling, with minutes metered in your **Wallet** |
| **SMS Integration** (Beta) | Text messages, with a separate allowance in your **Wallet** |
| **Whatsapp** | Marked **Coming soon** in EasyCRM |

**Email Integration** has four parts. **Email provider** lists your services, **Reply & forwarding settings** decides where replies go, and **Analytics** sits beside those two. **Domains** is a button on the provider list.

## Why webinar CRM email sending matters {#why-it-matters}

### What it's for {#what-its-for}

This setup answers one question: how do my CRM broadcasts and workflows go out from my own domain or address? It connects an email service and proves who you send as. You do it once, before you build anything.

### How it helps {#how-it-helps}

- **It opens the gate.** Broadcasts and workflows can go out once a service and a verified sender are in place.
- **It puts your name on the mail.** Your contacts see a domain or address that belongs to your business.
- **It improves your deliverability.** A verified domain gives you better deliverability than a verified single address.
- **It brings replies back to you.** You choose the address, so a reply reaches someone who reads it.

### What happens without it {#without-it}

Nothing sends. A broadcast you have written can't go out, and a published workflow can't reach anyone. People often find this out on the day of their first send, when an offer or a replay link is already due.

### Why buyers care {#why-buyers-care}

This matters most to the admin or marketer who owns the first send, and to the owner whose domain carries the mail. It matters at the very start, before lists and campaigns exist. Domain work can need help from whoever holds your DNS, so leave time for it.

## The EasyWebinar approach to webinar CRM email sending {#approach}

{/* 5P */}

Take a typical case. A family-run garden centre with two branches has 1,800 leads from its spring planting webinars. The office admin is asked to send the first broadcast on Monday, for an offer closing on Friday. She opens the CRM, writes the email, and learns that nothing can go out yet.

The usual workaround is to export the list and send from the shared office mailbox or a separate email tool. That may get one message out, but it tends to cost more with each send. Results sit apart from the lead records, replies scatter, and the next send starts from a fresh export.

The job itself hasn't changed. Mail has to leave under a name that belongs to the business, and someone has to read the replies. That work only needs doing once if it lives where the broadcasts and workflows live. Every later send can then rely on it, so a busy admin doesn't repeat it.

EasyWebinar puts that job on one screen, **Configurations**, inside its CRM. It lists your email services, asks you to verify a domain or a single business address, and lets you choose where replies go. The garden centre's admin could validate the office address for Monday's send and plan the domain work for when volume grows.

One detail shows how firm the gate is. The screen tells you to verify your sending identity before you can start sending email, and that notice sits right above the list of services. The other platforms' options are covered in How EasyWebinar compares for webinar CRM email sending, below.

## How to set up webinar CRM email {#set-up}

Work through these steps in order, and do them before you build anything else in the CRM:

1. Click **Configurations** in the EasyCRM sidebar and stay on **Email Integration**.
2. Choose your email service under **Email provider**, connecting your own SMTP account if you use one.
3. Verify your sending identity, either a whole domain or a single business address.
4. Open **Reply & forwarding settings** and set an address someone reads.
5. Set up **Call Integration** and **SMS Integration** (Beta) if you need them.
6. Run the checks described below, then build your broadcasts and workflows.

### What to have ready {#what-to-have-ready}

EasyCRM is a plan add-on, which you can check under **Plan & Billing → Add-ons**, and [plans and add-ons are on the pricing page](https://easywebinar.com/pricing/). You reach it by clicking **EasyCRM** under **Other Products** in the EasyWebinar sidebar, using the same login.

A few things save time once you start. If you're verifying a domain, you need access to its DNS settings, or a colleague who has it. That colleague can [work from their own team member login](https://maximuslabs-ai.github.io/easywebinar-product-docs/product-docs/account/team-members/). If you're connecting a provider, have your account credentials to hand. You also need a reply address that a person actually reads.

### Open the Configurations screen {#open-configurations}

Click **Configurations** in the EasyCRM sidebar. Three areas on the screen do most of the work: the channel tabs, the verification notice and the list of services.

<figure>

![The EasyCRM Configurations screen open on Email Integration, with a notice about verifying your sending identity above a Select Email service list showing EasyCRM Mail as Default and a connected SMTP provider.](https://maximuslabs-ai.github.io/easywebinar-product-docs/product-docs/images/screens/easycrm-sending/step-01-configurations.webp)

<figcaption>Start here for every send. The notice above the list says what must be verified, and the Sending health label sits beside the default service.</figcaption>
</figure>

### Choose an email service {#choose-service}

The list is headed **Select Email service**, and it invites you to connect an SMTP provider to send emails from EasyCRM. **EasyCRM Mail** is already on the list, marked **Default**. To use your own provider, click **Add Service**, then **Configure** on the one you use, and enter its credentials. The next section explains how to choose.

### Verify who you send as {#verify-identity}

The notice on the screen sets out the requirement. You must either complete **Domain Configuration** for a dedicated domain, or validate a single business email address under **Email addresses**. Either route counts, and nothing sends until one of them is done. The **Domain Configuration** link in the notice and the **Domains** button both sit on this screen.

### Decide where replies go {#reply-forwarding}

**Reply & forwarding settings** decides where replies to your email go. Point it at an address someone reads, because people reply to marketing email more than you might expect. A monitored team inbox is a sensible choice for a small business, since replies still get seen when one person is away.

### Add call and SMS (Beta) sending {#call-sms}

**Call Integration** and **SMS Integration** (Beta) have their own tabs, and you set them up the same way as email. Skip both if your first sends are email only, and come back when you need them. Calling is connected here, and your **Wallet** meters the minutes.

WhatsApp (Beta) can't be set up here yet, because the **Whatsapp** tab in EasyCRM is marked **Coming soon**. WhatsApp (Beta) notifications are available on the EasyWebinar side, under a webinar's **Notifications** tab.

## Domain or single address: which to verify {#domain-or-address}

You don't need your own domain to send broadcasts, because a single business email address also counts as a sending identity. The choice depends on how much you send and how much setup you can take on now.

| | **Domain Configuration** | **A single business email address** |
|---|---|---|
| **What you verify** | A dedicated domain you own | One address |
| **Setup effort** | More setup, including DNS work | Quicker |
| **Suits** | Sending in any volume | Lower volume and small sends |
| **Deliverability** | The better of the two | Weaker than a verified domain |
| **Who may need to help** | Whoever holds your DNS | Usually nobody else |

EasyWebinar's guidance is that a verified domain is worth the DNS work if you send in any volume. If your first send is a small list and it's due soon, the single address is the quicker way to start. Neither route can promise that a given message lands in the inbox, since the receiving mail system makes that decision. For the wider picture, [our guide to webinar email marketing](https://easywebinar.com/blog/email-marketing-strategies-to-boost-webinar-attendance/) covers what happens after your mail is sending.

### A sending domain isn't a page domain {#sending-vs-page-domain}

Two settings use the word "domain", and they do different jobs. **Domain Configuration** under **Configurations** concerns the email your CRM sends. **Custom domain (C-Name)** under **Settings** → **Edit Profile** points your own domain at your webinar pages, so links read `webinars.yourcompany.com`.

The page setting needs the **C-Name** add-on plus a CNAME record, and it changes the [public links people click](https://maximuslabs-ai.github.io/easywebinar-product-docs/product-docs/webinars/registration/sharing-links/). Treat them as two separate jobs, even if you use the same company domain for both.

## Built-in mail or your own SMTP provider {#choose-provider}

Yes, you can use your own SMTP provider. Three are offered, and each sends through an account you hold with that company, so you need an account there first. EasyCRM sends through your provider rather than instead of it.

| Option on the screen | Powered by | What you need |
|---|---|---|
| **Amazon SES SMTP Mail** | Amazon SES | Your own Amazon SES account and its credentials |
| **Sendgrid SMTP Mail** | SendGrid | Your own SendGrid account and its credentials |
| **Mailgun SMTP Mail** | Mailgun | Your own Mailgun account and its credentials |

**EasyCRM Mail** appears above any provider you add. It carries the **Default** badge and has no **Configure** button of its own, and a connected provider shows a **Connected** badge with its server address. You pick between them with the selector at the left of each row.

The choice usually comes down to what you already run. If your company has an SES, SendGrid or Mailgun account that someone manages, connect it. If you have no provider account, start from the default row and leave provider work for later. Whichever you select, the verification notice still applies, so choosing a service never replaces verifying your identity.

## Check sending before your first broadcast {#check-before-send}

Run through this short list once the steps are done, and again before any large send:

- **Email service.** The service you want is selected under **Email provider**, and a provider you added shows **Connected**.
- **Sending health.** Look at **Sending health**, beside **EasyCRM Mail**, before you send through that service.
- **Sending identity.** Your domain or single address has finished verification.
- **Replies.** **Reply & forwarding settings** points at an address someone reads.
- **Allowance.** Your **Wallet** has room for the send. A channel that runs out stops sending until the cycle resets.
- **List size.** [Send to a targeted list rather than everyone](https://easywebinar.com/blog/email-segmentation-for-webinar-follow-ups/), because it helps on both allowance and open rate.

It's also worth making your first broadcast a small one. Broadcasts send to the list you pick, so a short list of your own colleagues lets you see the message arrive and test a reply. Workflows are safe to build at this stage, since a draft sends nothing until you publish it.

### Read the first results {#first-results}

Once a broadcast has gone out, **Marketing → Broadcasts** is the first place a sending problem shows. The screen sets your average open rate against an industry average of 21%, and your average click rate against 2.6%.

<figure>

![The EasyCRM Broadcasts screen with cards for total broadcasts, total sent, average open rate and average click rate, above a list of two completed email broadcasts.](https://maximuslabs-ai.github.io/easywebinar-product-docs/product-docs/images/screens/easycrm-broadcasts/step-01-broadcasts.webp)

<figcaption>After your first send, compare these cards with the industry averages shown beneath them. The figures here are sample data from a test account.</figcaption>
</figure>

A low open rate usually points to the subject line or the sender, so recheck your sending identity along with your wording. A good open rate with a low click rate means the email was opened and the offer didn't land, which isn't a setup problem.

## When CRM emails aren't sending {#not-sending}

Most failures trace back to one of a few causes, and each has a place to look:

| What you notice | Likely cause | Where to fix it |
|---|---|---|
| Nothing goes out at all | The sending identity isn't verified, or no provider is connected | **Configurations** → **Email Integration** |
| A workflow never sends | It's still a draft, because only published workflows send | **Marketing → Campaign** |
| A channel stops partway through a cycle | That channel's allowance has run out | **Wallet**, then wait for the cycle to reset |
| The meter looks wrong | Your cycle follows your signup date, and older rows show **Not counted** | **Wallet** → recent activity |
| A meter moved more than you expected | Usually a workflow running automatically | **Wallet** → recent activity |
| Replies don't reach anyone | The reply address is one nobody reads | **Reply & forwarding settings** |

## What this setup leaves alone {#what-it-leaves-alone}

These settings don't change your webinar reminder emails. They cover EasyCRM broadcasts and workflows, and a webinar's own messages are set on that webinar.

Each webinar's [registration confirmation](https://maximuslabs-ai.github.io/easywebinar-product-docs/product-docs/webinars/notifications/confirmation-emails/), [reminders](https://maximuslabs-ai.github.io/easywebinar-product-docs/product-docs/webinars/notifications/reminder-emails/) and follow-ups live on its **Notifications** tab. Their **Email Settings** button holds the **Sender name**, **Reply-to email** and **Notify admin** settings. So if your reminder shows the wrong sender name, look there rather than in **Configurations**.

<figure>

![A webinar's Notifications tab open on Emails, with SMS and Whatsapp tabs marked Beta, an Email Settings button, and groups for registration confirmation and webinar reminders.](https://maximuslabs-ai.github.io/easywebinar-product-docs/product-docs/images/screens/the-notifications-section/step-01-emails.webp)

<figcaption>This screen is the other half of the picture: emails tied to one webinar, with their own sender settings, which your CRM sending setup leaves untouched.</figcaption>
</figure>

The same split applies to text messages. A webinar's own SMS (Beta) is built on the same **Notifications** tab, and those messages go from your EasyWebinar number. That builder needs a phone number for each person, which comes from the [Phone field on your registration form](https://maximuslabs-ai.github.io/easywebinar-product-docs/product-docs/webinars/registration/custom-fields/).

<figure>

![The SMS Builder (Beta) for a webinar, with SMS Settings on the left showing type, trigger and sender, and a grid of registration confirmation templates beside a phone preview.](https://maximuslabs-ai.github.io/easywebinar-product-docs/product-docs/images/screens/sms-notifications/step-01-sms-builder.webp)

<figcaption>The webinar SMS builder (Beta) opens from a webinar's Notifications tab, so it isn't where you connect SMS Integration (Beta) for the CRM.</figcaption>
</figure>

| Message | Where it's set | Covered by this setup |
|---|---|---|
| CRM broadcast | **Marketing → Broadcasts** | Yes |
| CRM workflow | **Marketing → Campaign** | Yes |
| Webinar confirmation, reminder or follow-up email | The webinar's **Notifications** tab | No |
| Webinar SMS (Beta) or WhatsApp (Beta) | The webinar's **Notifications** tab | No |

## What works with webinar CRM email setup {#works-with}

Several parts of the product rely on this setup or sit right beside it:

- **Broadcasts.** A broadcast is a one-off send to a list, such as a [replay link](https://maximuslabs-ai.github.io/easywebinar-product-docs/product-docs/webinars/media/replay-pages/) after a webinar or an [offer](https://maximuslabs-ai.github.io/easywebinar-product-docs/product-docs/webinars/engagement/timed-offers/) that's about to close. Each one depends on this setup being finished.
- **Workflows.** A workflow is an automated sequence, and [webinar follow-up](https://easywebinar.com/features/webinar-follow-up/) is the sensible first one to build. It keeps sending once published, so it relies on these settings for as long as it runs.
- **Wallet.** Email, SMS (Beta) and call minutes each have a monthly allowance, listed with the other [limits and defaults](https://maximuslabs-ai.github.io/easywebinar-product-docs/product-docs/reference/limits-and-defaults/). Workflows use more over time than broadcasts, because they keep sending every day.
- **Leads.** **Import from EasyWebinar** pulls registrants and attendees across from a webinar, so [the people in your webinar records](https://maximuslabs-ai.github.io/easywebinar-product-docs/product-docs/webinars/analytics/people/) can be sent to once sending works.
- **Another CRM.** You may prefer to send from a CRM you already use. In that case, [map your webinar data to that CRM](https://maximuslabs-ai.github.io/easywebinar-product-docs/product-docs/integrations/map-webinar-data/) and skip this setup, since [you don't need EasyCRM to run webinars](https://easywebinar.com/blog/webinar-crm/).

## Who sets up webinar CRM email {#who-uses-it}

### Small businesses and solo operators {#who-small-business}

An office admin or owner usually does this alone, with a first send already in the diary. Validating a single business address is the quick way to get going. Move to a domain once sending becomes regular, and ask whoever manages your website to help with the DNS.

### B2B marketing teams {#who-b2b-marketing}

A marketing team sending regularly gets the most from **Domain Configuration**, because volume is where a verified domain pays back. If the company already runs SES, SendGrid or Mailgun, connect that account with **Add Service** and agree who looks after the credentials.

### Coaches and consultants {#who-coaches}

For a coach, the reply is often the point of the email, because a reply can start a client conversation. Set **Reply & forwarding settings** with the same care as the identity, and use an address you check daily. A single business address often suits this kind of low-volume sending.

### Agencies {#who-agencies}

An agency often sends for a client whose domain it doesn't control, so the DNS work may sit with the client's own team. Raise it early, because DNS changes can take a few hours to propagate. A separate client workspace keeps that client's webinars, registrants and settings apart from yours.

## How EasyWebinar compares for webinar CRM email sending {#compare}

EasyWebinar sets the email service, the sending identity and the reply address on one screen in its own CRM. Those settings then serve broadcasts and workflows, with calling on the next tab. EasyWebinar is the only platform in this table that does all four.

Webinar CRM email sending features, from each platform's public documentation:

| Platform | Your own SMTP provider | Domain or single address verified | CRM broadcasts and workflows | Calling set up beside email |
|---|---|---|---|---|
| **EasyWebinar** | Yes | Yes | Yes | Yes |
| **eWebinar** | Yes ([SMTP service integration](https://ewebinar.com/help/smtp-service)) | Partly ([verified in SendGrid](https://ewebinar.com/help/sendgrid)) | Not in docs | Not in docs |
| **WebinarJam and EverWebinar** | Yes ([third-party SMTP service](https://support.webinarjam.com/en/articles/15370076-create-an-spf-record-for-integrated-smtp)) | Partly ([DKIM on your domain](https://support.webinarjam.com/en/articles/15370075-set-up-dkim-domain-authentication)) | Not in docs | Partly ([voice call reminders](https://support.webinarjam.com/en/articles/15369988-manage-webinar-notifications-and-reminders)) |
| **Demio** | Not in docs | Partly ([technical sender address is fixed](https://help.demio.com/en/articles/3524469-manage-your-email-settings)) | Not in docs | Not in docs |
| **Livestorm** | Partly ([your own email app via Zapier](https://support.livestorm.co/article/108-how-to-send-your-own-emails)) | Not in docs | Not in docs | Not in docs |
| **WebinarKit** | Not in docs | Not in docs | Partly ([broadcasts in its CRM](https://help.webinarkit.com/help/how-to-create-and-send-a-broadcast)) | Not in docs |
| **Kajabi** | Not in docs | Partly ([custom email domain](https://help.kajabi.com/en/articles/17175105-connect-a-custom-email-domain)) | Partly ([email sequences](https://help.kajabi.com/en/articles/17175112-create-an-email-sequence)) | Not in docs |

*Yes: documented and built in. Partly: documented with a limit, shown in brackets. Not in docs: not found in the vendor's public documentation.*

### Why EasyWebinar is the stronger choice for webinar CRM email sending {#compare-stronger}

- **Sending is part of the product.** EasyWebinar connects your service directly under **Configurations**, while [Livestorm's guide sends your own emails through a Zapier automation](https://support.livestorm.co/article/108-how-to-send-your-own-emails). More in [EasyWebinar vs Livestorm](https://easywebinar.com/compare/easywebinar-vs-livestorm/).
- **Two routes to a verified sender.** EasyWebinar accepts a dedicated domain or a single business address on the same screen, while [eWebinar's SendGrid steps run through verification in SendGrid](https://ewebinar.com/help/sendgrid). More in [EasyWebinar vs eWebinar](https://easywebinar.com/compare/easywebinar-vs-ewebinar/).
- **One setup for a CRM's sends.** EasyWebinar's setup serves CRM broadcasts and workflows, while [WebinarJam's third-party SMTP service is described for webinar emails](https://support.webinarjam.com/en/articles/15370076-create-an-spf-record-for-integrated-smtp). More in [EasyWebinar vs WebinarJam](https://easywebinar.com/compare/easywebinar-vs-everwebinar-webinarjam/).
- **A sending identity you verify.** EasyWebinar lets you verify your own domain for sending, while [Demio's technical sender address stays fixed](https://help.demio.com/en/articles/3524469-manage-your-email-settings). More in [EasyWebinar vs Demio](https://easywebinar.com/compare/easywebinar-vs-demio/).

*Competitor details checked against each vendor's public documentation on 2 November 2026. Features and plans change, so confirm with the vendor before you decide.*

## Limits of this sending setup {#limits}

These are the boundaries to plan around:

- **It covers the CRM only.** Broadcasts and workflows use it. A webinar's own emails, SMS (Beta) and WhatsApp (Beta) use that webinar's **Notifications** tab.
- **Verification comes first.** Nothing sends until your domain or address is verified, and no setting skips this step.
- **Three SMTP providers are offered.** They are Amazon SES, SendGrid and Mailgun, and each needs your own account with that company.
- **WhatsApp (Beta) isn't on this screen yet.** The **Whatsapp** tab in EasyCRM is marked **Coming soon**.
- **Sends draw on a monthly allowance.** Emails, SMS (Beta) and call minutes are counted separately, so running out of one leaves the others working. The cycle follows your signup date, not the calendar month.

## Common questions {#common-questions}

#### Can I use my own SMTP provider? {#faq-own-smtp}

Yes. EasyCRM offers Amazon SES, SendGrid and Mailgun. Click **Add Service**, then **Configure** on the provider you use, and enter its credentials. You still verify your domain or address, and sends still count against your **Wallet** allowance once sending is working.

#### Do I need my own domain to send broadcasts? {#faq-need-domain}

No. You can validate a single business email address instead, which is quicker and suits lower volume. EasyWebinar's guidance is to verify a domain if you send in any volume, since a domain gives better deliverability than a single address.

#### Do these settings change my webinar reminder emails? {#faq-reminders}

No. They apply to EasyCRM broadcasts and workflows. A webinar's confirmation, reminder and follow-up emails are set on that webinar's **Notifications** tab, and its **Email Settings** button holds their sender name and reply-to address.

#### Why isn't my CRM email sending? {#faq-not-sending}

Almost always, the sending identity isn't verified or no provider is connected. Open **Configurations**, check the notice on **Email Integration**, and finish whichever step is missing. If only a workflow is silent, check that it's published, because a draft sends nothing.

#### Do I need an account with the SMTP provider? {#faq-provider-account}

Yes. When you connect Amazon SES, SendGrid or Mailgun, EasyCRM sends through your account with that company rather than replacing it. So set up the account first, then bring its credentials to the **Configure** step on the **Email provider** tab.

#### Should I verify a domain or a single address? {#faq-domain-or-address}

Choose a domain if you send in volume and can make DNS changes. Choose a single business address if your sends are small or your first one is due soon. The domain route takes more setup, and it gives you better deliverability in return.

#### Where do replies to my broadcasts go? {#faq-replies}

Replies go wherever you set under **Reply & forwarding settings**, on the **Email Integration** tab. Point that setting at an address someone actually reads, such as a monitored team inbox, because people often reply to marketing email and expect an answer.

#### What is EasyCRM Mail? {#faq-easycrm-mail}

**EasyCRM Mail** is the service listed first under **Select Email service**, marked **Default**. Unlike a provider you add, its row has no **Configure** button. The verification notice sits above the whole list, so verify your domain or address whichever service you select.

#### Where do I check sending health? {#faq-sending-health}

On **Configurations**, under **Email Integration** and **Email provider**. **Sending health** sits beside **EasyCRM Mail** on the service list. Look there before your first send, then watch your open rate on the **Broadcasts** screen once mail has gone out.

#### What does call and SMS (Beta) setup involve? {#faq-call-sms}

**Call Integration** and **SMS Integration** (Beta) each have their own tab on **Configurations**, and you set them up the same way as email. Your **Wallet** meters call minutes and SMS (Beta) messages separately from your email allowance.

#### Do broadcasts and workflows need separate setup? {#faq-separate-setup}

No. You set up sending once on **Configurations**, and both broadcasts and workflows depend on it. Both also draw on the same **Wallet** allowance, so a workflow running every day leaves less room for your one-off broadcasts in that cycle.

#### Does my custom webinar page domain count for email? {#faq-c-name}

No. **Custom domain (C-Name)** points your own domain at your webinar pages, and **Domain Configuration** concerns the email your CRM sends. They are separate settings on separate screens, so finishing one doesn't complete the other, even with the same company domain.

## Related {#related}

- [Registration confirmation emails](https://maximuslabs-ai.github.io/easywebinar-product-docs/product-docs/webinars/notifications/confirmation-emails/): the webinar's own email that carries the join link, with separate sender settings.
- [Reminder emails](https://maximuslabs-ai.github.io/easywebinar-product-docs/product-docs/webinars/notifications/reminder-emails/): the messages to adjust when a reminder's timing or sender needs changing.
- [Connect a CRM and map your webinar data](https://maximuslabs-ai.github.io/easywebinar-product-docs/product-docs/integrations/map-webinar-data/): the route to take if your sends come from a different CRM.
- [Limits and defaults](https://maximuslabs-ai.github.io/easywebinar-product-docs/product-docs/reference/limits-and-defaults/): the monthly email, SMS (Beta) and call allowances in one table.
- [Everything EasyCRM includes](https://easywebinar.com/easycrm/): the leads, deals and marketing tools these sending settings serve.
- [EasyWebinar product documentation](https://maximuslabs-ai.github.io/easywebinar-product-docs/product-docs/): the full library, for the steps before and after your first send.
