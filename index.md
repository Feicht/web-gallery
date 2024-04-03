---
layout: default
---
# Auftritte 2023/2024

[![Galerie](./docs/assets/img/folder48.png '25.11.2023 - Kaltenberg')](./docs/2023/kaltenberg-25_11_23.html)
25.11.2023 - Kaltenberg

[![Galerie](./docs/assets/img/folder48.png '03.12.2023 - Jesenwang')](./docs/2023/jesenwang-03_12_23.html)
03.12.2023 - Jesenwang

[![Galerie](./docs/assets/img/folder48.png '08.12.2023 - Pfaffenhofen')](./docs/2023/pfaffenhofen-08_12_23.html)
08.12.2023 - Pfaffenhofen

[![Galerie](./docs/assets/img/folder48.png '10.12.2023 - Krampuslauf München')](./docs/2023/muc-10_12_23.html)
10.12.2023 - Krampuslauf München

[![Galerie](./docs/assets/img/folder48.png '15.12.2023 - Braumanufaktur Olching')](./docs/2023/obm-15_12_23.html)
15.12.2023 - Braumanufaktur Olching

[![Galerie](./docs/assets/img/folder48.png '16.12.2023 - Kaltenberg')](./docs/2023/kaltenberg-16_12_23.html)
16.12.2023 - Kaltenberg

[![Galerie](./docs/assets/img/folder48.png '23.12.2023 - Olching')](./docs/2023/olching-23_12_23.html)
23.12.2023 - Olching

[![Galerie](./docs/assets/img/folder48.png '29.12.2023 - Freising')](./docs/2023/freising-29_12_23.html)
29.12.2023 - Freising

# Auftritte 2022/2023

[![Galerie](./docs/assets/img/folder48.png '26.11.2022 - Kaltenberg')](./docs/2022/kaltenberg-26_11_22.html)
26.11.2022 - Kaltenberg

[![Galerie](./docs/assets/img/folder48.png '03.12.2022 - Kaltenberg')](./docs/2022/kaltenberg-03_12_22.html)
03.12.2022 - Kaltenberg

[![Galerie](./docs/assets/img/folder48.png '03.12.2022 - Mammendorf')](./docs/2022/mammendorf-03_12_22.html)
03.12.2022 - Mammendorf

[![Galerie](./docs/assets/img/folder48.png '09.12.2022 - Braumanufaktur Olching')](./docs/2022/obm-09_12_22.html)
09.12.2022 - Braumanufaktur Olching

[![Galerie](./docs/assets/img/folder48.png '10.12.2022 - Kaltenberg')](./docs/2022/kaltenberg-10_12_22.html)
10.12.2022 - Kaltenberg

[![Galerie](./docs/assets/img/folder48.png '11.12.2022 - Krampuslauf München')](./docs/2022/muc-11_12_22.html)
11.12.2022 - Krampuslauf München

[![Galerie](./docs/assets/img/folder48.png '17.12.2022 - Kaltenberg')](./docs/2022/kaltenberg-17_12_22.html)
17.12.2022 - Kaltenberg

[![Galerie](./docs/assets/img/folder48.png '17.12.2022 - Türkenfeld')](./docs/2022/tuerkenfeld-17_12_22.html)
17.12.2022 - Türkenfeld

[![Galerie](./docs/assets/img/folder48.png '18.12.2022 - Olching')](./docs/2022/olching-18_12_22.html)
18.12.2022 - Olching

[![Galerie](./docs/assets/img/folder48.png '05.01.2023 - Alling')](./docs/2022/alling-05_01_23.html)
05.01.2023 - Alling

[![Galerie](./docs/assets/img/folder48.png '06.01.2023 - Kirchseeon')](./docs/2022/kirchseeon-06_01_23.html)
06.01.2023 - Kirchseeon


<h1>Photo Sets</h1>
<ul>
  {% comment %}
    Get all "photo_set" pages and display a list with links to them.
  {% endcomment %}
  {% assign photo_pages = site.pages | where: "layout", "photo_set" %}
  {% for photo_page in photo_pages %}
    <li>
      <a href="{{ photo_page.url | prepend: site.baseurl }}">{{ photo_page.title }}</a>
    </li>
  {% endfor %}
</ul>