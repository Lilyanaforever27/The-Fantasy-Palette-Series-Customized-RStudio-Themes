# The Fantasy Palette Series Customized RStudio Themes
The Fantasy Palette Series is a collection of customized RStudio themes inspired by fantasy, cosmetics, and color palettes. Initiated on June 23, 2026, the series is based on Ben Harrap’s RStudio theme Knitted (&lt;https://benharrap.com/post/two-more-rsthemes/>). Many thanks to Ben!

1. **Lilyana's Daydream (aka Lily's Dream, June 24,2026)**: As the first palette of Lilyana's The Fantasy series, **Lilyana's Daydream (2026)** captures the vibe of *fantasy*,*dreaminess*, *Barbie-inspired glamour*, and celebration of *womanhood*.Built around shades of *pink*, *purple*, *blue*, and *yellow*, this palette provides an alternative pink & purple option that existing R themes are missing. The vibrant color palette is designed to remain gentle on the eyes and provide visual comfort during longer coding sessions.

2. **Kiana's Summer (coming soon in Summer)**: The second palette, Kiana’s Summer, is designed for Lilyana’s friend. It combines different shades of blue to evoke the imagery *beach*, *ocean*, and *calmness*.


# How to apply the RStduio Theme
Option 1: 
a. Click the rstheme file you would like to add from the above
b. Click on "Raw" on the top right of the bar
c. It should load a new page, find the url and copy it. The URL should look like something like: https://raw.githubusercontent.com/Lilyanaforever27/The-Fantasy-Palette-Series-Customized-RStudio-Themes/refs/heads/main/lilyana_daydream.rstheme
d. Open Rstudio and use the code below, add the url
rstudioapi::addTheme(
  "PASTE THE URL YOU COPIED from the last step, don't forget the quotation mark",
  apply = TRUE,
  force = TRUE)
  
Option 2: 
a. Click the r rtheme file and download to Desktop of your laptop (or anywhere you prefer)
b. open R studio, and From the top bar, find "Tools" 
c. Drop down the "Tools" menu, we will find "Global Options" at the end
d. It should pop up a new window, now click "Appearance" from the left column 
e. click "Add" in the middle
f. Find the R theme you downloaded and click on the desktop (or anywhere you saved)
g. The new theme should be in the "Editor Theme" section in the middle column now
h. click "Apply" or "OK"

