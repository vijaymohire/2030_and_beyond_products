
# Aarti's Day – QAI Digital Society Simulation

## KPI Summary
| KPI                      |   Baseline |   QAI_DS |   Improvement(Abs) |   Baseline(%) |   QAI_DS(%) |   Improvement(pp) |
|:-------------------------|-----------:|---------:|-------------------:|--------------:|------------:|------------------:|
| Safety Index             |   0.62     |   0.94   |           0.32     |          62   |        94   |              32   |
| Productivity Index       |   0.58     |   1      |           0.42     |          58   |       100   |              42   |
| Service Quality Index    |   0.55     |   1      |           0.45     |          55   |       100   |              45   |
| Low Crime Exposure Index |   0.6      |   0.94   |           0.34     |          60   |        94   |              34   |
| Happiness Index          |   0.644075 |   1      |           0.355925 |          64.4 |       100   |              35.6 |
| Overall Day Score        |   0.596971 |   0.9748 |           0.377829 |          59.7 |        97.5 |              37.8 |

## Narrative Timeline (Baseline vs QAI DS)

### Baseline City
[08:00] Morning Planning
  - What happens: Aarti asks a street robot for the best route and errands planning.
  - Baseline outcome: Checks 2-3 apps; conflicting info; 10 min spent planning.
  - QAI DS outcome:  Robot verifies ID, pulls context, gives optimal route in 30s with errands.
[09:00] Commute incident
  - What happens: Accident near junction causes congestion.
  - Baseline outcome: Stuck 25 extra minutes; emergency response takes ~12 minutes.
  - QAI DS outcome:  Robo Wardens reroute in 2 minutes; robo-med kits arrive in ~5 minutes.
[10:30] Utilities & Scheduling
  - What happens: Workspace utilities and bookings for the day.
  - Baseline outcome: Manual billing checks, two forms, 15 min admin.
  - QAI DS outcome:  Smart contracts auto-schedule and settle; 1 min review.
[13:00] Lunch Payment
  - What happens: Buys lunch at kiosk.
  - Baseline outcome: Card terminal flaky; risk of phishing QR; 7 min delay.
  - QAI DS outcome:  Trusted payment zone via biochip; 30s checkout; fraud-proof.
[14:30] Micro-errand
  - What happens: Picks a book from community library robot.
  - Baseline outcome: Stands in queue; wrong catalog entry; 12 min lost.
  - QAI DS outcome:  VC-based membership; robot fetch in 1 min; correct item.
[18:00] Stray Animal Report
  - What happens: A harmless stray dog roams in the park.
  - Baseline outcome: Not sure whom to call; nothing logged.
  - QAI DS outcome:  Kiosk logs humane pickup; team dispatched; status tracked.
[19:00] Groceries & Transit Home
  - What happens: Quick grocery stop on the way home.
  - Baseline outcome: Confusing offers; checkout line; 15 min delay.
  - QAI DS outcome:  Robot-guided pick; queue smoothing; 3 min checkout.
[21:00] Nightly Briefing
  - What happens: Aarti asks home humanoid for local updates.
  - Baseline outcome: Scrolls multiple sites; doomscroll risk.
  - QAI DS outcome:  Verified community brief; concise; suggests next-day plan.

### QAI Digital Society (Robots-first)
[08:00] Morning Planning
  - What happens: Aarti asks a street robot for the best route and errands planning.
  - Baseline outcome: Checks 2-3 apps; conflicting info; 10 min spent planning.
  - QAI DS outcome:  Robot verifies ID, pulls context, gives optimal route in 30s with errands.
[09:00] Commute incident
  - What happens: Accident near junction causes congestion.
  - Baseline outcome: Stuck 25 extra minutes; emergency response takes ~12 minutes.
  - QAI DS outcome:  Robo Wardens reroute in 2 minutes; robo-med kits arrive in ~5 minutes.
[10:30] Utilities & Scheduling
  - What happens: Workspace utilities and bookings for the day.
  - Baseline outcome: Manual billing checks, two forms, 15 min admin.
  - QAI DS outcome:  Smart contracts auto-schedule and settle; 1 min review.
[13:00] Lunch Payment
  - What happens: Buys lunch at kiosk.
  - Baseline outcome: Card terminal flaky; risk of phishing QR; 7 min delay.
  - QAI DS outcome:  Trusted payment zone via biochip; 30s checkout; fraud-proof.
[14:30] Micro-errand
  - What happens: Picks a book from community library robot.
  - Baseline outcome: Stands in queue; wrong catalog entry; 12 min lost.
  - QAI DS outcome:  VC-based membership; robot fetch in 1 min; correct item.
[18:00] Stray Animal Report
  - What happens: A harmless stray dog roams in the park.
  - Baseline outcome: Not sure whom to call; nothing logged.
  - QAI DS outcome:  Kiosk logs humane pickup; team dispatched; status tracked.
[19:00] Groceries & Transit Home
  - What happens: Quick grocery stop on the way home.
  - Baseline outcome: Confusing offers; checkout line; 15 min delay.
  - QAI DS outcome:  Robot-guided pick; queue smoothing; 3 min checkout.
[21:00] Nightly Briefing
  - What happens: Aarti asks home humanoid for local updates.
  - Baseline outcome: Scrolls multiple sites; doomscroll risk.
  - QAI DS outcome:  Verified community brief; concise; suggests next-day plan.

## Notes
- Indices are normalized 0..100 scales.
- Low Crime Exposure Index is computed as (1 - crime_exposure_proxy).
- Overall Day Score is a weighted blend (Safety 28%, Productivity 24%, Service 20%, Low Crime 14%, Happiness 14%).
- QAI DS improvements stem from verified identity, robots-first service, optimized routing, and trusted payments.
