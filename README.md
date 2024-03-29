









```
r language BS11, echo=FALSE, include=TRUE
source("./R/language.R")
output_type <- knitr::opts_knit$get("rmarkdown.pandoc.to")
```


```
asis sesile serrated adenoma lesion polyp , echo = (language == "TR")
## BS11 - sesile serrated adenoma lesion polyp {#sec-BS11 }
```


```
asis sesile serrated adenoma lesion polyp , echo = (language == "EN")
## BS11 - sesile serrated adenoma lesion polyp {#sec-BS11 }
```






```
r BS11 screenshot HE, eval=TRUE, include=FALSE
if (!file.exists("./screenshots/BS11-HE_screenshot.png")) {
webshot2::webshot(
  url = "https://images.patolojiatlasi.com/BS11/HE.html",
  file = "./screenshots/BS11-HE_screenshot.png"
)
}
```





::::: panel-tabset


### WSI - Link







```
asis, echo = (language == "TR")

**sesile serrated adenoma lesion polyp**


[![Tam Ekran Görmek İçin Resmi Tıklayın](./screenshots/BS11-HE_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS11/HE.html) [Tam Ekran Görmek İçin Resmi Tıklayın](https://images.patolojiatlasi.com/BS11/HE.html)
```

```
asis, echo = (language == "EN")

**sesile serrated adenoma lesion polyp**

[![Click for Full Screen WSI](./screenshots/BS11-HE_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS11/HE.html) [Click for Full Screen WSI](https://images.patolojiatlasi.com/BS11/HE.html)

```





### WSI








```
asis, echo = ((language=="TR") & (output_type=="html"))
Mikroskopik görüntüleri inceleyin:

<iframe src="https://images.patolojiatlasi.com/BS11/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





```
asis, echo = ((language == "EN") & (output_type=="html"))

See Microscopy with viewer:

<iframe src="https://images.patolojiatlasi.com/BS11/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





### Diagnosis


```
asis, echo = (language == "TR")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Tanı için tıklayın

sesile serrated adenoma lesion polyp

:::


```


```
asis, echo = (language == "EN")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Click for Diagnosis

sesile serrated adenoma lesion polyp

:::

```









:::::









