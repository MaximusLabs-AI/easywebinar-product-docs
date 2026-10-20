# Connect a CRM and map your webinar data

Connect one of EasyWebinar's 14 CRM and email integrations, tag contacts by what they did, and send webinar details into your CRM's own fields.

- Applies to: All plans · any team member · set per webinar
- Status: Live
- Verified: 2026-10-16
- Canonical page: https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/integrations/map-webinar-data/

Connecting a CRM does more than copy email addresses across. You can tag people by **what they actually did** (attended, missed, watched the replay, left early, clicked your offer) and push details like each person's join link into your CRM's fields.

**Expected result:** a connected integration on your webinar, with event mappings that tag contacts and custom fields that receive webinar data.

## Before you begin {#before-you-begin}

- **Create your tags in the CRM first**, then select them in EasyWebinar.
- **Custom fields must exist in your CRM** before you can map to them.
- Integrations are set **per webinar**, so connecting one doesn't connect the rest. Different webinars can feed different lists.

## Supported integrations {#supported-integrations}

| | | |
|---|---|---|
| GoHighLevel | Mailchimp | Constant Contact |
| Keap | Ontraport | iContact |
| AWeber | HubSpot | InfluencerSoft |
| Kit (ConvertKit) | ActiveCampaign | EasyCRM |
| GetResponse | Drip | |

**EasyCRM** is EasyWebinar's own CRM and connects the same way.

## Connect an integration {#connect}

1. Open your webinar and click the **Integrations** tab.
2. Find your tool under **Available integrations** and click **Connect**.
3. Sign in to that service and allow access.

It moves up to **Connected apps**, marked **Ready to use**.

## Map events to tags {#map-events-to-tags}

Click your connected integration to open its settings. The first tab is **Event mappings**: "Map webinar events to CRM tags, lists, and custom fields."

![The Event mappings tab](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/images/integrations/step-01-event-mappings.png)

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

![The Custom fields tab](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/images/integrations/step-02-custom-fields.png)

| Webinar data | What it's for |
|---|---|
| **Webinar Title** | Which webinar this contact came from |
| **Webinar Join Link** | The attendee's personal join link |
| **Webinar Join Short Link** | A shortened version |
| **Webinar Replay Link** | Their replay link |
| **Webinar Replay Short Link** | A shortened version |
| **Phone Number** | Their phone, if collected |

Pick the matching CRM field beside each one. **Refresh** pulls in fields you have just created in the CRM.

### Send reminders from your CRM {#reminders-from-crm}

Mapping the **join link** lets you send reminders from your CRM instead of EasyWebinar, because each contact gets their own working link.

## Verify the result {#verify-the-result}

- The integration shows under **Connected apps** as **Ready to use**.
- Your rules appear under **Current mappings**.
- Register a test contact and check the tag and fields arrive in your CRM.

## Change or disconnect {#change-or-disconnect}

**Change integration** swaps the connected tool. **Disconnect** removes it from the webinar.

## Common questions {#common-questions}

#### Can I tag no-shows? {#faq-no-shows}

Yes, with the **Missed** event.

#### My CRM field isn't in the list. {#faq-missing-field}

Create it in your CRM, then click **Refresh**.

#### What if my tool isn't one of the 14? {#faq-other-tools}

Check whether it accepts data from one of the listed platforms, or use EasyCRM.

## Next steps {#next-steps}

- [Offers and the countdown timer](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/webinars/engagement/timed-offers/)
- [Limits and defaults](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/reference/limits-and-defaults/#team-and-account)
