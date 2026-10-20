# Camera not detected: "Not able to access selected media device"

Why the live room can't open your camera or microphone, and how to get into the green room.

- Applies to: Hosts, co-hosts and moderators entering the live room
- Status: Live
- Verified: 2026-10-16
- Canonical page: https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/troubleshooting/camera-not-detected/

## Symptom {#symptom}

When you click **Enter Room** from a [webinar's Overview tab](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/webinars/setup/overview-tab/#enter-room), the [device check](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/webinars/live-room/run-a-live-webinar/#device-check) asks you to choose your camera, microphone and speakers, then shows:

> **Not able to access selected media device**

and **Continue to Green Room** stays greyed out.

## Why it happens {#why}

The live room needs a working **camera and microphone** before it lets you into the [green room](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/webinars/live-room/green-room/#enter-the-green-room). The button stays greyed out until the room can see both. You can turn them off once you are in, but you can't enter without them.

The message appears when the room can't open the camera or microphone you selected.

## Fix it {#fix}

Work through these in order and check the device preview after each one.

1. **Allow camera and microphone access** for EasyWebinar when your browser asks. If you blocked it earlier, change the site's camera and microphone permission in your browser settings, then reload the page.
2. **Close other apps that are using the camera**, such as another video-call tool, then reload.
3. **Pick the right device** in the device check if you have more than one camera or microphone.

## Verify the fix {#verify}

The device check shows your camera preview and microphone, and **Continue to Green Room** becomes clickable. Nothing in the green room is broadcast; the header reads **Not Live** until you click **Go Live**.

## Related problems {#related-problems}

### "You can only have one event live at a time." {#one-event-live}

This appears on **Enter Room** when another of your webinars is already live, because only [one webinar can be live at a time](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/reference/limits-and-defaults/#webinars-and-scheduling). Join that one from [its Overview tab](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/webinars/setup/overview-tab/#enter-room), or go live with the new one.

## Prevent it next time {#prevent}

Enter the room well before your start time. The green room broadcasts nothing, so you can pass the device check, [finish your checks](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/webinars/live-room/green-room/#final-checks) and test **Share** before anyone is watching. Close other video-call tools before you click **Enter Room**, so nothing else is holding the camera. For the kit itself, see the [webinar equipment guide](https://easywebinar.com/blog/webinar-equipment/) and this [host preparation guide](https://easywebinar.com/blog/how-to-start-webinar-guide/).

## Common questions {#common-questions}

#### Can I enter the room with my camera off? {#faq-camera-off}

Not at first. A camera and microphone are required to enter, even if you turn them off afterwards with the **Camera** and **Mic** controls in the green room.

#### Will attendees see me while I fix my camera? {#faq-attendees-see}

No. Nothing in the green room is broadcast, and the header reads **Not Live** until you click **Go Live**.

#### Can I switch camera or microphone once I'm in? {#faq-switch-device}

Yes. Click **Settings** in the room's top bar; **Device settings** covers camera, audio and recording.

#### My co-host has the same message. What do they do? {#faq-co-host}

The same fixes apply on their computer. [Co-hosts and moderators](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/account/team-members/#presenters-and-moderators) who get in land backstage, not on stage, so your audience doesn't see or hear them until you bring them on. A guest co-host or moderator joins with the [Co-presenter Join Link](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/webinars/registration/sharing-links/#co-presenter-join-link) or the [Moderator Join Link](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/webinars/registration/sharing-links/#moderator-join-link) from the Share dialog.

## Still stuck? {#still-stuck}

Contact EasyWebinar support with the webinar name, the browser you are using and a screenshot of the message. Don't send passwords.

## Next steps {#next-steps}

- [Create and schedule a live webinar](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/webinars/getting-started/create-a-live-webinar/): set up the session you'll be entering the room for.
- [Team members and roles](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/account/team-members/#presenters-and-moderators): who joins as a co-host or moderator, and how they get in.
- [Run a live webinar](https://maximuslabs-ai.github.io/easywebinar-product-docs/easywebinar-product-docs/product-docs/webinars/live-room/run-a-live-webinar/): what happens after the green room, from going live to ending the session.
- [Live webinars on EasyWebinar](https://easywebinar.com/live-webinars/): what the live webinar type is built for.
