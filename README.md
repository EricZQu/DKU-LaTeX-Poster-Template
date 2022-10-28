# Duke Kunshan LaTeX Poster Template

![](demos/demo.jpeg)

This is an unofficial LaTeX poster template for Duke Kunshan University, adapted from [Stanford](https://github.com/RylanSchaeffer/Stanford-LaTeX-Poster-Template). The color palette is taken from the [Brand Identity System for Duke Kunshan University](https://dku-web-admissions.s3.cn-north-1.amazonaws.com.cn/dkumain/wp-content/uploads/mainsite/2022/05/brand-guide-compressed_2021.pdf).

Before using the template, you might need to install the fonts under `fonts\`. Please compile it with XeLaTeX or LuaLaTeX.

There are three color demos under `demos`: DukeBlue, DKUGreen, and White. To change the color, go to `beamerthemeDKU.sty` and change the `headline` color:

- White Text, DukeBlue Banner: `\setbeamercolor{headline}{bg=DukeDarkBlue,fg=white}`
- DukeBlue Text, White Banner: `\setbeamercolor{headline}{bg=white,fg=DukeDarkBlue}`
- White Text, DKU Green Banner: `\setbeamercolor{headline}{bg=DKUGreen,fg=white}`

Open to suggests for other color combinations...
