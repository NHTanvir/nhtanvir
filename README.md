<h1 align="center">
  <a href="https://github.com/NHTanvir">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=3500&pause=800&color=7C3AED&center=true&vCenter=true&width=720&lines=Hi+there%2C+I'm+Naymul+Hasan+Tanvir+%F0%9F%91%8B;Software+Engineer+%7C+WordPress+Specialist;Full-Stack+%26+React+Native+Developer;Building+WP+Pond+%E2%80%94+local+WP+dev+in+Rust;Crafting+products+that+ship+and+scale" alt="Typing SVG" />
  </a>
</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Based_in-Dhaka,_Bangladesh-7C3AED?style=for-the-badge&logo=googlemaps&logoColor=white" />
  <img src="https://img.shields.io/badge/Experience-~5_Years-10B981?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Focus-WordPress_%26_React-3B82F6?style=for-the-badge&logo=wordpress&logoColor=white" />
  <img src="https://komarev.com/ghpvc/?username=NHTanvir&label=Profile%20views&color=7C3AED&style=for-the-badge" alt="Profile views" />
</p>

---

## 💻 About Me

I'm a **Software Engineer** from **Dhaka, Bangladesh 🇧🇩** with nearly **5 years** of hands-on experience shipping scalable web and mobile products. My home base is the **WordPress ecosystem** — where I architect custom plugins, power eCommerce stores, and help move the platform forward for the community that made my career possible.

I care about **clean architecture, thoughtful UX, and code that ages well**. From a bespoke WordPress plugin to a cross-platform React Native app used by real people every day, I enjoy every step of the journey — from first sketch to production rollout. I'm always learning, always iterating, and always hungry for the next meaningful problem to solve.

