#HeliosShield
HeliosShield is an advanced space weather monitoring system built to track solar storms from the Sun across the inner solar system. because i was born with melanin deficiency i frequently used to get sun burns whenver i went out. but some days it was more some days it was less. then i came to find out it was because of the solar flares which shoot out more ultraviolet light which is bad for us..

#The problem
The Sun regularly shoots out massive clouds of magnetic plasma called Coronal Mass Ejections. If a large one hits Earth, it can knock out power grids, fry satellites. Most space weather tools only show static charts or alert you after a storm has already arrived. We wanted to fix that. HeliosShield lets you track these storms in real-time while they are flying through space so we know exactly when and where they will hit.

#Architecture
HTML5 Canvas Rendering Engine: Built with Vanilla JavaScript and HTML5 Canvas. It uses dual 2D contexts to render the orbital mechanics radar and the global ionospheric projection,

#Telemetry Pipeline:

NASA DONKI API - Fetches live data on confirmed solar storms, including their initial launch speed, angle, and coordinates.

NOAA SWPC - Pulls real-time solar wind speeds from the DSCOVR satellite to monitor the active activities of sun

#Math Engine:

Calculates the exact real-time orbital positions of Mercury, Venus, Earth, and Mars using true Keplerian orbital mechanics.

Uses the Drag-Based Model to calculate how solar wind creates physical drag on the solar ejections, giving us a highly accurate arrival time instead of just assuming a constant speed.
