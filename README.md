Initieel heb ik voor Jekyll als SSG (Static Site Generator) gekozen omdat deze op GitHub Pages ondersteund wordt.
Helaas lijkt de ondersteuning niet zeer goed: geen KaTeX (voor wiskundige formules):

> The page build failed for the `master` branch with the following error:
> 
> The tag `katexmm` on line 9 in `_hst1/lading.md` is not a recognized Liquid tag. For more information, see https://docs.github.com/github/working-with-github-pages/troubleshooting-jekyll-build-errors-for-github-pages-sites#unknown-tag-error.
> 
> For information on troubleshooting Jekyll see:
> 
>   https://docs.github.com/articles/troubleshooting-jekyll-builds

Zelfs als deze tags verwijderd worden (en hier een creatieve oplossing voor zou bedacht worden) bleken ook stijlen niet door te komen.
Genoeg redenen om alternatieven te proberen...

- cloudcannon.com: https://cosmic-skunk.cloudvent.net/
- netlify.com: https://flamboyant-kare-365920.netlify.app/
