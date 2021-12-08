# Paletteer Gallery
my visual color palette gallery for paletteer R pkg

```
ggplot(
  mtcars,
  aes(x=mpg,
      y= hp,
      color= cyl)
)+
  geom_point(size= 3)+
  scale_color_paletteer_c("ggthemes::Blue-Green Sequential")+
  ggdark::dark_mode()+
  labs(title = " ggthemes::Blue-Green Sequential ")
```

# ggthemes
<img height='500' src='https://user-images.githubusercontent.com/55933131/145127319-c8dc7ff1-1d5b-49cf-9040-d27cccf8743d.png'>

<img height='500' src=''>
