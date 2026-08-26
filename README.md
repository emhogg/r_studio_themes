# Barbie RStudio Themes 🌸

Barbie-inspired RStudio themes for all the hyper-femmes out there.

To add these themes to your RStudio, follow the steps outlined below. 

Required packages: 
- rstudioapi: `install.packages("rstudioapi")`
- `library(rstudioapi)`

## Add Barbie Light to RStudio:
- `barbie_light <- "https://raw.githubusercontent.com/emhogg/r_studio_themes/main/Barbie_Light.rstheme"`
- `rstudioapi::addTheme(barbie_light, apply = TRUE)`

### Barbie Light theme preview
<img width="800" alt="Barbie Light Theme Preview" src="https://user-images.githubusercontent.com/83481390/208359433-27dfa486-e00a-452e-afb5-c5a05cf54807.png">

## Add Barbie Dark (v2.0) to RStudio
- `barbie_dark <- "https://raw.githubusercontent.com/emhogg/r_studio_themes/main/Barbie_Dark_v2.rstheme"`
- `rstudioapi::addTheme(barbie_dark, apply = TRUE)`

### Barbie Dark v2.0 preview
<img width="892" height="878" alt="Barbie_Dark_v2" src="https://github.com/user-attachments/assets/7fec264d-0e18-4a33-a5fe-54d2f2524229" />


### Troubleshooting

`Error in value[[3L]](cond) : 
  Unable to add the theme file ".../Barbie_Light.rstheme". The specified theme, "Barbie Light", already exists in the target location. Please delete the existing theme and try again.`

To resolve this error, delete the existing Barbie Light and/or Barbie Light from your RStudio in Preferences > Appearance and try again. 

Drop a comment if you have any issues.
