# My Professional Blog

[![Netlify Status](https://api.netlify.com/api/v1/badges/67a3c7ef-3ccd-422e-95ed-6aff4dce275c/deploy-status)](https://app.netlify.com/sites/chris-s-friedman/deploys)

This is a blogdown site, built using the wonderful instructions [here](https://bookdown.org/yihui/blogdown/) and hosted on Netlify.

The site is built using Hugo and uses the [tranquilpeak](https://github.com/kakawait/hugo-tranquilpeak-theme) theme.

The most major customization I've performed so far is changing the syntax highlighting. The bundled syntax highlighter doesn't by default highlight R and as an R useR and blogR, that highlighting was kind of important... I achieved that using [Amber Thomas's tutorial](https://amber.rbind.io/2017/11/15/syntaxhighlighting/) on the subject. Note that the one addition required was adding in function names into the highlighter javascript file. 
