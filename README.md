# Quirekeep

*[Español](README.es.md)*

**[Open the app → quirekeep.pages.dev](https://quirekeep.pages.dev)**

A personal library for the three things you keep track of separately and never
in one place: **books, screen (film and TV) and games**. It runs in the browser,
needs no account and no server, and everything you write stays on your device.

The name is the point: a *quire* is a gathering of folded sheets, the unit a
book is bound from. This keeps yours.

---

## What it does

Each of the three **sectors** is a library of its own, with the same six
screens, and each keeps its own settings, shelves and statistics:

| Screen | What it is for |
|---|---|
| **Library** | Everything in that sector. Filter by status, genre, language, format, shelf or tag; sort; switch between a grid of covers and a list. |
| **Shelves** | Your own shelves. A title can sit on as many as you like. |
| **Stats** | Counts, ratings, what you read, in which languages, and how much of it each connected app knows about. |
| **Sync queue** | The titles a connected service is missing, with their data ready to copy and a link to that service's search. |
| **Import and export** | CSV in, JSON out, backups in and out. |
| **Add** | One form, mostly filled in by searching the title. |

And three screens that are not about one sector:

- **Home** — the three sectors at a glance: what you have started, what comes
  next, and what is released soon. Mark an episode watched or a book finished
  from here.
- **Shelf** — a single shelf across all three sectors: what is in progress, in
  one row per sector.
- **Challenges** — reading, watching and playing challenges: a target ("24
  books in 2026") or a list of prompts you assign titles to. Each one belongs
  to a sector and counts with that sector's titles.

Also: a rating out of ten, per-title progress (pages, minutes, hours, episodes
or a plain percentage), reading history with re-reads, private notes, an
up-next queue of five, light and dark themes, and Spanish and English.

On a phone it grows a bottom bar and you move between screens by swiping
sideways; on a wide screen it is a three-column desktop app.

---

## Getting the app

Quirekeep is not in the App Store or Google Play, and there is no installer to
download. It is a web app: you open one address and tell the browser to keep
it. From then on it sits with your other apps, opens like them, and works with
the phone in flight mode.

> **The address: https://quirekeep.pages.dev**

**On Android** — open the address in Chrome, then the ⋮ menu at the top right
and *Install app* (older versions say *Add to Home screen*). Say yes.

**On iPhone or iPad** — open the address **in Safari**, not in another browser.
Tap the share button (the square with an arrow going up), scroll the list, and
tap *Add to Home Screen*.

**On Windows or Mac** — open the address in Chrome or Edge. At the right-hand
end of the address bar there is a small install icon (a screen with an arrow);
click it, or find *Install Quirekeep* in the browser's ⋮ menu. Firefox does not
install apps: there it works, but it stays a tab.

**If there is no install option**, the browser is usually in a private window.
That alone stops it from offering.

### Once it is installed

- It opens without the browser bars around it, from the icon like any other
  app.
- It works with no connection. Only searching for a new title needs one.
- It updates itself: open it with a connection and you have the latest version.
  There is nothing to reinstall, ever.
- It asks for no account, no email and no permissions.

---

## Your data stays yours

Everything you write lives in your browser's storage, on that device, and
nowhere else. Nothing is sent anywhere, there is no account, and there is
nothing to log into. Nobody has a copy — which is the point, but it also means
nobody can give it back to you.

So, in **Profile**, under the panel that says *Your library only lives in this
browser*, press *Download a backup* now and then; it saves one small file with
everything. That file is what puts it all back on a new phone (*Restore*), or
brings two devices together into one (*Merge*). The app tells you there how
long it has been since the last one.

And avoid clearing your browser's site data for this address: it deletes the
library along with it. The saved copy is the way back.

To bring a library in, **Import** reads CSV exports from Goodreads, StoryGraph,
Pagebound and Letterboxd: ratings, dates, shelves and reviews included.

---

## The accounts you keep elsewhere

Quirekeep does not connect to any of them: no login, no API, no permissions
asked. What it keeps is which of your accounts already has each title, so you
know what is left to upload. Every title carries one coloured band per account
— a strip of spines down the side of it — and tapping a band says "this one is
already there".

It comes with **Booktower, StoryGraph, Pagebound and Goodreads** for books,
**IGN, Backloggd and Steam** for games, and **Letterboxd and Trakt** for film
and TV. Any of them can be switched off or hidden, and you can add your own.

With them on, the **sync queue** lists what each account is missing with the
data ready to copy, the **stats** say how much of a sector each one knows
about, and **export** can write only what a given service lacks. Turn them all
off and nothing breaks: the queue is simply empty.

---

## Where the data comes from

Only sources that need no key and no account: **Open Library** for book search,
ISBN lookup and cover art; **Wikidata** for films, series and games — who made
it, genre, year, length, language, and the cast with the character each one
plays; and **TVMaze** for seasons and episodes with their air dates, which is
what lets the app know an episode has not aired yet.

Film, TV and games have no keyless source of cover art, so they show a coloured
card with the title instead. Where the browser supports it, an ISBN can be
scanned with the camera instead of typed.

---

## Support it

Quirekeep is free, has no ads, no accounts and nothing to unlock. If it earns
its place, you can chip in at **[ko-fi.com/alex_create](https://ko-fi.com/alex_create)**.

---

## Licence

The source code is not published; this repository holds the documentation and
the link to the app. Both the application and these texts are proprietary, all
rights reserved — see [LICENSE](LICENSE).
