# ScheduleWise

A planning prototype that helps Cal Poly students see which degree requirements they still need, check prerequisite order, compare sample course experiences, and build conflict-free schedule options before enrolling.

**This is an unofficial student prototype.** It is not affiliated with or endorsed by Cal Poly. It does not have live enrollment data, degree-audit access, or the ability to enroll anyone.

## What's real and what's sample

- Course codes, titles, units and many BUS prerequisites come from the published Cal Poly 2026-28 catalog (Business Administration, Entrepreneurship concentration, plus GE lists).
- Section times, open seats, ratings, workload labels and student feedback are **placeholder sample data**.
- Standing, GE and concentration rules appear as notes but are not enforced. ITP, STAT, MATH and ECON prerequisites are not loaded.

Always confirm requirements, prerequisites and availability in Cal Poly's official systems (Degree Progress Report, catalog, class schedule) and with an academic advisor.

## Run it

It is a single static file. Open `index.html` in a browser. No build step or server needed.

Completed courses, saved schedules and preferences are stored in your browser's local storage only.

## Use your own course data

Click **Data: Sample** in the header, paste a JSON array (use **Insert template** for the format), and load it. Only use data you have permission to use.

## Deploy on GitHub Pages

1. Settings → Pages
2. Source: Deploy from a branch, Branch: `main`, Folder: `/ (root)`
3. Save, then wait a minute for the site URL to appear
