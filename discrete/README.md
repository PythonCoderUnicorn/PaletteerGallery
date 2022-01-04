# Palettes for Discrete data

```
ggplot(
  mtcars,
  aes(x=mpg,
      y= hp,
      color= factor(cyl))
)+
  geom_point(size= 3)+
  scale_color_paletteer_d("awtools::bpalette")+
  ggdark::dark_mode()
  ```
  
