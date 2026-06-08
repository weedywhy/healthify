This repo is a demo version of idea and capabilities required in modern times of Healthify.

The backend,logic,etc are not added.

# Healthify

AI-powered meal & health and lifestlye tracker and optimizer. Scan barcodes, snap meals,
chat with a nutrition coach, and track weight/BMI.

## Highlights

- **Barcode scan** via camera 
- **Healthify Score** — AI grades any product 1-10 based on its ingredients;
  works on the OFF data *and* falls back to OCR'ing a photographed ingredient
  list when the barcode isn't in the catalog
- **Photo-to-meal** — snap a plate, your local vision model returns structured items + macros
- **Natural-language log** — "two eggs and toast"
- **Coach** — conversational nutrition guide that knows goals,diseases and allergy.
- **Meditate coach and reminder** - Meditation reminder and step by step guide with categories,audio and streaks.
- **Custom goals** - Allow users to create their own custom goals.
- **Workout guide** - Provide demo videos and workout plans.
- **Weight + BMI + TDEE** - with charted history
- **Water tracking** — daily target, +200/+250/+500 ml taps.
- **Frequent foods** — one-tap re-log from your last 30 days
- **Swipe-to-delete** on meal cards · **Pull-to-refresh** on Today
- **Search OFF by name** — type "greek yogurt" and pick from the live list
- **Editable goals** — tweak kcal/macros/water from the Profile screen
- **Realtime sync** — meals, water, and weight refresh automatically across devices
- **Today's meals are sectioned** by breakfast/lunch/dinner/snacks
- **Daily wellness score** — composite of kcal, protein, water, and food-quality adherence
- **AI weekly insight** — your LLM reads the last 7 days and surfaces a headline, summary, and 1-3 tips
- **History view** — tap any bar in the weekly chart (or "Browse history") to see that day's meals, water, and macro rings
- **Step counter** — live daily steps via `expo-sensors` Pedometer on Today (hidden on devices without motion data)
- **Achievements** — unlockable badges for streaks, scans, photo logs, clean eating, and more
- **Units toggle** — metric or imperial across the app (kg ↔ lb, cm ↔ ft/in, L ↔ cups)
- **Edit any meal** — tap a logged meal to adjust name, portion, macros, or meal type
- **Notes on weight** — annotate weight entries (e.g. "morning", "post-workout")
- **Body measurements** — track waist, chest, hip, bicep, thigh, and body fat % with deltas and a per-metric trend chart
- **AI goal recommender** — Edit Goals can ask the LLM to propose new kcal/macros from your weight trend, then apply with one tap
- **Coach typewriter** — assistant replies type themselves in for a more conversational feel
- **Coach quick replies** — each AI reply ends with 2-3 tappable follow-up prompts
- **Quick add FAB** — floating button on Today expands into Scan / Search / Type shortcuts
- **Wellbeing** — daily mood, energy, sleep hours and quality with note (one tap on Today, full detail on a dedicated screen)
- **Share my day** — one-tap rendered summary card (rings, macros, score, streak) shared via OS share sheet
- **Daily reminders** — toggleable local notifications for breakfast / lunch / dinner / evening recap
- **Activities** — log workouts (run, yoga, strength, custom) with duration, intensity, kcal, notes
- **Coach slash commands** — `/macros`, `/water`, `/score`, `/streak`, `/help` answered locally without an AI round-trip
- **Mood × nutrition AI insight** — the LLM reads up to 14 days of wellbeing + nutrition and surfaces real-world patterns on the Wellbeing screen
- **Monthly calendar** — score-colored grid of every day, jump into a day's detail with one tap
- **Meal templates** — save any logged meal as a reusable template and re-log it in one tap from Log
- **AI workout ideas** — the LLM suggests 3 activities matched to remaining calories, energy, and recent sessions; tap to log
- **Coach sees photos** — attach a meal photo to a Coach message and ask "is this healthy?" / "estimate the calories"
- **Net calories** — Today's totals show calories after subtracting today's activity burn
- **About page** — feature list, stack, data sources, version
- **AI daily plan** — the LLM builds a balanced day (breakfast/lunch/dinner/snack + workout + water tip) you can log one tap at a time
- **Photo gallery** — every photo-logged meal in a tappable grid
- **Today vs yesterday** — at-a-glance % delta on kcal, protein, and water
- **Search history** — find any meal you've ever logged by name
- **Share my week** — Progress can render the last 7 days as a branded PNG and share it
- **Delete account** — privacy-safe full account wipe via a service-role Edge Function
- **Resilient** — root-level error boundary recovers from render failures; skeleton loaders smooth out fetches
- **Daily score breakdown** — tap the score chip to see how calories, protein, water, and food quality contributed
- **Export your data** — one-tap JSON dump shared via the OS share sheet
  
