# Cheat Sheet For Creating A GitHub Wiki / Documentation

Creating a Wiki page for documentation on GitHub is pretty easy. There's really no coding experience necessary and the best thing is that it's completely free. I was using this markdown code for creating a **[R36S Wiki](https://github.com/manster-zz/R36S-LINKS/wiki)**.

***

## Horizontal line

`***`

***

## Basic text formatting

**Example text** `**Example text**` 

_Example text_ `_Example text_` 

~~Example text~~ `~~Example text~~`

<sub>Example text</sub> `<sub>Example text</sub>` 

<sup>Example text</sup> `<sup>Example text</sup>`

***

## Creating Lists

Example list
* 1
* 2
  * 2.1
  * 2.2

```
Example list
* 1
* 2
  * 2.1
  * 2.2
```

***

## Headlines

# Example headline 1 
`# Example headline 1`

## Example headline 2
`## Example headline 2`

### Example headline 3
`### Example headline 3`

#### Example headline 4
`#### Example headline 4`

***

## Table of Contents list

- [Example headline 1](#example-headline-1)
  * [Example headline 2](#example-headline-2)
    + [Example headline 3](#example-headline-3)
      - [Example headline 4](#example-headline-4)

```
- [Example headline 1](#example-headline-1)

  * [Example headline 2](#example-headline-2)

    + [Example headline 3](#example-headline-3)

      - [Example headline 4](#example-headline-4)
```

***

## Quotes and Infoboxes

> Example quote 

`> Example quote `

> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.

```
> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.
```

***

## Text alignment

<div align="center">centered text</div>

`<div align="center">centered text</div>`

<div align="right">right aligned text</div>

`<div align="right">right aligned text</div>`

***

## Table

| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

```
| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |
```

Use images with the same aspect ratio in tables or it will stretch them which does not look nice.

***

## Table with images

<table>
  <tr>
    <td><a href='https://www.google.com/'><img src="https://www.google.de/images/branding/googlelogo/2x/googlelogo_light_color_272x92dp.png"  width="100" /></a></td>
    <td><a href='https://github.com/'><img src="https://github.githubassets.com/assets/GitHub-Mark-ea2971cee799.png"  width="100" /></a></td>
    <td><a href='https://www.youtube.com/'><img src="https://lh3.googleusercontent.com/DMPqTbcN-R_kPwzF0qg9zZH8UPLtVBoqrDQ_63zhmIq5NUBrllM5Xkj2h7Bi0X_KPzJ6_sTvRFIXWB2HIEeFd2EtnRyUbs0uWTPey3MYtSICaibNBfcA=v0-s1050"  width="100" /></a></td>
    <td><a href='https://discord.com/'><img src="https://cdn.prod.website-files.com/6257adef93867e50d84d30e2/636e0b52aa9e99b832574a53_full_logo_blurple_RGB.png"  width="100" /></a></td>
  </tr>
</table>

```
<table>
  <tr>
    <td><a href=''><img src=""  width="" height="" /></a></td>
    <td><a href=''><img src=""  width="" height="" /></a></td>
    <td><a href=''><img src=""  width="" height="" /></a></td>
    <td><a href=''><img src=""  width="" height="" /></a></td>
  </tr>
</table>
```

***

## Image resizing

<img src="https://lh3.googleusercontent.com/qnaJEbFIpvsWJm2KrRI_GIvz1yZdXntgEsCZxy-1pVZi244bCk1RFwdk0ZBRmmvdHiUl6sIa_tsmskL5WLKiigp2AMsIIxinOJNf39qCmacViRGXIOY"  width="100" height="150" />

[<img src="https://lh3.googleusercontent.com/qnaJEbFIpvsWJm2KrRI_GIvz1yZdXntgEsCZxy-1pVZi244bCk1RFwdk0ZBRmmvdHiUl6sIa_tsmskL5WLKiigp2AMsIIxinOJNf39qCmacViRGXIOY"  width="150" height="150" />]()

[<img src="https://lh3.googleusercontent.com/qnaJEbFIpvsWJm2KrRI_GIvz1yZdXntgEsCZxy-1pVZi244bCk1RFwdk0ZBRmmvdHiUl6sIa_tsmskL5WLKiigp2AMsIIxinOJNf39qCmacViRGXIOY"  width="100"  />]()

```
<img src=""  width="100" height="150" />

[<img src=""  width="150" height="150" />]()

[<img src=""  width="100"  />]()
```

***

## Youtube video link with thumbnail

<a href="https://www.youtube.com/watch?v=TuUFJzYDRwg"><img src="http://img.youtube.com/vi/TuUFJzYDRwg/0.jpg" width="240" height="180" /></a>

`<a href=""><img src="http://img.youtube.com/vi/INSERTYOUTUBEIDHERE/0.jpg" width="240" height="180" /></a>`


***

## Expandable section

<details>
<summary>CLICK HERE TO EXPAND</summary>
Example text
<img src="https://lh3.googleusercontent.com/qnaJEbFIpvsWJm2KrRI_GIvz1yZdXntgEsCZxy-1pVZi244bCk1RFwdk0ZBRmmvdHiUl6sIa_tsmskL5WLKiigp2AMsIIxinOJNf39qCmacViRGXIOY"  width="100"  />
</details>

```
<details>
<summary>CLICK HERE TO EXPAND</summary>
Example text
<img src="https://lh3.googleusercontent.com/qnaJEbFIpvsWJm2KrRI_GIvz1yZdXntgEsCZxy-1pVZi244bCk1RFwdk0ZBRmmvdHiUl6sIa_tsmskL5WLKiigp2AMsIIxinOJNf39qCmacViRGXIOY"  width="100"  />
</details>
```

***

## Example Badges

<a href=''><img src="https://img.shields.io/github/forks/manster-zz/R36S-LINKS?style=flat&logo=github&logoColor=whitesmoke&label=Forks"  /></a>
<a href=''><img src="https://img.shields.io/github/stars/manster-zz/R36S-LINKS?style=flat&logo=github&logoColor=whitesmoke&label=Stars"   /></a>
<a href=''><img src="https://img.shields.io/github/contributors-anon/manster-zz/R36S-LINKS?style=flat&logo=github&logoColor=whitesmoke&label=Contributors"   /></a>
<a href=''><img src="https://img.shields.io/github/watchers/manster-zz/R36S-LINKS?style=flat&logo=github&logoColor=whitesmoke&label=Watchers"   /></a>
<a href=''><img src="https://img.shields.io/github/repo-size/manster-zz/R36S-LINKS?style=flat&logo=github&logoColor=whitesmoke&label=Repo%20Size"   /></a>
[![Discord](https://img.shields.io/discord/741895796315914271.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://discord.gg/retrohandhelds)
![](https://img.shields.io/badge/YouTube-FF0000?style=flat&logo=youtube&logoColor=white)

ArkOS Community Image [![GitHub Release](https://img.shields.io/github/v/release/AeolusUX/ArkOS-R3XS?style=flat)](https://github.com/AeolusUX/ArkOS-R3XS?tab=readme-ov-file#download-links)

AmberELEC [![GitHub Pre-Release](https://img.shields.io/github/release-pre/AmberELEC/AmberELEC-prerelease?style=flat)](https://github.com/AmberELEC/AmberELEC-prerelease/releases/)

ROCKNIX [![GitHub Release](https://img.shields.io/github/v/release/ROCKNIX/distribution?style=flat)](https://github.com/ROCKNIX/distribution/releases)

```
<a href=''><img src="https://img.shields.io/github/forks/manster-zz/R36S-LINKS?style=flat&logo=github&logoColor=whitesmoke&label=Forks"  /></a>
<a href=''><img src="https://img.shields.io/github/stars/manster-zz/R36S-LINKS?style=flat&logo=github&logoColor=whitesmoke&label=Stars"   /></a>
<a href=''><img src="https://img.shields.io/github/contributors-anon/manster-zz/R36S-LINKS?style=flat&logo=github&logoColor=whitesmoke&label=Contributors"   /></a>
<a href=''><img src="https://img.shields.io/github/watchers/manster-zz/R36S-LINKS?style=flat&logo=github&logoColor=whitesmoke&label=Watchers"   /></a>
<a href=''><img src="https://img.shields.io/github/repo-size/manster-zz/R36S-LINKS?style=flat&logo=github&logoColor=whitesmoke&label=Repo%20Size"   /></a>
[![Discord](https://img.shields.io/discord/741895796315914271.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://discord.gg/retrohandhelds)

ArkOS Community Image [![GitHub Release](https://img.shields.io/github/v/release/AeolusUX/ArkOS-R3XS?style=flat)](https://github.com/AeolusUX/ArkOS-R3XS?tab=readme-ov-file#download-links)

AmberELEC [![GitHub Pre-Release](https://img.shields.io/github/release-pre/AmberELEC/AmberELEC-prerelease?style=flat)](https://github.com/AmberELEC/AmberELEC-prerelease/releases/)

ROCKNIX [![GitHub Release](https://img.shields.io/github/v/release/ROCKNIX/distribution?style=flat)](https://github.com/ROCKNIX/distribution/releases)
```

[Hits / Page Views Counter](https://github.com/gjbae1212/hit-counter)

[Shields.io Badges](https://shields.io/badges)

[Badges Generator](https://badgesgenerator.com/)

[Badges for your personal developer branding, profile, and projects](https://github.com/Ileriayo/markdown-badges)

[Lots of dynamic GitHub badge examples](https://github.com/munabedan/BadgeBonanza)

***

## Useful links for Markdown formatting

[Basic writing and formatting syntax - GitHub Docs](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

[Working with advanced formatting - GitHub Docs](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting)

[Create your own info panel, warning box - GitHub Markdown Example](https://gist.github.com/cseeman/8f3bfaec084c5c4259626ddd9e516c61)

[Generate TOC Table of Contents from GitHub Markdown or Wiki Online](https://ecotrust-canada.github.io/markdown-toc/)

[A curated list of awesome GitHub Wikis](https://github.com/MyHoneyBadger/awesome-github-wiki?tab=readme-ov-file#awesome-github-wikis---)

[A curated list of delightful Markdown stuff](https://github.com/BubuAnabelas/awesome-markdown#readme)

***

## More Advanced Wiki / Documentation Creation Tools

[GitHub Pages](https://pages.github.com/)

[GitBook](https://www.gitbook.com/)

[Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) - [example #1](https://rocknix.org/) - [example #2](https://manster-zz.github.io/RK3326/)

[Docusaurus](https://docusaurus.io/) - [example](https://onionui.github.io/)

