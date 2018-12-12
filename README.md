# aRgh

What you should know about R to lessen prevent any frustration.

## Gems

### Accessing Private Variables or Functions

Use `:::` in conjuction with a library such as `ggplot2:::`.

### Adding significance manually to ggplot2 plots

```r
geom_signif(annotations = c(formatC("*"),formatC("*")), y_position = c(1.5, 2.5), xmin=c(1, 2), xmax=c(3, 3))
```
