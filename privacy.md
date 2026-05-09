# One Stop Lawn — Privacy Policy

**Effective Date:** 4 May 2026
**App Version:** v200+
**Owner:** One Stop Lawn, LLC, registered in South Carolina

---

## Summary

One Stop Lawn helps you care for your lawn using AI-powered identification, weather data, soil testing guidance, and journaling. We collect the minimum data needed to make those features work. Your lawn data and photos stay on your device unless you explicitly use a feature that requires sending data to a third party (clearly marked below).

We do not sell your data. We do not use your data for advertising. We do not share your data with anyone except the specific service providers listed below who help us operate the app.

---

## What We Collect

**Information you provide directly:**
- ZIP code (required for weather and growing-zone calculations)
- Grass type, lawn size, and zone names you enter
- Optional address you input into the lawn measuring tool (used only on-device to position the map; we do not store it on our servers)
- Photos you choose to attach to AI features, save to your Lawn Journal, or save to your Wall of Fame
- Soil test data and product application records you enter
- Subscription tier selection and trial activation timestamps

**Information collected automatically:**
- Approximate location coordinates (latitude/longitude derived from your ZIP code) used to fetch weather and soil data from public weather services
- Standard app usage data (which features you use, errors you encounter) only if crash reporting is enabled

**Information we do NOT collect:**
- Your real name (unless you put it in a lawn name)
- Your phone number, email, or contact information (the app does not require an account)
- Your precise device location (we use ZIP-based approximate location only)
- Your contacts, photos other than ones you explicitly attach, calendar, or any other system-level data
- Tracking data across other apps or websites

---

## Photo and Image Handling

When you use a feature that involves a photo (Ask AI image attachment, Field Guide weed/insect/fungus/grass identification, fertilizer label scanning, baseline photos, Wall of Fame photos, or journal entry photos), the following applies:

**Photos sent for AI identification:**
- Resized to 1200 pixels max and JPEG-compressed before transmission
- Sent through our backend proxy (hosted on Vercel) to Anthropic's Claude API
- Used only to generate the AI response you requested
- **Not retained by Anthropic for model training** under their commercial API terms (see https://www.anthropic.com/legal/privacy)
- **Not stored on our servers** — the proxy forwards the request and response without persisting the image
- May appear briefly in our Vercel server logs alongside the request, automatically deleted per Vercel's standard retention

**Photos saved to your device:**
- Lawn Journal photos and Wall of Fame photos are stored only in your browser's local storage on your device
- These photos are not uploaded to any server
- They are deleted when you delete the entry or when you clear the app's local data

**Photo Library and Camera Access:**
- The app may request access to your photo library or camera when you choose to attach a photo
- These permissions are managed by your device's operating system (iOS Settings → Privacy & Security, or Android Settings → Apps → Permissions)
- You can revoke access at any time without losing app functionality — you simply won't be able to attach photos until access is restored
- We do not access your photo library or camera in the background or without your direct action

**EXIF metadata:**
- Photos may contain EXIF metadata such as the date the photo was taken
- We extract only the DateTimeOriginal field to populate the photo's date in your Wall of Fame timeline
- We do not extract or transmit GPS coordinates from your photos
- The full image (with whatever metadata it originally contained) is sent to Anthropic when you use AI identification — Anthropic's privacy practices apply to that transmission

---

## Third-Party Services We Use

We use a small number of third-party services to operate the app. Each is described here with a link to their privacy policy.

| Service | What it does | Data sent | Privacy Policy |
|---|---|---|---|
| **Anthropic (Claude API)** | Powers all AI features: weed/insect/fungus/grass identification, soil test analysis, label scanning, Lawn Genie chat | Photo data and text prompts you submit; ZIP code and grass type for context | https://www.anthropic.com/legal/privacy |
| **Vercel** | Hosts our backend proxy that forwards AI requests to Anthropic | Request payloads pass through; not retained | https://vercel.com/legal/privacy-policy |
| **National Weather Service (NWS)** | Provides forecasts, soil temperature, and rainfall data | Approximate latitude/longitude derived from your ZIP | https://www.weather.gov/disclaimer |
| **Open-Meteo / Zippopotam** | Geocodes ZIP to coordinates if NWS data is unavailable | ZIP code | https://open-meteo.com/en/terms |
| **Rachio** (optional) | Auto-syncs your sprinkler schedule and watering history if you connect your Rachio account | Your Rachio Personal Access Token (you provide it; stored only on your device) | https://rachio.com/privacy |
| **Tally.so** (optional) | Hosts our feedback form (link in Settings) | Whatever you choose to type in the form | https://tally.so/privacy |

We do not use Google Analytics, Facebook Pixel, advertising networks, or any other third-party tracking services.

---

## How We Use Your Data

- **Lawn calculations and recommendations:** Your ZIP, grass type, and lawn size drive seasonal task recommendations, watering schedules, and product suggestions
- **AI features:** Photos and text you submit are used to generate the requested identification or response, then discarded by us
- **Storage on your device:** Journal entries, Wall of Fame photos, soil test history, schedules, and zones are stored locally on your device using browser storage
- **Subscription management:** Your tier selection and trial dates are stored locally and used to gate premium features

We do not use your data for any other purpose. We do not advertise. We do not sell your data.

---

## Data Retention

- **On your device:** All your local data persists until you uninstall the app or clear its local storage
- **In our backend:** We do not store user data on our backend. The proxy forwards AI requests in real time and does not persist them
- **In server logs:** Vercel may keep request logs for up to 30 days for operational purposes; we cannot tie those logs back to a specific user since we do not collect user identifiers

---

## Your Rights

Because we do not maintain accounts or store your data on our servers, most data control happens directly on your device:

- **Access:** Use Settings → Export Data to download a JSON copy of everything stored on your device
- **Deletion:** Delete individual journal entries, photos, or zones from within the app, OR clear all app data via your device settings to erase everything at once
- **Photo permissions:** Revoke camera or photo library access at any time via your device's Settings → Privacy

If you have questions, requests, or complaints about how your data is handled, contact us at onestoplawnfeedback@gmail.com.

---

## Children's Privacy

This app is intended for users 13 years of age and older. We do not knowingly collect data from children under 13. If you believe a child under 13 has used the app, please contact us and we will work to address it.

---

## Changes to This Policy

When we update this policy, we will:
- Update the "Effective Date" at the top
- Notify you via an in-app notice the next time you open the app
- Keep older versions accessible by request

Material changes that affect how your data is handled will be highlighted in the in-app notice.

---

## Contact

One Stop Lawn, LLC
Email: onestoplawnfeedback@gmail.com

For questions about Anthropic's data handling, contact Anthropic directly at https://www.anthropic.com/legal/privacy

---

## Version History

- **v200 (this version):** Added Photo and Image Handling section, EXIF metadata disclosure, and updated third-party services table to reflect current architecture (Anthropic, Vercel proxy, Rachio, Tally.so).
