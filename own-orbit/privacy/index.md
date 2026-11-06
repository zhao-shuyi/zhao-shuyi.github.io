# Own Orbit Privacy Policy

Last updated: November 6, 2026

Own Orbit is developed and published by Shuyi Zhao ("we", "us", "our"). Own Orbit is an offline-first planner for tasks and calendar, habits, and a Shelf for the movies, TV series and books you're into. Your tasks, habits, Shelf items, cover photos and settings are stored on your device by default. We do not operate an account system for Own Orbit, and we do not run analytics, advertising, tracking, or third-party SDKs in the app.

This policy explains what data Own Orbit handles, where it is stored, and how the app uses Apple services.

## Summary

- We do not collect your Own Orbit data.
- We do not sell your data.
- We do not use your data for advertising, and we do not track you across apps or websites (as defined by Apple's App Tracking Transparency framework).
- We do not use analytics or crash-reporting SDKs.
- Your data stays on your device unless you choose to turn on iCloud Sync.
- Own Orbit reads your device's calendars only to show your events, and only if you allow it. It never changes, stores, or sends your events anywhere.
- Own Orbit makes no network requests of its own, with one exception: if you add a subscribed calendar (a Pro feature), the app downloads that calendar from the web address you entered. Nothing is sent to us.
- The only other outside services involved are Apple's: iCloud (if you enable sync) and the App Store (for purchases).
- Own Orbit's App Store privacy label is "Data Not Collected."

## Data You Enter in the App

Own Orbit lets you create and manage personal planning records, including:

- Tasks — titles, notes, dates, times and time zones, how long they last, repeat rules, reminders, priority, tags, subtasks, and whether each task (or each occurrence of a repeating task) is open, completed, or skipped.
- Lists and folders — names, emojis, and colours.
- Habits — names, emojis, colours, how often they repeat, part of the day, an optional reminder time, and your daily check-ins.
- Shelf items — titles, type, status, progress, score, start and finish dates, creator, where you watched or read it, year, notes, and an optional cover photo — plus your own Shelf types.
- Subscribed calendars (Pro) — the name, colour, and web address of each calendar you add.
- Your preferences, such as the default list for quick add, how long finished tasks stay visible, habit and Shelf defaults, and whether the Habits and Shelf areas are shown.

Some information stays on the device it belongs to and is never synced: which device calendars you show, the downloaded copy of each subscribed calendar, your recent searches, view settings, whether Own Orbit Pro is unlocked (cached), whether iCloud Sync is turned on and when it last synced, and the app's bookkeeping for scheduled reminders.

This data is stored locally on your device using Apple's app storage technologies, in storage shared only between Own Orbit and its own widgets. We do not receive, access, or store this data on our own servers. We do not operate any servers for Own Orbit.

## Calendars

Own Orbit can show the events from your device's calendars (for example iCloud, Google, or Outlook calendars set up in iOS) next to your tasks.

- **Permission.** Own Orbit asks for calendar access the first time you open a calendar view, after a short explanation in the app. It never asks at launch. If you decline, everything except events keeps working, and you can change your answer at any time in iOS Settings.
- **Read only.** Own Orbit reads events to display them on screen, in Today, in search results, and in its widgets. It never creates, edits, or deletes events.
- **Never stored or sent.** Events are read when they are shown. They are not saved in Own Orbit's data, not synced through iCloud, and not sent to us or anyone else.
- You can choose which calendars are shown on each device under **Settings > Calendars**.

## Subscribed Calendars

With Own Orbit Pro you can subscribe to a calendar published on the web (for example a sports season or a school term) by entering its address.

- **What is downloaded.** Own Orbit downloads the calendar file directly from the address you entered, over a secure (HTTPS) connection. It makes one request per calendar and sends no cookies, account details, or identifiers. This is the only network request Own Orbit makes of its own.
- **When.** When you add a calendar (to check it is valid), when the app opens or returns to the foreground (at most every 30 minutes), when you tap **Refresh**, and during iOS background refresh. Own Orbit only refreshes calendars that are shown and only while Pro is active.
- **What the server sees.** As with any web request, the server hosting that calendar receives ordinary technical connection information, such as your IP address, and handles it under its own privacy practices. We do not control those servers.
- **What is kept.** The last good copy of each calendar is kept in a file on your device so it is available offline. That copy is never synced. The calendar's name, colour and address are part of your Own Orbit data, so they sync through your private iCloud if you turn on iCloud Sync.
- Calendar addresses can contain private keys, so Own Orbit never writes them to its logs. Treat a private calendar address like a password.

## Cover Photos

You can add a cover photo to a Shelf item.

- Own Orbit uses Apple's system photo picker. It receives only the photo you select and does not get access to the rest of your library, so it never asks for photo library permission.
- The photo is downscaled and saved inside Own Orbit's own storage as part of the Shelf item. Only the image itself is kept; the photo's metadata, such as where it was taken, is not saved with it.
- Photos are not uploaded anywhere by us. If you turn on iCloud Sync, they sync through your private iCloud along with the rest of your data.
- Own Orbit does not use the camera.

## Reminders and Notifications

- Own Orbit asks for permission to send notifications the first time you set a reminder on a task or habit, never at launch.
- All reminders are scheduled locally on your device by iOS. Their text (a task's title and when it is due, or a habit's name) is created on the device and is not sent to us.
- If you turn on the app icon badge, Own Orbit also schedules silent local notifications around midnight so the badge count is right for the new day.
- Own Orbit does not send push notifications or marketing messages. (If you use iCloud Sync, Apple's silent update notifications tell your devices that new data is waiting; Apple handles these and they carry none of your records.)

## Widgets

Own Orbit's widgets read the same data as the app, directly from its storage on your device, and can show your tasks, events, habits and Shelf items on your Home Screen and Lock Screen. Actions you take in a widget (such as completing a task, checking in a habit, or adding +1 to a Shelf item) are saved straight to that storage. Widgets make no network requests.

Anything shown in a widget is visible to anyone who can see your Home Screen or Lock Screen. Choose your widgets with that in mind.

## iCloud Sync

Own Orbit Pro includes optional iCloud Sync. iCloud Sync is off by default, even after you purchase Pro.

If you turn on iCloud Sync, your Own Orbit data is synced through Apple's iCloud/CloudKit service using your Apple ID and your private iCloud database. The data is stored in your personal iCloud account, not in a shared or public database. We do not operate the iCloud service, and we do not receive or have access to the records synced through your iCloud account. Calendar events, the downloaded copies of subscribed calendars, and the device-only settings described above are never synced.

When you turn sync on, you choose how this device joins your iCloud data:

- **Keep This Device Data** uploads this device's data and merges it with whatever iCloud already holds.
- **Restore Existing iCloud Data** replaces the data on this device with the data in your iCloud account.

Turning sync off stops syncing and keeps the full copy on your device; it does not delete anything from iCloud.

Your use of iCloud is also governed by Apple's applicable iCloud and Apple ID terms and privacy policies.

## Data Reset

Own Orbit does not have an export, import, or backup-file feature, and it does not have a "delete all data" button. It does have two destructive actions in the iCloud Sync screen, each scoped to one place so a single action can't unexpectedly wipe more than you intend:

- **Delete iCloud Data** removes Own Orbit's data from your iCloud account without affecting the data on your device. It is available only while iCloud Sync is turned off, and it works by deleting the app's data directly from your private iCloud database — not by syncing a deletion from your device. This action is irreversible; if you use iCloud Sync on other devices, those devices will lose access to that data once the deletion reaches them.
- **Restore Existing iCloud Data** replaces the data on this device with the data in iCloud.

Before either action, the app saves a safety copy of your data in its own storage on your device as a precaution; the three most recent copies are kept. They are never synced to iCloud or sent to us, are not something you can import or restore from in the app, and are removed when you delete the app.

## Purchases

Own Orbit Pro is purchased through Apple's App Store using StoreKit. Apple processes the purchase and payment information under Apple's own terms and privacy policy. We do not receive your payment card details, name, or Apple ID.

The app reads purchase entitlement information from Apple to unlock or restore Pro features, and checks it again each time the app opens. Apple may provide us aggregated, anonymized statistics about the app (such as download counts, sales reports, and — only if you have opted in to share diagnostics with developers — crash reports), which do not identify you within the app's data.

## Web Links

The About screen links to the Own Orbit User Guide, Support page, Privacy Policy, and Terms of Use, to Own Orbit's App Store review page ("Rate Own Orbit"), and to the App Store pages of the developer's other apps; the Pro screen links to the Terms of Use and Privacy Policy. Links inside a calendar event's details or notes open the address the event contains, and **Open in Calendar** opens Apple's Calendar app. Web pages open in your web browser, not inside the app. As with any website, the host of those pages may receive ordinary technical connection information, such as your IP address, under its own privacy practices. We do not run analytics or tracking on our pages.

## What We Do Not Do

Own Orbit does not:

- Create an Own Orbit account.
- Collect your tasks, habits, check-ins, Shelf items, cover photos, notes, or lists.
- Store, change, or send your calendar events.
- Collect location data.
- Access your contacts, health data, camera, microphone, or the rest of your photo library.
- Send you push notifications or marketing messages.
- Use third-party advertising.
- Use tracking technologies, and it does not track you across other companies' apps and websites.
- Sell, rent, or share your personal data for marketing.

## Data Retention and Deletion

Because we do not collect your Own Orbit records, we do not retain them on our servers, and there is no server-side copy for us to delete.

You can delete your data by deleting individual tasks, lists, folders, habits, Shelf items, subscribed calendars, and other records inside the app; using Delete iCloud Data to remove your Own Orbit data from iCloud; turning off iCloud Sync; deleting Own Orbit's data through Apple's own iCloud storage controls; or deleting the app from your device. Deleting the app removes the data stored on that device (including the safety copies and the downloaded subscribed calendars), but it does **not** remove data already stored in your iCloud account — use Delete iCloud Data first, or Apple's iCloud storage settings, if you want that gone too.

If you enabled iCloud Sync, deletion behavior may depend on Apple's iCloud sync state and your other devices: deleting or editing a record on one synced device can propagate to the others. Delete iCloud Data affects only your iCloud account, and is available only while sync is turned off, specifically to prevent one action from unexpectedly affecting both your device and iCloud.

## Your Privacy Rights

Depending on where you live (for example, the European Union, United Kingdom, or California), you may have legal rights over your personal data, such as the rights to access, correct, delete, or port it, or to object to certain processing.

Because Own Orbit does not collect or store your personal data on our servers, there is no copy of your data that we could access, correct, delete, or export on your behalf. You can exercise full control directly: your records live on your device (and, if you enable iCloud Sync, in your personal iCloud account), and you can view, edit, or delete them at any time using the app and Apple's iCloud controls.

We do not sell or share personal information as defined by the California Consumer Privacy Act (CCPA/CPRA), and we do not process personal data as a controller of your Own Orbit records.

If you have questions about these rights, contact us at the address below. You may also have the right to lodge a complaint with your local data protection authority.

## Children

Own Orbit is not directed to children, and we do not knowingly collect personal information from children. Because the app does not collect personal information from any user, it does not collect personal information from children.

## Changes to This Policy

We may update this Privacy Policy if Own Orbit's features, data practices, or legal requirements change. If we make material changes, we will update the "Last updated" date and make the new policy available through the app or App Store listing.

## Contact

For privacy questions, contact:

`shuyizhao.support@gmail.com`