🔭 **Currently building [WP Pond](https://github.com/NHTanvir/wp-pond)** — a native, non-Docker local WordPress development environment written in Rust.

---

## 🚀 Core Expertise

<table>
  <tr>
    <td width="50%" valign="top">

### 🌟 What I Build
- 🔌 **WordPress plugins at scale** — custom extensions, WooCommerce add-ons, and eCommerce tooling running in production
- 🧩 **Full-stack web engineering** — shipping features end-to-end, from database schema to pixel-perfect UI
- 📱 **Cross-platform mobile** — React Native apps that feel native on iOS and Android
- 🛒 **High-performance eCommerce** — building, optimizing, and scaling online storefronts

    </td>
    <td width="50%" valign="top">

### 🎯 What Drives Me
- 💡 **Always leveling up** — chasing new tech, sharper patterns, better craft
- 🏗️ **Real-world impact** — tools people actually depend on, not toys
- 🌱 **Giving back to WordPress** — code, ideas, and community contributions
- 🤝 **Great teams** — shipping great work, together

    </td>
  </tr>
</table>

---

## 🛠️ Technical Stack

<p align="center">
  <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white" />
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/WordPress-21759B?style=for-the-badge&logo=wordpress&logoColor=white" />
  <img src="https://img.shields.io/badge/WooCommerce-96588A?style=for-the-badge&logo=woocommerce&logoColor=white" />
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white" />
</p>

| Skill | How I Use It |
|-------|--------------|
| **Rust** | Systems work — WP Pond is a 12-crate Rust workspace with a Tauri desktop GUI |
| **PHP** | The backbone of every production-grade WordPress backend I ship |
| **TypeScript** | Typed React/Next.js front ends — see [NextCommerce](https://github.com/NHTanvir/NextCommerce) |
| **React** | Component-driven UIs that stay fast and maintainable over time |
| **React Native** | One codebase, native feel on both iOS and Android |
| **WordPress** | Custom plugins, themes, and occasional ecosystem contributions |
| **JavaScript** | Interactive UIs, async flows, and clean API integrations |
| **WooCommerce** | Deep customization of the world's largest eCommerce platform |
| **Kotlin** | Native Android modules behind React Native bridges |

---

## 📌 Featured Projects

### 🪷 [WP Pond](https://github.com/NHTanvir/wp-pond) — Native Local WordPress Development, in Rust

<p>
  <a href="https://github.com/NHTanvir/wp-pond"><img src="https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/License-MIT-10B981?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white" />
  <img src="https://img.shields.io/badge/Role-Author_%26_Maintainer-7C3AED?style=for-the-badge" />
</p>

My flagship project — a **host-based (non-Docker) local WordPress development tool**, and an open-source
alternative to Local/LocalWP. Built as a **12-crate Rust workspace** with a Tauri 2 desktop GUI.

WP Pond supervises bundled **PHP, MariaDB/MySQL, and nginx/Apache** binaries directly on the host:
no Docker, no VM, no daemons. It routes `*.local` domains through an nginx reverse proxy on ports
80/443, terminates TLS with a locally-trusted CA, and provisions WordPress through WP-CLI. Every site
picks its own **PHP (5.6 → 8.5)**, database engine, and web server — each changeable on an existing
site and downloaded on demand.

Also ships site clone, export/import, blueprints, one-click WP admin login, an Xdebug toggle, Adminer,
and Mailpit mail capture. Targets **Windows** and **Ubuntu/Debian x86_64 (16.04+)**, with the Linux
binary floor verified by executing every bundled binary inside containers of the oldest supported release.

<p>
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" />
  <img src="https://img.shields.io/badge/Tauri-24C8D8?style=flat-square&logo=tauri&logoColor=white" />
  <img src="https://img.shields.io/badge/nginx-009639?style=flat-square&logo=nginx&logoColor=white" />
  <img src="https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white" />
  <img src="https://img.shields.io/badge/WP--CLI-21759B?style=flat-square&logo=wordpress&logoColor=white" />
</p>

<br/>

### 🛍️ [EasyCommerce](https://wordpress.org/plugins/easycommerce/) — AI-Powered WordPress eCommerce Plugin

<p align="center">
  <a href="https://wordpress.org/plugins/easycommerce/">
    <img src="https://ps.w.org/easycommerce/assets/banner-772x250.png" alt="EasyCommerce — AI-Powered WordPress Ecommerce Plugin" width="100%" />
  </a>
</p>

<table>
  <tr>
    <td width="120" align="center" valign="middle">
      <a href="https://wordpress.org/plugins/easycommerce/">
        <img src="https://ps.w.org/easycommerce/assets/icon-128x128.gif" alt="EasyCommerce" width="96" />
      </a>
    </td>
    <td valign="middle">
      <p>
        The first and only <b>AI-powered WordPress eCommerce plugin</b> that automates product content, image generation, and business analytics — all on top of a dedicated database architecture that the plugin reports as <b>3–5× faster</b> than traditional platforms. Built to sell digital products, subscriptions, and physical goods without the bloat of legacy eCommerce stacks.
      </p>
      <p>
        <b>My role:</b> contributor — EasyCommerce is published by the EasyCommerce team, not a personal project of mine. Contributing here has sharpened my craft for architecting <b>scalable, production-grade</b> WordPress solutions that real merchants rely on every day.
      </p>
      <p>
        <a href="https://wordpress.org/plugins/easycommerce/"><img src="https://img.shields.io/badge/WordPress.org-Plugin-21759B?style=for-the-badge&logo=wordpress&logoColor=white" /></a>
        <a href="https://downloads.wordpress.org/plugin/easycommerce.latest-stable.zip"><img src="https://img.shields.io/badge/Download-Latest-10B981?style=for-the-badge&logo=download&logoColor=white" /></a>
        <a href="https://wordpress.org/support/plugin/easycommerce/"><img src="https://img.shields.io/badge/Support-Forum-7C3AED?style=for-the-badge&logo=wordpress&logoColor=white" /></a>
      </p>
      <p>
        <img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white" />
        <img src="https://img.shields.io/badge/WordPress-21759B?style=flat-square&logo=wordpress&logoColor=white" />
        <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
        <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
        <img src="https://img.shields.io/badge/AI_Powered-FF6B6B?style=flat-square&logo=openai&logoColor=white" />
      </p>
    </td>
  </tr>
</table>

<br/>

### 🖼️ [ThumbPress](https://wordpress.org/plugins/image-sizes/) — Image Management Suite for WordPress

<p align="center">
  <a href="https://wordpress.org/plugins/image-sizes/">
    <img src="https://ps.w.org/image-sizes/assets/banner-772x250.png" alt="ThumbPress — Image Management Suite for Performance and Optimization" width="100%" />
  </a>
</p>

<table>
  <tr>
    <td width="120" align="center" valign="middle">
      <a href="https://wordpress.org/plugins/image-sizes/">
        <img src="https://ps.w.org/image-sizes/assets/icon-256x256.png" alt="ThumbPress" width="96" />
      </a>
    </td>
    <td valign="middle">
      <p>
        A complete <b>image management suite</b> trusted by <b>20,000+ WordPress sites</b> to slim down bloated media libraries. ThumbPress disables unused thumbnails, regenerates missing ones, converts JPG/PNG to <b>WebP</b> in bulk, detects unused and oversized images, and sets per-platform social media thumbnails — all from a clean dashboard.
      </p>
      <p>
        <b>My role:</b> contributor — ThumbPress is a <b>Codexpert, Inc.</b> product. Working on it has deepened my understanding of <b>WordPress media internals</b>, <b>Action Scheduler-based background jobs</b>, and shipping performance-critical features to a large install base.
      </p>
      <p>
        <a href="https://wordpress.org/plugins/image-sizes/"><img src="https://img.shields.io/badge/WordPress.org-Plugin-21759B?style=for-the-badge&logo=wordpress&logoColor=white" /></a>
        <a href="https://downloads.wordpress.org/plugin/image-sizes.latest-stable.zip"><img src="https://img.shields.io/badge/Download-Latest-10B981?style=for-the-badge&logo=download&logoColor=white" /></a>
        <a href="https://thumbpress.co/"><img src="https://img.shields.io/badge/ThumbPress-Pro-F59E0B?style=for-the-badge&logo=wordpress&logoColor=white" /></a>
        <img src="https://img.shields.io/badge/Active_Installs-20,000%2B-10B981?style=for-the-badge&logo=wordpress&logoColor=white" />
      </p>
      <p>
        <img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white" />
        <img src="https://img.shields.io/badge/WordPress-21759B?style=flat-square&logo=wordpress&logoColor=white" />
        <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
        <img src="https://img.shields.io/badge/WebP-4285F4?style=flat-square&logo=google&logoColor=white" />
        <img src="https://img.shields.io/badge/Performance-10B981?style=flat-square&logo=speedtest&logoColor=white" />
      </p>
    </td>
  </tr>
</table>

---

## 📊 GitHub in Numbers

<p align="center">
  <img height="180" src="https://github-readme-stats.vercel.app/api?username=NHTanvir&show_icons=true&theme=radical&hide_border=true&bg_color=0D1117&title_color=7C3AED&icon_color=10B981&text_color=E5E7EB&include_all_commits=true" />
  <img height="180" src="https://streak-stats.demolab.com/?user=NHTanvir&theme=radical&hide_border=true&background=0D1117&ring=7C3AED&fire=10B981&currStreakLabel=7C3AED" />
</p>

<p align="center">
  <img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=NHTanvir&layout=compact&theme=radical&hide_border=true&bg_color=0D1117&title_color=7C3AED&text_color=E5E7EB&langs_count=8" />
  <img height="180" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=NHTanvir&theme=radical" />
</p>

### 📈 Contribution Activity

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=NHTanvir&theme=react-dark&bg_color=0D1117&color=7C3AED&line=10B981&point=FFFFFF&hide_border=true&area=true" />
</p>

---

## 🤝 Let's Connect & Build Together

- 💬 **Let's talk shop** — WordPress, React, React Native, or eCommerce: I love a good technical conversation
- 🚀 **Got an ambitious project?** I'm always up for meaningful collaborations
- 📚 **I teach what I know** and learn from everyone I work with
- 🌟 **Open source matters** — let's build things that outlast us

<p align="center">
  <a href="https://github.com/NHTanvir"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/nhtanvir"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://naymul.com"><img src="https://img.shields.io/badge/Website-naymul.com-7C3AED?style=for-the-badge&logo=astro&logoColor=white" /></a>
  <a href="https://facebook.com/NaymulHasanTanvir"><img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" /></a>
  <a href="mailto:naymulhasantanvir10@gmail.com"><img src="https://img.shields.io/badge/Email-Say_Hello-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/Dhaka,_Bangladesh-7C3AED?style=for-the-badge&logo=googlemaps&logoColor=white" />
</p>

<p align="center">
  📬 <a href="mailto:naymulhasantanvir10@gmail.com"><b>Drop me a line</b></a> — always happy to talk shop!
</p>

---

## 💡 Fun Fact

> When I'm not shipping code, you'll find me chasing the latest in tech, tinkering with a new framework, or soaking in Dhaka's vibrant street culture. For me, **every commit is a chance to grow** — both as an engineer and as a human.

---

<p align="center">
  <i><b>"Building the future, one commit at a time."</b></i>  🚀
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=100&section=footer&reversal=true" />
</p>
