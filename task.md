Build a complete event registration web app (single HTML file + optional JS/CSS files) called "Jura Events".

## Goal
A free, hostable static web app on GitHub Pages that lets people:
1. Create events with a title, description, location, and multiple date options
2. Register for events (enter their name + choose date(s))
3. See who registered and for which date
4. Export event to iCal (.ics) or Google Calendar

## Tech Stack
- Pure HTML/CSS/JavaScript (no framework) — must work as static files on GitHub Pages
- Use **localStorage** for storage (no backend needed, simple and free)
- Clean, modern UI with dark theme (like the roadtrip app)

## Features

### Event Creation (Admin)
- Create an event with: title, description, emoji/icon, location, multiple date options
- Each date has: date, time, max participants (optional)
- Events stored in localStorage
- Simple "admin mode" via a secret code (e.g., entering "admin" somewhere)

### Public View
- List all events, each with a card showing title, dates, nb of registrations
- Click event to open detail page
- See list of registered people per date
- Registration form: first name, last name, optional email, choose date(s)
- Confirmation message after registration

### Calendar Export
- "Add to Google Calendar" button for each date
- "Download .ics" button to add to Apple/Outlook calendar

### UI
- Beautiful dark theme (similar to the roadtrip app: #1a1a2e, #2ecc71 accent)
- Mobile-friendly
- French language throughout
- Emoji icons for events
- Show registration count per date with a progress bar (if max set)

## File Structure
- `index.html` — complete app (can be single file with inline CSS/JS)
- `README.md` — instructions

## Important
- Everything must work offline/static (localStorage only, no server calls)
- Mobile-first design
- French UI

When completely finished, run: openclaw system event --text "Done: Jura Events app built" --mode now
