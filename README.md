# 🏆 Tactical Analysis: Alexis Mac Allister in the 2022 FIFA World Cup Final

This project focuses on the tactical and performance analysis of **Alexis Mac Allister** in the 2022 FIFA World Cup Final between **Argentina** and **France**. The aim is to dissect his role, positioning, movement, and key contributions in Argentina's historic 3–3 (4–2 pen) victory.

## 🎯 Objective

To provide a data-driven breakdown of:
- Mac Allister’s spatial behavior and role in Argentina’s system.
- His involvement in key attacking transitions and build-up phases.
- How his performance contributed to the team’s structure, press resistance, and offensive execution — especially his pivotal assist to Di María.

## ⚽ Match Context

- 📅 **Date**: December 18, 2022  
- 🏟️ **Fixture**: Argentina vs France – 2022 FIFA World Cup Final  
- ⏱️ **Result**: 3–3 (Argentina wins on penalties)

## 🔍 Analytical Focus

- Ball receptions by zone and direction.
- Progressive passes and carries.
- Positional heatmaps and link-up patterns.
- Key contributions in transition (including his assist on the 2nd goal).
- Defensive work rate and recoveries.

## 📊 Tools & Data

- **Event data**: Provided by [StatsBomb Open Data](https://statsbomb.com/)
- **Accessed with**: [`statsbombpy`](https://github.com/statsbomb/statsbombpy)
- **Visualizations**: matplotlib, seaborn, and custom pitch maps.

## 🧠 Methodology

1. **Data Retrieval**  
   - Used `statsbombpy` to extract event data from the 2022 World Cup Final.
   - Filtered all actions involving Mac Allister (by player ID).

2. **Tactical Mapping**  
   - Created heatmaps of touches, passes received, and pass targets.
   - Identified attacking channels used and defensive recoveries.

3. **Moment Analysis**  
   - Isolated key sequences including the counterattack leading to Di María’s goal.
   - Visualized sequences with arrows, pass networks, and pitch control zones.

4. **Contextual Commentary**  
   - Complemented the data with qualitative tactical notes on Argentina's 4-4-2 defensive structure and 4-3-3 build-up.

## 📈 Sample Visuals

- 🎯 **Heatmap** of Mac Allister’s touches.
- 🔁 **Pass Map** showing links with Messi, Di María, and Álvarez.
- 🛡️ **Defensive recoveries** in the middle third.
