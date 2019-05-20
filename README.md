# Zika paper Repository
#### Figure 1 Markdown code
[Zika Paper Figure 1 SVG](http://prfw.github.io/Zika/test.svg)

[Zika_Paper_plot_May_15_2019](http://prfw.github.io/Zika/Zika_Paper_plot_May_15_2019.html)




#### Markdown Syntax
[Markdown Syntax](https://guides.github.com/features/mastering-markdown/)


##### Testing
```r
tiff('test.tiff', units="in", width=5, height=5, res=300)       ### Beginning of the code ###

ggplot(data, aes(Condition, Value) )  + 
geom_point(aes(col = Cell.Type)) + 
ylab("Relative ZIKA RNA Copies") + 
ggtitle("Effect of ARB during ZIKA Infection ") + 
theme(plot.title = element_text(hjust = 0.5))           

dev.off()                 ### end the code with this line ###    


```
