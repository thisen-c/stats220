---
title: "Creating images with R"
author: "Thisen Chandrasena"
output: html_document
subtitle: Me trying to figure out if someone waved at me or the person behind me
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo=TRUE, message=FALSE, warning=FALSE, error=FALSE)
```

```{css}
.title {
  text-align: center; /* centers the title */
}

.author {
  text-align: center; /* centres the author */
}

.subtitle {
  text-align: center; /* centres the subtitle */
}

h1 {
  font-family: "Times New Roman", Times, serif; /* set font for header1 */
  color: #000000; /* black */
  
}

h2 {
  font-family: "Times New Roman", Times, serif; /* set font for header2 */
  text-transform: uppercase; /* make headings uppercase */
  margin-bottom: 15px; /* adds space below headings */
  color: #000000;
}

body {
  font-family: "Times New Roman", Times, serif; /* set font for page text */
  font-size: 16px; /* set text size */
  line-height: 1.6; /* increase space between lines */
  color: #000000;
}

img {
  border: 3px solid #73FF79; /* add greed border to imgs */
  border-radius: 10px; /* round image corners */
  margin: 10px 0; /* add space around images */
  max-width: 80%;
  display: block; /* displays images as block elements */
}

```

## Project requirements
Here is a screenshot of my project folder showing the .Rproj and all files used: 

![Project folder screenshot](project_folder_screenshot.png)

### GitHub Repository
You can view my project repository on GitHub here: [stats220-meme-project](https://github.com/thisen-c/stats220-meme-project)

## Inspo meme
### The display of my inspo meme:
![Inspo meme](inspo_meme.jpeg)
There is a cat staring at you intensely; a white text box at the top with black **bold** text: "how toddlers stare at people with visible disabilities".

## My meme
### The display of my meme:
![My meme](my_meme.png)
I found the original photo of the cat without the text and added my own different text, to show that cat image can be used in a different scenario. I also couldn't find the exact font from the original meme so I chose **"Impact"** as my font which was similar.


## My animated meme
![My animated meme](my_meme_animation.gif)

## Creativity
I demonstrated creativity by using the magick functions beyond adding just text. I created a 4 frame animated meme getting inspo from a static meme. I did this by using the image_annotate() and repeated frames to control timing, because I wanted the first frame to display longer so end user has enough time to read all of the text. I have also displayed creativity by the use of **CSS**, I have used new features such as text-aligning, border-colours, border rounding and displaying images as blocks.

## Learning reflection

I found that using functions from the **magick package** was very important, as I would not have been able to accomplish many of the tasks in this project without it. I also think it would be interesting to explore other packages and see how they could enhance this project if I had incorporated them. In addition, I am curious about how to use R programming for more data- or statistics-focused projects. While I did enjoy working on this project, I feel that data or statistics projects would be more interesting to me, as they could also help showcase my skills on my resume. This is especially relevant because I am interested in pursuing a career in the data sector.

## Appendix

<mark>Do not change, edit, or remove the `R` chunk included below.</mark> 

If you are working within RStudio and within your Project1 RStudio project (check the top right-hand corner says "Project1"), then the code from the `meme.R` script will be displayed below.

This code needs to be visible for your project to be marked appropriately, as some of the criteria are based on this code being submitted.


```{r file='meme.R', eval=FALSE, echo=TRUE}

```

