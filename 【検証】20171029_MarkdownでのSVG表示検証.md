# 概要
SVGファイルの埋め込みリンクがMarkdownのimg記法だとリンクされなかった為、リンクされる方法を検証

# 検証

様々な書き方でSVGファイルに埋め込まれているxlinkが使える記載方法を検証

![testsvg](img/test2.svg?sanitize=true)

[testjpg](img/test.jpg)

![testhtml](img/test3.html)

[testpdf](img/test.pdf)

![testsvg2](https://git-sk.github.io/top/img/test2.svg?sanitize=true)

<svg>
<img src="https://git-sk.github.io/top/img/test2.svg?sanitize=true" />
</svg>

<code>
<img src="img/test2.svg?sanitize=true" />
</code>

<!DOCTYPE svg PUBLIC "-//W3C//DTD SVG 1.1//EN" "http://www.w3.org/Graphics/SVG/1.1/DTD/svg11.dtd">
<svg xmlns="http://www.w3.org/2000/svg" style="background-color: rgb(255, 255, 255);" xmlns:xlink="http://www.w3.org/1999/xlink" width="306px" height="56px" version="1.1" content="&lt;mxfile userAgent=&quot;Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:56.0) Gecko/20100101 Firefox/56.0&quot; version=&quot;7.6.5&quot; editor=&quot;www.draw.io&quot; type=&quot;device&quot;&gt;&lt;diagram id=&quot;8cca7890-f0fc-1f5b-9cd8-c10410771984&quot; name=&quot;Page-1&quot;&gt;5VZLj9owEP41uaJgk0KPhWXbw1ZdaVX1WJlkcLw4mcgZXv31tbHzIlC11Z5aOOD5PA/7+2YSIr4qTh+NqPLPmIGOWJydIv4QMTad8dj+OOTskTmbekAalQWnDnhRPyCAIU7uVQb1wJEQNalqCKZYlpDSABPG4HHotkU9rFoJCSPgJRV6jH5TGeUeXbB5h38CJfOm8vTde7+zEelOGtyXoV7E+Pby8duFaHKFi9a5yPDYg/g64iuDSH5VnFagHbcNbT7u8c5ue24DJf1OQLhQTefm6pBZJoKJhnKUWAq97tDl5XrgEsTWyqnQdjm1y1cgOgcxxZ7QQl2GJ8Qq+PmartDdUweoxr1Jgxdr6bFtB1gAmbN1MaAFqcMwlQj6y9avDX1GZYuwOPQqS4ISoVN5HA9TkDASKER1TNpF7xgddOH3NtfMJz4IvYemO67Ib9vBMZuJOr9Fc00Gd7BCjcYiJZZOlK3SuoFs0yWx+1pciw3oZ6wVKSztXmopBuu0PIAhZTv+6cphg0RY9Bw+aCXdBjn9lvaElTtscZJu9Ce43aoUJnYQU6ionoiq0jbKJfsuoQSj0lZxlxFOv9Z8LHATMB0KxRbBPnYDmnAP5b3ZnMX3W2IgZqfc1xrMl82re7Cw+EJgXy6tyl1jPxLUvi1alXnvFqEB/i2BTZpfxu0tRL2ePjbnI1F5MhY1Sf5YVGv2dL09obP/YUI3oswCvW8hIZ9fS7gYSTi7IeHsryTs3oz+Adz9/eDrnw==&lt;/diagram&gt;&lt;/mxfile&gt;"><defs/><g transform="translate(0.5,0.5)"><path d="M 53 27 L 133.63 27" fill="none" stroke="#000000" stroke-miterlimit="10" pointer-events="none"/><path d="M 138.88 27 L 131.88 30.5 L 133.63 27 L 131.88 23.5 Z" fill="#000000" stroke="#000000" stroke-miterlimit="10" pointer-events="none"/><path d="M 39.57 11.45 L 41.8 11.45 L 41.8 9.24 L 39.57 9.24 Z M 44.04 11.45 L 46.28 11.45 L 46.28 9.24 L 44.04 9.24 Z M 48.52 11.45 L 50.76 11.45 L 50.76 9.24 L 48.52 9.24 Z M 49.99 44.77 C 50.56 44.77 50.76 44.39 50.76 44.01 L 50.76 14.42 L 2.24 14.42 L 2.24 43.96 C 2.25 44.38 2.4 44.71 2.97 44.77 Z M 0 44.05 L 0 9.81 C 0 8.58 1.09 7 3.14 7 L 49.95 7 C 51.69 7 53 8.37 53 9.91 L 53 43.95 C 53 45.43 51.92 47 49.95 47 L 2.9 46.99 C 1.34 46.99 0 45.63 0 44.05 Z" fill="#505050" stroke="none" pointer-events="none"/><a xlink:href="/test"><path d="M 153.7 39.93 L 161.3 39.93 L 161.3 36.16 L 153.7 36.16 Z M 145.33 49.72 L 145.33 31.64 L 169.67 31.64 L 169.67 49.72 Z M 153.69 13.56 L 161.3 13.56 L 161.3 9.79 L 153.7 9.79 Z M 145.33 23.35 L 145.33 5.27 L 169.67 5.27 L 169.67 23.35 Z M 143.04 25.62 L 171.96 25.62 L 171.96 3 L 143.04 3 Z M 143.04 51.99 L 171.96 51.99 L 171.96 29.38 L 143.04 29.38 Z M 140 55 L 140 0 L 175 0 L 175 55 Z" fill="#505050" stroke="none"/></a><path d="M 285.89 27.72 C 285.83 29.4 284.49 30.94 282.52 30.94 C 280.37 30.87 279.2 29.17 279.2 27.55 C 279.26 25.1 281.29 24.21 282.44 24.2 L 290.41 19.24 C 290.5 19.2 290.59 19.2 290.7 19.29 C 290.79 19.38 290.82 19.48 290.78 19.58 Z M 277.26 39.49 L 277.26 36.49 L 287.75 36.49 L 287.75 39.49 Z M 301.93 28.99 L 295.7 28.99 C 295.8 28.31 295.81 26.81 295.7 26.01 L 301.94 26.01 C 301.58 22.07 300.29 18.29 297.25 14.78 L 292.85 19.17 C 292.23 18.42 291.54 17.71 290.75 17.08 L 295.14 12.71 C 292.19 10.08 288.13 8.4 284 8.06 L 284 14.3 C 283.38 14.2 281.74 14.18 281 14.3 L 281 8.06 C 276.38 8.41 272.86 10.21 269.87 12.68 L 274.25 17.08 C 273.54 17.71 272.52 18.7 272.16 19.18 L 267.76 14.78 C 264.24 18.96 263.34 22.78 263.06 26.01 L 269.3 26.01 C 269.16 26.92 269.24 27.99 269.3 28.99 L 263.06 28.99 C 263.76 38.28 271.56 47 282.76 47 C 293.17 47 301.33 38.4 301.93 28.99 Z M 282.58 50 C 271.76 50 260 41.37 260 27.57 C 260 14.69 270.31 5 282.71 5 C 294.83 5 305 15.04 305 27.29 C 305 40.01 294.97 50 282.58 50 Z" fill="#505050" stroke="none"/></g></svg>

<div style="width:32px; height:32px; background-image:url(img/test2.svg); background-size:100%;"></div>

<a xlink:href="http://google.com" target="_blank">
  <object type="image/svg+xml" data="img/test2.svg" width="100%" height="100%"></object>
</a>

<svg width="320" height="80" viewBox="10 90 320 80">
  <use xlink:href="img/test2.svg" />
</svg>

<object type="text/html" data="img/test2.svg"></object>

<embed type="image/svg+xml" src="img/test2.svg" height="400" width="400"/>

<input type="image" src="img/test2.svg" height="400" width="400"/>

<iframe src="img/test2.svg" height="400" width="400" style="border:none;"></iframe>


# 参考

[MarkdownファイルでのSVG読み込み方法](https://stackoverflow.com/questions/13808020/include-an-svg-hosted-on-github-in-markdown)

[HTML5でのSVG指定](https://qiita.com/ka215/items/f9834dca40bb3d7e9c8b)
