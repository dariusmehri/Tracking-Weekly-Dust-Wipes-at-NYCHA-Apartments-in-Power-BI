### Tracking Weekly Dust Wipes at NYCHA Apartments in Power BI

Dust wipes are a required environmental test used to detect lead-contaminated dust inside apartments and are part of NYCHA’s compliance with federal lead-safety regulations issued by HUD and the EPA.

A dust wipe test uses a specialized wipe to collect dust from surfaces where lead commonly accumulates, such as floors, window sills, and window troughs. The samples are sent to a certified laboratory to measure lead levels.

NYCHA typically performs dust wipes when a child under six resides in the apartment, lead paint hazards are identified, or lead abatement or repair work has been completed.

A Power BI tool was developed for the Lead Hazard Unit to track dust wipe activity and monitor progress toward NYCHA’s lead-safety compliance goals.

Previously, analytics were performed manually in Excel using downloaded datasets. For this project, the workflow was automated using Python to pull source data directly, process it programmatically, and export it to Power BI for reporting.

The time-series chart below shows the percentage of dust wipes performed, performed or attempted, and not attempted over time.
<br>
<br>

<img width="1251" height="1035" alt="image" src="https://github.com/user-attachments/assets/b4c52362-2cb4-4878-b3a0-07b147400d05" />

<br>
<br>

The summary statistics table below shows the number of work orders issued per week, the number of work orders with a child under six, the number performed and not performed, etc

<br>
<br>

<img width="1239" height="423" alt="image" src="https://github.com/user-attachments/assets/26a3c139-0dd8-42a5-b54c-62923739ab57" />
