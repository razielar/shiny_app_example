# Shiny app example

### Based from this tutorial: [tutorial](https://www.bjoern-bos.de/post/learn-how-to-dockerize-a-shinyapp-in-7-steps/)


## 1) Fist download the docker image:

```{r}

docker pull razielar/my_shinyapp_example     

```

## 2) Run the app:

```{r}

docker run -p 80:80 -d  razielar/my_shinyapp_example     

```
