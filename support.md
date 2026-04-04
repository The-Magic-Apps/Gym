# Gym App — Support & User Guide

## Quick Start

### Calendar Tab

Plan and review your workouts across the week or month.

1. Use the **Agenda / Week / Month** segmented control to switch views.
2. In week or month view, tap a day to see its scheduled workouts.
3. Tap **+ Add** to schedule a workout on a specific day.
4. Tap a scheduled workout to start logging it, or tap the **bin icon** to remove it.
5. Coloured dots on each day indicate workout status:
   - **Green** — completed
   - **Amber** — partial (some sets skipped)
   - **Red** — missed
6. Tap **Export** to download a CSV of your complete workout history.
7. Share completed workouts by tapping the **share icon**, or connect **Strava** in Settings to upload them automatically.

### Workouts Tab

Manage your workout sessions and start training.

1. Tap **+ New Workout** to build a new session.
2. Add exercises from your Library — strength exercises, cardio machines, or interval timers.
3. Configure sets — choose from **Standard**, **Pyramid**, **Drop Set**, or **AMRAP**.
4. Tap **Quick Start** on any session to schedule it for today and begin immediately.
5. Tap a session to edit, rename, or delete it.

### Library Tab

Your exercise library — the building blocks for workout sessions.

The Library has three sections — **Strength**, **Cardio**, and **Intervals** — selectable via the segmented control at the top.

#### Strength
Browse 100+ exercises grouped by muscle group (Chest, Back, Shoulders, Arms, Core, Legs, Conditioning). Each exercise can have an animated demo — tap the **download/play icon** to view it. Tap **+ New Exercise** to create a custom exercise.

#### Cardio
Your cardio machines (e.g. treadmill, rowing machine, bike). Each machine is configured with:
- **Rate type** — Pace (min/km) or Speed (km/h)
- **Primary measure** — Duration or Distance
- **Defaults** — pre-fill values when adding to a workout (can be changed per workout)

Calculated values (e.g. distance and speed) are shown automatically based on your inputs. Tap **Quick Start** to begin a cardio session immediately. Tap a machine to edit its name or default values.

#### Intervals
Create and manage custom interval timers.

1. Tap **+ New Interval** to create a timer.
2. Add steps — set each as **Work** or **Rest**, choose a duration, and pick a start sound.
3. Enable countdown options to hear remaining time announced.
4. Tap **Quick Start** on any interval to begin immediately.

### History Tab

Review all completed workouts.

- Each entry shows the workout name, date, duration, and compliance badge (Complete / Partial / Missed).
- Tap a workout to see full details — all exercises, sets, reps, and weights logged.
- Tap **Share** on any workout to share a summary card.
- Tap **Export** to download a CSV of your complete history.

---

## Logging a Workout

1. From **Workouts** or **Calendar**, open a workout to begin logging.
2. For each exercise, enter your **actual reps and weight** (pre-filled with your planned targets).
3. Tap the **circle** on any set to mark it complete or skip it.
4. For cardio exercises, enter your rate and primary measure — calculated values appear automatically.
5. For interval steps, the timer runs automatically through your work and rest periods.
6. Tap **Finish Workout** when done. Your log is saved and — if Strava is connected — uploaded automatically.

---

## Exercise Demos

Many exercises include animated GIF demos from the ExerciseDB library. In the Library tab:

- **Download icon** — the demo hasn't been downloaded yet. Tap to fetch it (~100 KB per exercise).
- **Play icon** — the demo is cached. Tap to view it.
- Tap the GIF in the demo modal to view it fullscreen.
- You can also add a custom video URL (e.g. YouTube) on any exercise via the edit screen.

---

## Settings

### Appearance
Choose between **System** (follows device), **Dark**, or **Light** theme.

### Accessibility
- **Colour-blind mode** — replaces green/red with orange/blue
- **High contrast** — increases text and border contrast
- **Reduce motion** — disables animated transitions

### Voice
Select which voice is used for audio countdown cues. Tap any voice to preview it. Speech rate is set in **iOS Settings → Accessibility → Spoken Content**.

### Units
- **Weight** — kg or lb
- **Distance** — km or miles
- **Date format** — DD/MM/YYYY, MM/DD/YYYY, or YYYY-MM-DD
- **Week starts** — any day of the week

### Subscription
Manage or restore your Gym App subscription.

### Sync
- **iOS:** Workouts sync automatically via iCloud Key-Value Store across all your devices signed in to the same Apple ID. Sync uses your iCloud storage — ensure you have sufficient free space.
- **Android:** Sync via Google Drive — tap to sign in.

### Calendar Sync
Sync scheduled workouts to your device calendar. They appear in a calendar named **"Gym App Workouts"**. Tap to enable — you'll be prompted to allow calendar access.

### Connected Accounts

**Strava** — When connected, completed workouts are automatically uploaded to Strava as Weight Training activities. Your workout summary (exercises, sets, reps, and weights) appears in the activity description. When you first connect, you'll be prompted to upload any existing completed workouts.

- Tap **Connect** to link your Strava account.
- Tap **×** to disconnect.

### Helper Hints
Tap **Reset Helper Hints** to re-enable any welcome screens and helper explanations you previously dismissed.

### Feedback
Tap **Request a Feature or Report a Bug** to submit anonymous feedback. Your submissions are queued locally and sent in the background — you can see their status (Pending / Sent / Failed) in the Recent Submissions list. Failed submissions can be retried.

---

## Tips

- **Supersets:** In the workout editor, link two exercises together so they appear as a superset pair during your session.
- **Muted mode:** Tap the speaker icon when running a session to silence audio cues — haptic feedback still works.
- **Select all on tap:** When editing a number field (reps, weight, duration), tapping it selects all the text so you can type immediately.
- **Editing a workout:** If you rename or modify a workout that is scheduled on future calendar dates, you'll see a warning showing how many future dates will be affected.

---

## iCloud Storage

Gym App uses Apple's iCloud Key-Value Store to sync your data across devices. This uses a small amount of your iCloud storage (typically under 1 MB). If your iCloud storage is full, sync may stop working. You can check your iCloud storage in **iOS Settings → [Your Name] → iCloud → Manage Storage**.

---

## System Requirements

- iOS 16 or later
- iPhone or iPad

---

## Contact & Support

For help, feature requests, or to report a bug:

- Use the **Feedback** feature in Settings (anonymous, no account required)
- Visit [github.com/The-Magic-Apps/Gym](https://github.com/The-Magic-Apps/Gym/issues)
