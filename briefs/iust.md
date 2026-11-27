# Brief: IUST Student App — explore without an account

Read AGENT_BRIEF.md first: its tools, rules and final report files all apply.
Only the mission and the goal change, as below.

## The app

IUST Student App (package com.mussey.iustapp), a companion app for students of
the Islamic University of Science and Technology (Awantipora, Kashmir). It is
meant to show a student their home dashboard, class timetable, attendance,
exam results, university notices, syllabus and settings. This is the real
release build (v2.89) that students install.

## Your goal (replaces the persona goal)

Find today's class timetable and read the latest university notice, going as
far as the app lets you WITHOUT a student account. Then judge the app as your
persona: could a new student figure it out?

## Hard rules for this app

- You do NOT have a student account and must not try to get one. Never guess
  credentials. On the login screen you may try exactly these clearly fake
  values, once each: empty fields; username `testuser` with password
  `wrongpass123`. Judge what the app answers (clear error? spinner forever?
  crash?). Do not use the forgot-password flow with any address.
- If an "update available" or any other dialog appears, screenshot it, note
  what it says, and dismiss it (Later / Not now) — do not update the app.
- Explore every screen reachable without login: all tabs and menus, notices,
  timetable, attendance, results, syllabus, settings, about. Note which
  screens demand login and how the app says so (dead end, polite prompt,
  blank screen, crash).
- If lists need the network, wait for them; if they stay empty or error,
  screenshot that state and report it as an empty/error-state finding.
- Everything else from AGENT_BRIEF.md stands: screenshot after every action,
  about 30 actions of budget, report.md + findings.json in the usual format,
  with your persona's honest score out of 10.
