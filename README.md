# William Spriggs | Japanese Portfolio Site

A Japanese portfolio that presents my background, skills and open-source projects, built with plain HTML and CSS and no frameworks or build step.


## Overview

I studied both Japanese language and information technology, and have lived and worked in Japan. This site presents that combination to Japanese employers, in Japanese.

## Sections

| Section | Japanese | Contents |
|---|---|---|
| Top | トップ | Name, title, short introduction, links to GitHub and LinkedIn |
| About | 自己紹介 | Education timeline, experience in Japan, strengths |
| Skills | スキル | Programming languages, tools and fields, language proficiency |
| Projects | プロジェクト | GitHub projects in four categories, each linking to source code |
| Contact | 連絡先 | LinkedIn and GitHub links |

### Project categories

- **ソフトウェア開発 (Software development):** memory-training games, a first-person 3D Pac-Man, a screen recorder and a geocoordinate analytics dashboard
- **スクリプト・Webアプリ (Scripts and web apps):** a desktop emulation page, ciphers, sound and language guessing games, a text to QR to SSTV converter
- **言語学・自然言語処理 (Linguistics and NLP):** Zipf's law analysis, a GloVe word-analogy solver, text statistics, author comparison
- **サイバーセキュリティ・フォレンジック (Cybersecurity and forensics):** a browser hex viewer, email analysis tools, Windows activity and threat monitoring, shutdown log investigation, device and IP scanning

## Tech Stack

- HTML5 (`lang="ja"`)
- CSS3 (`styles.css`): responsive layout with cards, grids and chips
- No JavaScript and no dependencies

## Project Structure

```
.
├── index.html    # page content (Japanese)
├── styles.css    # styling
└── README.md
```


## Customising

- **Text and projects:** edit the cards in `index.html`. Each project is a `.card` block with a title, description and GitHub link.
- **Skills:** add or remove `<span class="chip">` items in the skills section.
- **Appearance:** adjust colours, spacing and layout in `styles.css`.
- **Meta:** update the `<title>` and the footer year as needed.

## Accessibility and Responsiveness

- Mobile-friendly viewport settings, including `viewport-fit=cover` for notched devices
- Wide tables scroll inside their own wrapper so the page never scrolls sideways
- External links use `rel="noopener"`

## Contact

- GitHub: [William2716057](https://github.com/William2716057)
- LinkedIn: [william-spriggs](https://www.linkedin.com/in/william-spriggs-733a56181/)


