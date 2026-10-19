# Hill Day meeting tracker

The workbook I used to run congressional meeting requests for the American College of Nurse-Midwives' 2026 Hill Day: about fifty attendees from across the country, each matched to their two senators and their House member, with every scheduler contact, every request, every bounce, every reply, and the final meeting schedule in one place.

This copy is a template with made-up rows. The real one holds attendees' home addresses and personal email addresses and is not something to put on the internet.

## What is in it

`Hill_Day_Meeting_Tracker_Template.xlsx` has eight tabs. The same tabs are in `csv/` for anyone who would rather work in a database or a script.

| Tab | Purpose |
|---|---|
| Hill Day Tracker | One row per attendee: who they are, where they live (which decides which offices they are a constituent of), and for each of their three members of Congress, the scheduler contact and the state of the request |
| Sent via Email | Senate offices take meeting requests by email. One row per office with how many requests went out and whether they delivered |
| Sent via Contact Form | Most House offices only accept requests through a web form. One row per office with the form URL and the constituents named in it |
| Bounced Emails | Which scheduler addresses bounced, how many times, and whether there was a form to fall back on |
| Responses | Every reply, with the staffer's name and role and what they offered |
| Negative Responses | Declines, with the reason, because a decline with "send materials" is still worth a leave-behind |
| Meeting Schedule | Confirmed and pending meetings with time, room, and who is attending |
| Status Overview | The one tab to read the night before: office, status, time, location, and the next action |

## How the process worked

Match each attendee to their offices by home address, not by where they work, because schedulers check. Request Senate meetings by email to the scheduling address on the senator's site, and request House meetings through the office's scheduling form, since House scheduler inboxes are rarely published. Send one request per office that names every constituent attending, rather than one request per attendee, so the scheduler sees a delegation and not a pile of duplicates.

Track bounces separately. Senate scheduling addresses change with staff turnover, and a bounced request that nobody notices is a meeting that never happens. When an address bounces twice, try the firstname_lastname pattern for a named scheduler, then the main office line.

Log every reply the day it arrives, including the declines. A decline that says "schedule fully committed, will review materials" gets a leave-behind packet by email and a note to try the district office during recess.

The Status Overview tab is the deliverable. Attendees do not need the other seven tabs; they need to know where to be, when, and who they are meeting.

## Reuse

Change the column headers that name the organization, drop in your attendee list, and look up scheduler contacts from each member's official site. Official social media handles for every member of the 119th Congress are in my companion repository, `congress-social-media-handles`.

## License

CC0. Use it however you like.
