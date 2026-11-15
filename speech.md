# Fire Calendar: speaker script (about 160 seconds, 7 slides)

Press N in the deck to see these notes and a timer.

**Slide 1 · Fire Calendar + team**

Hello, we are Interstellar team: Qanat Aiym, Ibragimov Erik, Liina Abdrakhmanova and Serikov Arsen Kanatovich. Our challenge is Harmonization of MODIS and VIIRS Hot Spots. We built Fire Calendar: one consistent record of fire activity in Kazakhstan, from 2001 to today. Every column you see here is real data: the average yearly detections in a quarter-degree cell.

**Slide 2 · The problem**

The problem: satellites count fires differently. In 2019, VIIRS saw three times more detections than MODIS over the very same country. So you cannot compare 2005 with 2022 using raw counts. A fire increase might just be a new satellite. Calibrating VIIRS by point three brings it onto the MODIS level.

**Slide 3 · The idea**

Our idea is one yardstick. We calibrated every sensor to a MODIS equivalent, using the 174 months in which MODIS and VIIRS both observe the country. Early Terra-only data is multiplied by two, VIIRS by point three. Watch twenty-five years play out: the series stays continuous across every sensor change.

**Slide 4 · How it works**

The pipeline: 3.9 million detections from NASA FIRMS. We keep the reliable ones and mask static heat sources such as gas flares and plants. Everything is counted per quarter-degree cell and month, and merged into one MODIS-equivalent series.

**Slide 5 · The product**

The product is a static web page. Pick an area, and you get a year-by-month calendar of deviation from the multi-year norm. Blue means quieter than usual, red means stronger. Click any month for details, and export CSV or PNG. It works in Russian and English.

**Slide 6 · Validation**

Is it valid? The monthly correlation between MODIS and calibrated VIIRS is 0.98 over 174 months. We are also open about limits: one country-wide coefficient, a detection is not a confirmed fire, and the latest months are near-real-time data that NASA will later replace.

**Slide 7 · What it tells us + who it is for**

Here is what it answers in seconds. October 2026 had seventy percent fewer detections than normal. April is the typical peak. And across the whole record, 2002 was the heaviest year and 2024 the quietest. It serves early-warning and emergency services, scientists, and land managers: anyone who needs to know whether a season is unusual, in their own area. It runs in any browser: no server, no install, open source, in Russian and English. Thank you, we are happy to take your questions.
