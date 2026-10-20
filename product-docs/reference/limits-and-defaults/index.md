# Limits and defaults

Every limit, allowance and default setting in EasyWebinar in one place, with its unit and where it applies.

- Applies to: All plans unless a row says otherwise
- Status: Live
- Verified: 2026-10-16
- Canonical page: https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/reference/limits-and-defaults/

Use this page to check a number before you plan a webinar. Each row names the unit and where the limit applies. Prices are not listed here; see the [live pricing page](https://easywebinar.com/pricing/) for current prices.

## Attendee capacity by plan {#attendee-capacity}

| Plan | Live attendees | Automated attendees |
|---|---|---|
| **Launch** | 50 | Not listed |
| **Growth** | 200 | 1,000 |
| **Pro** | 500 | 2,500 |
| **Scale** | 1,000 | 5,000 |

Capacities as shown in the plan chooser. [Plans](https://easywebinar.com/pricing/) are billed monthly or yearly. The **Plan** tab under **Settings** meters live attendees, automated attendees and storage.

- **Live attendees** counts people joining live sessions in the current period.
- **Automated attendees** counts people watching [simulive](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/webinars/getting-started/create-a-simulive-webinar/#with-plan-usage) and [evergreen](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/webinars/getting-started/create-an-evergreen-webinar/#with-plan-usage) sessions.
- **Usage resets with your billing period**, so the meters show the current period only.

Check the meters before a big promotion. Running out of live attendee capacity mid-launch is an avoidable problem, and [add-ons for high-traffic webinars](https://easywebinar.com/blog/add-ons-for-high-traffic-webinars/) covers planning for a large audience.

## Webinars and scheduling {#webinars-and-scheduling}

| Item | Value | Notes |
|---|---|---|
| Webinar name | Character counter on the field | |
| Webinar type | Fixed after creation | [Clone the webinar](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/webinars/getting-started/clone-a-webinar/#choose-type) to change it |
| Default webinar type | **Live Webinar** | [Choose the type](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/webinars/getting-started/create-a-live-webinar/#name-and-type) when you create it |
| Default schedule frequency | **Specific Date** | Also **Daily** or **Weekly** |
| Default timezone | Your account timezone | |
| Default schedule preference | Show only the next available session | |
| Past sessions | Can't be scheduled | Past dates are disabled |
| Just-in-time interval | 2, 15, 30, 45 or 60 minutes | Evergreen webinars only; see [choosing an interval](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/webinars/automated/just-in-time/#choosing-an-interval) |
| Sessions in the attendee's local time | [Just-in-time sessions only](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/webinars/automated/just-in-time/#timezones) | Live and scheduled sessions use the webinar's timezone |
| Webinars live at once | One | Starting another shows ["You can only have one event live at a time."](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/troubleshooting/camera-not-detected/#one-event-live) |

## Registration and selling {#registration-and-selling}

| Item | Value | Notes |
|---|---|---|
| Default pricing | **Free** | [Choose **Paid** at creation](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/webinars/selling/paid-webinars/#choose-paid-at-creation) |
| Price currency | US dollars | Stripe may show local currency to attendees outside the US |
| Payment processor | [Stripe](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/webinars/selling/paid-webinars/#before-you-begin) | Payouts go to your own Stripe account |
| Default registration fields | Full name, Email | Both required; [add custom fields](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/webinars/registration/custom-fields/) |
| Registration templates | [17 templates](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/webinars/registration/registration-page-builder/#choose-a-template), plus your own under **My Templates** | Filter by Agency, Coach, Education, Health & Wellness, Lead Magnet or Marketing |
| [Polls](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/webinars/engagement/polls/) per webinar | No practical limit | |

## Video and media {#video-and-media}

| Item | Value | Notes |
|---|---|---|
| [Video upload format](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/webinars/media/video-hosting/#host-on-easywebinar) | MP4 | The Video Selection screen also lists MOV and WebM; the Upload media dialog says MP4 only |
| Maximum video upload | 4 GB per file | |
| Video import | YouTube, Vimeo, Wistia or a direct MP4 link | Uses no storage; [enter the duration](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/webinars/media/video-hosting/#import-from-url) so sessions can be scheduled |
| Additional storage | 5 GB per add-on | See [storage and your plan](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/webinars/media/library/#with-plan) |
| AI Moderator (Beta) knowledge base | PDF, DOCX or PPTX, up to 25 MB per file | Retrains after each upload |

## AI credits {#ai-credits}

[Create with AI](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/ai/create-with-ai/#credits) uses credits, shown at the top right of every step.

| Part generated | Credits |
|---|---|
| [Script](https://easywebinar.com/ai-webinar-script-generator/) | 10 |
| [Landing pages](https://easywebinar.com/ai-webinar-registration-page-builder/) | 10 |
| [Emails](https://easywebinar.com/ai-webinar-email-generator/) | 1 |
| Polls | 1 |
| Offers | 1 |
| **Full build** | **About 23** |

A full build takes about ten minutes.

## EasyCRM sending allowance {#easycrm-allowance}

| Channel | Included each month |
|---|---|
| Emails | 1,000 |
| SMS | 100 messages |
| Call minutes | 100 |

Everything [EasyCRM](https://easywebinar.com/easycrm/) sends draws on this monthly allowance, and its **Wallet** screen shows what's left. The allowance resets on your **signup date**, not the first of the month. Broadcasts and workflows draw on the same allowance, and each channel is counted separately.

## Team and account {#team-and-account}

| Item | Value | Notes |
|---|---|---|
| [Roles](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/account/team-members/#roles) | Owner, Admin, User | One Owner per account |
| Team seats | Depend on your plan | Settings overview shows [seats used](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/account/team-members/#before-you-begin) |
| Client workspaces | Each on its own plan | Workspaces don't use team seats; built for [agencies running client webinars](https://easywebinar.com/solutions/marketing-agencies/) |
| [Integrations](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/integrations/map-webinar-data/) | Set per webinar | Connecting one webinar doesn't connect the others |

## Add-ons {#add-ons}

Add-ons extend your plan without changing it. Switch one on with **Add to plan** on the **Add-ons** tab under **Settings → Manage Plan**.

| Add-on | What it unlocks |
|---|---|
| **White Label** | Removes EasyWebinar branding |
| **C-Name** | A custom domain for webinar pages |
| **[Paid Webinars](https://easywebinar.com/paid-webinars/)** | Checkout for webinars |
| **EasyCRM** | The built-in CRM |
| **Additional Storage** | 5 GB more storage |
| **One-Time Webinar Setup** | The EasyWebinar team configures a webinar for you |

## Related {#related}

- [Webinars overview](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/webinars/): the three webinar types, and why the type is fixed once you create a webinar.
- [The webinar Overview tab](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/webinars/setup/overview-tab/#registration-pricing): where one webinar's free or paid setting and live stats sit.
