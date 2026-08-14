# Electrical Calculator

## User guide

How to assess an existing RV energy setup or plan a new one.

**Source document:** `Electrical Calculator_User Manual_2026-08-05_v01.docx`  
**Tool file:** `Electrical calculator_2026-08-03_v05.html`  
**Version:** 05  
**Date:** 5 August 2026  
**Purpose:** Educational RV energy planning

> Important: The calculator is an educational planning aid. It does not replace an electrical installation design, product manual, campsite rules or a qualified installation check.

## Purpose and safe use

Use the calculator to build a transparent daily energy estimate for a specific RV trip. It can check whether an entered battery and inverter setup meets a selected planning target, or suggest a starting battery, solar and inverter capacity for a planned trip.

## Quick start

| Step | Action |
|---|---|
| 1 | Choose whether to check your current setup or plan a new setup. |
| 2 | Set the days between charging or hookup, then choose an energy reserve. |
| 3 | Enter the battery, inverter and solar values that apply to the trip. |
| 4 | Choose the fridge and add every relevant appliance. |
| 5 | Review the setup advice, daily energy picture, appliance chart and campsite section. |

## 1. Tell the tool how you travel

Start with the trip, not the equipment. The selected off-grid period and energy reserve determine the planning target.

| Field | How to use it |
|---|---|
| What do you need help with? | Choose **Check my current setup** if you want an assessment of equipment you already have. Choose **Plan a new setup** if you want a starting recommendation. |
| Days between charging or hookup | Enter the number of days the system should support before a charging opportunity or campsite hookup. The default is 3 days. |
| Energy reserve (%) | Add practical headroom for weather, changing use and normal variation. The default is 20%. A larger reserve increases the recommended capacity. |

## 2. Enter battery, inverter, solar and campsite power

### Battery and inverter

- Enter the battery size in Ah and select Lithium or AGM / lead-acid. The tool sets 95% usable capacity for lithium and 50% for AGM / lead-acid as editable defaults.
- Enter the inverter continuous rating and efficiency. A 230 V appliance selected as **230 V via inverter** counts toward the battery calculation and may create an inverter warning.
- When planning from scratch, enter 0 Ah battery capacity if you do not want to assess an existing battery.

### Solar and campsite connection

- Enter total solar Wp, realistic peak-sun hours per day and a solar yield factor. Solar is a daily recovery estimate, not guaranteed energy.
- Select the campsite hookup limit, 4 A, 6 A, 10 A or 16 A. The campsite section checks each 230 V appliance on its own. Several appliances used together can still exceed the limit.

## 3. Choose the fridge and appliances

### Fridge

Choose the installed fridge model. Compressor fridges use the listed average Ah per 24 hours. For absorption fridges, choose 12 V DC battery, 230 V campsite AC or gas, then enter the expected hours of use. Gas-mode energy is excluded from the electrical total.

### Other appliances

Use a quick-add preset, then adjust its name, power, daily run time and power source to match the actual RV. Add a custom appliance when a preset does not apply.

| Power source | How the calculator treats it |
|---|---|
| 12 V DC battery | Included in off-grid battery use and the appliance chart. |
| 230 V via inverter | Included in off-grid battery use. Inverter efficiency and continuous-rating checks apply. |
| 230 V campsite only | Shown in the campsite section. Excluded from the off-grid battery recommendation. |

> Preset values are editable starting points. Check the appliance rating plate or manufacturer documentation before using them for a real purchase or installation decision.

## 4. Read the result

### Setup advice

In **Check my current setup** mode, green OK markers mean the entered battery or inverter meets the selected planning target. Orange ! markers identify a shortfall. The solar item is a daily-recovery target, not an automatic pass or fail for a finite trip.

| Result | What it means |
|---|---|
| Battery to consider | Usable Ah needed for the selected trip and reserve. The card also shows the nominal lithium or AGM / lead-acid capacity implied by the selected usable-capacity setting. |
| Solar to consider | A daily-recovery target based on entered peak-sun hours and solar yield. It is not used as a guarantee of battery availability. |
| Inverter to consider | The largest selected 230 V inverter load plus a 25% margin. It is not a full cable, fuse or installation design. |
| Daily energy balance | The difference between daily off-grid use and estimated solar recovery. |

### Energy picture

- **Daily battery use** shows all 12 V and inverter-powered loads in Ah per day.
- The pie chart shows how much each off-grid appliance contributes to the daily battery total. Solar and campsite-only loads are not included in the chart.
- **Campsite hookup** lists the individual current demand of each 230 V appliance. Check combined use separately.

## Practical limitations

- The tool uses a fixed 12.5 V reference for battery calculations.
- It does not model battery temperature, battery state of health, wiring losses, appliance cycling, charging while driving or a full installation design.
- Solar output depends on weather, shade, panel angle, temperature and season. Use realistic local assumptions.
- Do not assume that campsite-only appliances such as air conditioning or electric heating can be run off-grid simply by changing their selection. Confirm the full electrical system and installation requirements first.

## Troubleshooting

| If you see this | Check this first |
|---|---|
| No setup recommendation | Choose a fridge or add at least one 12 V or inverter-powered appliance. |
| Battery or inverter shortfall | Check the entered days, reserve, appliance runtime and power source. Then compare the shortfall with the existing setup or increase the planning recommendation. |
| No solar target | Enter realistic peak-sun hours and a solar yield factor. |
| Campsite overload warning | Choose a higher available hookup limit, reduce the appliance load or avoid using high-demand appliances at the same time. |

Use the result to begin the conversation, then verify the real equipment and installation before deciding.
