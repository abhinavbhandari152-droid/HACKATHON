# 🎤 Hackathon Pitch Notes

*Keep this open during your presentation to hit all the judging criteria.*

## 1. The Hook (Problem Statement & Relevance - 15 marks)
* "How many of you have had to hunt for a flat in Kathmandu by wandering around reading posters on electric poles?"
* "And once you move in, how hard is it to find a reliable plumber at 8 PM?"
* "GharSathi solves this. We bring property listings, interactive mapping, and verified home services into one platform specifically built for the Kathmandu Valley."

## 2. The Solution (Best Idea - 15 marks)
* "It's not just a housing portal. It's a complete 'settle-in' solution."
* "We map everything. You don't just see a house; you see it on the map alongside our service providers."
* "Plus, we added community events because settling into a new city can be lonely."

## 3. The Tech (Technical Implementation - 35 marks)
* "We built this fully vanilla—HTML, CSS, JavaScript. No heavy frameworks."
* "We integrated **Leaflet.js** for real-time map rendering of listings and providers."
* "We built a client-side state management system using `localStorage`, so users don't lose their saved homes, bookings, or RSVPs if they close the tab."
* "For the demo, we simulated network delays on bookings to show how the async flow would work once we hook up our Node.js backend."

## 4. The Design (UI/UX - 15 marks)
* "We focused on a clean, accessible interface."
* "We added dynamic listing counts, empty states for the dashboard, and toast notifications so the user always gets feedback after an action."
* "It's fully responsive and works beautifully on mobile, which is how 90% of our target audience will use it."

## 5. Q&A Defense (Presentation & QNA - 20 marks)

**Q: "Why didn't you use React/Next.js?"**
**A:** "For a 24/48 hour hackathon, we wanted to guarantee a working prototype with zero build-step overhead. Vanilla JS let us move faster and keeps the app incredibly lightweight for users on slow mobile networks."

**Q: "How will you monetize?"**
**A:** "A freemium model for landlords to list properties, and a small lead-generation commission from service providers when they get booked through our platform."

**Q: "Where is the data coming from right now?"**
**A:** "Currently, it's simulated mock data to demonstrate the front-end flow. Our next step is to connect it to a Firebase or Node backend."
