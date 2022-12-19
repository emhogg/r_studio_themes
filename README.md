# r_studio_themes

Barbie inspired RStudio themes for all the hyper-femmes out there.

To add these themes to your RStudio, follow the steps outlined below. 

Required packages: 
- rstudioapi: `install.packages("rstudioapi")`
- `library(rstudioapi)`

## Add Barbie Light to RStudio:
- `barbie_light <- "https://raw.githubusercontent.com/emhogg/barbie_r_studio_themes/main/Barbie_Light.rstheme"`
- `rstudioapi::addTheme(barbie_light, apply = TRUE)`

### Barbie Light theme preview
<img width="800" alt="Barbie Light Theme Preview" src="https://user-images.githubusercontent.com/83481390/208359433-27dfa486-e00a-452e-afb5-c5a05cf54807.png">

## Add Barbie Dark to RStudio
- `barbie_dark <- "https://raw.githubusercontent.com/emhogg/barbie_r_studio_themes/main/Barbie_Dark.rstheme"`
- `rstudioapi::addTheme(barbie_dark, apply = TRUE)`

### Barbie Dark theme preview
<img width="800" alt="Barbie Dark" src="https://user-images.githubusercontent.com/83481390/208359464-8482471f-f364-40c2-b793-1685b470fef9.png">

### Troubleshooting

`Error in value[[3L]](cond) : 
  Unable to add the theme file "/var/folders/zp/5hb1l2cn2sxd5p8mq7xs_kdh0000gn/T//Rtmp8cMMrS/Barbie_Light.rstheme". The specified theme, "Barbie Light", already exists in the target location. Please delete the existing theme and try again.`
  
To solve this error, delete the existing Barbie Light and/or Barbie Light from your RStudio in Preferences > Appearence and try again. 

Drop a comment if you have any issues.

P.S. Thanks Jack for your pull request :)
