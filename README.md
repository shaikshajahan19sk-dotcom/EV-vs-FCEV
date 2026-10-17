# EV vs FCEV Decision Explorer

An interactive seminar prototype that compares battery electric vehicles (BEV) and hydrogen fuel cell electric vehicles (FCEV). Change the assumptions and see how energy use, trip cost, refuelling time and sector suitability respond.

## What it covers

- **Efficiency & cost:** energy drawn from the source and cost per trip, for any distance
- **Refuel vs charge:** time spent per day at 1 to 6 stops
- **Sector fit:** suitability by vehicle sector, with the main factor
- **Roadmap:** 2026–2035 milestones, filterable by BEV, FCEV or both

## Running it

Open `index.html` in any browser. There is no build step and no server. Fonts load from Google Fonts when online and fall back to system fonts otherwise.

## Where the figures come from

- **From the seminar deck:** BEV 75% and FCEV 35% well-to-wheel efficiency; BEV 18–35 min and FCEV 3–5 min per stop; sector suitability; four roadmap milestones (2026, 2028, 2030, 2035).
- **Assumptions (not sourced):** 0.18 kWh/km energy at the wheels and ₹8 per kWh electricity price. Replace before use.
- **Proposed roadmap items:** six additions (2027, 2029, 2031–2034) are illustrative and need a citation before they are presented.

## Limitations

- Cost uses the same electricity price for both vehicles, so it shows the efficiency gap only. Hydrogen pump prices are not modelled.
- Refuelling times cover the stop, not travel.
