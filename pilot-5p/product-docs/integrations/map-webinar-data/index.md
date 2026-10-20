# Connect a CRM and map your webinar data

Connect one of EasyWebinar's 14 CRM and email integrations, tag contacts by what they did, and send webinar details into your CRM's own fields.

- Applies to: All plans · any team member · set per webinar
- Status: Live
- Verified: 2026-10-16
- Canonical page: https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-5p/easywebinar-product-docs/pilot-5p/product-docs/integrations/map-webinar-data/

Connecting a CRM does more than copy email addresses across. You can tag people by **what they actually did** (attended, missed, [watched the replay](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-5p/easywebinar-product-docs/pilot-5p/product-docs/webinars/media/replay-pages/), left early, [clicked your offer](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-5p/easywebinar-product-docs/pilot-5p/product-docs/webinars/engagement/timed-offers/)) and push details like each person's [join link](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-5p/easywebinar-product-docs/pilot-5p/product-docs/webinars/registration/sharing-links/#attendee-join-link) into your CRM's fields.

**Expected result:** a connected integration on your webinar, with event mappings that tag contacts and custom fields that receive webinar data.

## Why it matters {#why-it-matters}

Connecting a webinar to your CRM or email platform means registrants and attendees arrive in the system you already work in, without exporting anything. Tagging by behaviour is what turns a webinar into something your [sales follow-up](https://easywebinar.com/features/webinar-follow-up/) can act on. A no-show can start a replay sequence, while someone who clicked your offer goes to the top of the sales list.

Registrants and attendees are different events, so you can treat someone who attended apart from someone who only registered. Without that split, everyone on the list gets the same follow-up, whether they watched to the end or never turned up. That gap is what [tracking webinar leads in your CRM](https://easywebinar.com/blog/tracking-webinar-leads-with-crm-integration/) is meant to close.

## Before you begin {#before-you-begin}

- **Create your tags in the CRM first**, then select them in EasyWebinar.
- **Custom fields must exist in your CRM** before you can map to them.
- Integrations are set **per webinar**, so connecting one doesn't connect the rest. Different webinars can feed different lists.

## Supported integrations {#supported-integrations}

| | | |
|---|---|---|
| GoHighLevel | Mailchimp | Constant Contact |
| Keap | Ontraport | iContact |
| AWeber | [HubSpot](https://easywebinar.com/integrations/hubspot-integration/) | InfluencerSoft |
| Kit (ConvertKit) | [ActiveCampaign](https://easywebinar.com/integrations/activecampaign-integration/) | EasyCRM |
| GetResponse | Drip | |

**[EasyCRM](https://easywebinar.com/easycrm/)** is EasyWebinar's own CRM and connects the same way. The full list, with what each connection is for, is on the [integrations overview](https://easywebinar.com/integrations/).

## Connect an integration {#connect}

1. Open your webinar and click the **Integrations** tab.
2. Find your tool under **Available integrations** and click **Connect**.
3. Sign in to that service and allow access.

It moves up to **Connected apps**, marked **Ready to use**.

## Map events to tags {#map-events-to-tags}

Click your connected integration to open its settings. The first tab is **Event mappings**: "Map webinar events to CRM tags, lists, and custom fields."

![The Event mappings tab](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-5p/easywebinar-product-docs/pilot-5p/images/integrations/step-01-event-mappings.png)

| | Control | What it does |
|---|---|---|
| 1 | **Event mappings / Custom fields** | The two halves of the integration |
| 2 | **Add a mapping** | Builds a new rule |
| 3 | **Current mappings** | Rules already running |

A mapping is three choices: **When** (the event) → **Then** (the action) → **Value** (the tag). Pick each one and click **Add mapping**.

### The events you can trigger on {#events}

| Event | Fires when someone |
|---|---|
| **Registered** | Signs up |
| **Attended** | Joins the session |
| **Missed** | Registers and never shows |
| **Watched replay** | Views the recording |
| **Didn't watch replay** | Never views it |
| **Joined webinar after** | Arrives later than a point you set |
| **Left webinar before** | Leaves before a point you set |
| **Left early** | Leaves before the end |
| **Stayed on webinar at least** | Stays a minimum length of time |
| **Watched full** | Watches the whole thing |
| **Clicked offer** | Clicks your offer |

### A starting set of tags {#starter-tags}

"Registered" is a weak signal; **Watched full** and **Clicked offer** are strong ones. Tag them separately so your sales team works the right people first:

- *Registered* → `webinar-registered`
- *Missed* → `webinar-no-show`, and trigger your replay sequence
- *Watched full* → `webinar-engaged`
- *Clicked offer* → `webinar-hot`, and notify sales

## Map custom fields {#map-custom-fields}

The **Custom fields** tab sends webinar details into your CRM's own fields: "Choose which of your CRM's custom fields should receive each piece of webinar data."

![The Custom fields tab](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-5p/easywebinar-product-docs/pilot-5p/images/integrations/step-02-custom-fields.png)

| Webinar data | What it's for |
|---|---|
| **Webinar Title** | Which webinar this contact came from |
| **Webinar Join Link** | The attendee's personal join link |
| **Webinar Join Short Link** | A [shortened version](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-5p/easywebinar-product-docs/pilot-5p/product-docs/webinars/registration/sharing-links/#shorten-links) |
| **Webinar Replay Link** | Their [replay page link](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-5p/easywebinar-product-docs/pilot-5p/product-docs/webinars/media/replay-pages/#with-crm) |
| **Webinar Replay Short Link** | A shortened version |
| **Phone Number** | Their phone, if your [registration form collects it](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-5p/easywebinar-product-docs/pilot-5p/product-docs/webinars/registration/custom-fields/#set-up-the-form) |

Pick the matching CRM field beside each one. **Refresh** pulls in fields you have just created in the CRM.

### Send reminders from your CRM {#reminders-from-crm}

Mapping the **join link** lets you send reminders from your CRM instead of [EasyWebinar's own reminder emails](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-5p/easywebinar-product-docs/pilot-5p/product-docs/webinars/notifications/reminder-emails/#with-crm), because each contact gets their own working link.

## How it works with other features {#works-with}

### Registration fields {#with-registration-fields}

The **Phone Number** field only has something to send if your registration form collected it. Select the form block in the page builder and add the **Phone** field; [custom registration fields](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-5p/easywebinar-product-docs/pilot-5p/product-docs/webinars/registration/custom-fields/#in-your-crm) covers the other fields you can add.

### The People view {#with-people-view}

[People](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-5p/easywebinar-product-docs/pilot-5p/product-docs/webinars/analytics/people/#with-crm) is every registrant and attendee across all your webinars in one table, and you can filter it by behaviour and source and export the list. It is a quick way to check who should have received a tag, or to follow up with people outside your CRM rules.

### Cloning {#with-cloning}

When you [clone a webinar](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-5p/easywebinar-product-docs/pilot-5p/product-docs/webinars/getting-started/clone-a-webinar/#with-integrations), **Integration settings** is one of the groups you can copy. Tick it to bring this webinar's integration settings across to the copy.

### EasyCRM {#with-easycrm}

You don't need EasyCRM to run webinars. It's for managing the people your webinars produce. Registrants reach it by connecting EasyCRM as an integration on a webinar, as on this page, or with **Import from EasyWebinar** on its Leads screen.

### Streaming {#with-easycast}

The **Social media** category on the Integrations tab is separate from CRMs. To broadcast a webinar to YouTube or LinkedIn while it runs, use [EasyCast](https://easywebinar.com/easycast/), under **Integrations** in the sidebar.

## Verify the result {#verify-the-result}

- The integration shows under **Connected apps** as **Ready to use**.
- Your rules appear under **Current mappings**.
- Register a test contact and check the tag and fields arrive in your CRM.

## Change or disconnect {#change-or-disconnect}

**Change integration** swaps the connected tool. **Disconnect** removes it from the webinar.

## Limits and things to know {#limits}

- **Integrations are per webinar.** Connecting one doesn't connect the rest, and different webinars can feed different lists.
- **Connecting needs an account with that service**, and you sign in to it during setup.
- **Tags and custom fields must exist in your CRM first.** Use **Refresh** after adding a field.
- **There are 14 integrations**, including EasyWebinar's own EasyCRM.

## Common questions {#common-questions}

#### Can I tag no-shows? {#faq-no-shows}

Yes, with the **Missed** event.

#### My CRM field isn't in the list. {#faq-missing-field}

Create it in your CRM, then click **Refresh**.

#### What if my tool isn't one of the 14? {#faq-other-tools}

Check whether it accepts data from one of the listed platforms, or use EasyCRM.

#### Do I have to connect every webinar separately? {#faq-every-webinar}

Yes, integrations are set per webinar. Cloning a webinar with **Integration settings** ticked brings those settings across to the copy.

#### Will it sync people who registered but didn't attend? {#faq-registrants}

Yes. Registrants and attendees sync as separate events, so you can treat no-shows differently.

#### Can I send the join link to my CRM? {#faq-join-link}

Yes. Map **Webinar Join Link** to one of your custom fields on the Custom fields tab.

#### Can I stream my webinar to YouTube or LinkedIn from here? {#faq-streaming}

Not from this tab. Use **EasyCast**, a separate item under **Integrations** in the sidebar.

## Next steps {#next-steps}

- [Offers and the countdown timer](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-5p/easywebinar-product-docs/pilot-5p/product-docs/webinars/engagement/timed-offers/#with-crm): the offers behind the **Clicked offer** event.
- [Limits and defaults](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-5p/easywebinar-product-docs/pilot-5p/product-docs/reference/limits-and-defaults/#team-and-account): the per-webinar integration rule alongside other account limits.
- [Webinar analytics](https://maximuslabs-ai.github.io/easywebinar-product-docs/pilot-5p/easywebinar-product-docs/pilot-5p/product-docs/webinars/analytics/webinar-analytics/#with-crm): compare attendance and offer clicks with what reached your CRM.
- [Automate follow-ups with CRM tools](https://easywebinar.com/blog/how-to-automate-webinar-follow-ups-with-crm-tools/): ideas for the sequences your tags can trigger.
