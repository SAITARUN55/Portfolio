# Personal Website & Portfolio

[![Netlify Status](https://api.netlify.com/api/v1/badges/6850ad60-9b1c-48d1-9a92-565f9aa78700/deploy-status)](https://app.netlify.com/sites/ksaitarun/deploys)

[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg "Built with love")](https://forthebadge.com)

This is the codebase for my personal portfolio!

🚀 **Live:** https://ksaitarun.com

## 🏗 Structure

- Articles: [Source](https://github.com/SAITARUN55/Portfolio/blob/master/_data/articles.yml)
  ```yaml
  - title: "From Developer to Volunteer to Speaker @FOSSASIA"
    url: "https://medium.com/@saitarunkaniganti/from-developer-to-volunteer-to-speaker-fossasia-68e09715cb97"
  ```
  - `img_alt`, `img_url`, `date` and `reading_time` are optional.
  - `title` is used in place of `img_alt`, when required.

- Projects: [Source](https://github.com/SAITARUN55/Portfolio/blob/master/_data/projects.yml)
  ```yaml
  - title: SUSI.AI Android App
    made_for: FOSSASIA
    description: The DevFest Mobile application is for all the GDG Devfests around the world. You can see the agenda in the app as well as the speakers and other updates regarding the devfest. Made with Flutter, entirely by myself.
    img_alt: SUSI.AI Android App
    img_url: /assets/work/susi.png
    img_type_logo: true
    source_url: https://github.com/fossasia/susi_android
    demo_url: https://play.google.com/store/apps/details?id=ai.susi
  ```
  - `source_url` and `demo_url` are optional and do not render if empty.
  - `img_alt` is also optional, instead we use `title` in place of `img_alt`.
  - `img_type_logo` is set to true, a CSS class `.logo` is added to the image. Effect: Reduced width.

- Videos: [Source](https://github.com/SAITARUN55/Portfolio/blob/master/_data/videos.yml)
  ```yaml
  - title: "Flutter Tutorial for Beginners #1 - Scaffold & AppBar Widgets"
    url: "https://www.youtube.com/watch?v=lulwjpEgoJg"
  ```
  - `img_alt` and `img_url` are optional.
  - `title` is used in place of `img_alt`, when required.

## Meta

- Designed by [Ajit Panigrahi](https://ajitpanigrahi.com).
- Uses [Bootstrap 4.5.2](https://getbootstrap.com).
- Icons by [Font Awesome](https://fontawesome.com).
- Built with [Jekyll](https://jekyllrb.com) & [Sass](https://sass-lang.com/).
- Hosted on ~~[GitHub Pages](https://pages.github.com)~~ [Netlify](https://netlify.com)!

**License:** Distributed under the [MIT License](https://opensource.org/licenses/MIT).

See [`LICENSE`](https://github.com/SAITARUN55/Portfolio/blob/master/LICENSE) for more information.
