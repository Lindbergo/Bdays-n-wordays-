# Birthdays & Workday Milestones

A simple web app that shows upcoming **birthday milestones** (20, 30, 40, 50, 60, 70 years) and **workday milestones** (progress to 1 000 employed days) for your employees — pulled live from the Evity HR system.

---

## What you need

- A modern web browser (Chrome, Firefox, Edge, Safari)
- An **Evity API key** (ask your system administrator if you don't have one)

No installation, no server, no extra software required.

---

## How to download

1. Go to the repository page on GitHub.
2. Click the green **Code** button.
3. Select **Download ZIP**.
4. Unzip the downloaded file to any folder on your computer.

---

## How to open the app

1. Open the unzipped folder.
2. Double-click **index.html** — it opens directly in your browser.

> **Tip:** You can also drag and drop `index.html` onto an open browser window.

---

## How to connect to Evity

The first time you open the app, a pop-up will appear asking for your API key.

1. Paste your **Evity API key** into the field.
2. Click **Save & Load Data**.

Your key is saved in your browser — you only need to do this once. To change the key later, click the **⚙ Settings** button in the top-right corner.

---

## How to use the app

### Birthday Milestones tab

Shows employees whose next milestone birthday (20, 30, 40, 50, 60, or 70 years) is coming up.

| Column | What it means |
|---|---|
| Name | Employee name |
| Date of Birth | Their birthday |
| Age Today | How old they are right now |
| Turning | Which milestone age they are reaching |
| Milestone Date | The exact date of the milestone |
| Days Away | How many days until the milestone |

**Filter by time window** — use the **30d / 90d / 1y / All** buttons to narrow down the list.

**Search by name** — type in the search box (top right) to find a specific person.

### Workday Milestones tab

Shows how close each employee is to reaching **1 000 working days**.

| Column | What it means |
|---|---|
| Name | Employee name |
| Days Worked | Total days employed so far |
| Progress to 1 000 | Visual progress bar with percentage |
| Days Remaining | Days left until the milestone |
| Est. Milestone Date | Projected date they will reach 1 000 days |

Employees who have already reached 1 000 days are shown in a separate section at the bottom.

---

## Refreshing the data

Click the **↻ Refresh** button (top right) at any time to reload the latest data from Evity.

---

## Exporting to Excel

Both tabs have a **↓ xlsx** button in the table header. Click it to download the current view as an Excel file.

---

## Troubleshooting

| Problem | Solution |
|---|---|
| "Could not reach the API" error | Check that your API key is correct. Click ⚙ Settings to re-enter it. |
| Blank / loading screen | Check your internet connection and try ↻ Refresh. |
| Data looks outdated | Click ↻ Refresh to pull the latest data from Evity. |
| Pop-up doesn't appear | Scroll to the top of the page — the settings form may be behind the overlay. |
