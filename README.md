<h1 align="center">
  <br>
    <a href="https://www.vuethemes.org/theme/electra">
  <img width=60% src="https://github.com/vuethemes/electra/blob/master/VueThemes.png" alt="Vue Themes"></a> <br>
  Electra
  <br>
</h1>

<h4 align="center">A modern ecommerce site built with Vue.js and Tailwind CSS. We made it easy to start taking action with organized directory structure and component driven development. Optimized and structured for junior devs to look like senior devs.</h4>

<p align="center">
  <a href="https://img.shields.io/badge/">
    <img src="https://img.shields.io/badge/dependencies-up%20to%20date-brightgreen.svg"
         alt="Dependencies">
  </a>
  <a href="https://badgen.net/badge/stars/%E2%98%85%E2%98%85%E2%98%85%E2%98%85%E2%98%85"><img src="https://badgen.net/badge/stars/%E2%98%85%E2%98%85%E2%98%85%E2%98%85%E2%98%85"></a>
  <a href="https://img.shields.io/badge/contributions-welcome-orange.svg">
      <img src="https://img.shields.io/badge/contributions-welcome-orange.svg">
  </a>
</p>

<p align="center">
  <a href="#key-features">Key Features</a> •
  <a href="#how-to-use">How To Use</a> •
  <a href="#download">Download</a> •
  <a href="#structure">Structure</a> •
  <a href="#credits">Credits</a> •
  <a href="#related">Related</a> •
  <a href="#support">Support</a> •
  <a href="#license">License</a> •
  <a href="#contributing">Contributing</a>
</p>

![screenshot](https://github.com/vuethemes/electra/blob/master/electraVueThemes.gif)

## Key Features

* Hot Reload - Make changes, See changes
  - Instantly see what your changes look like in the browser as you create them.
* Update products and manage data in one store.js file
* [TailwindCSS](https://tailwindcss.com) Styling
* Vue Meta plugin for Search Engine Optimization  
* Customizable shopping cart 
* Optimized with clean code and organized structure
* Component driven development 
* One click Vercel/Netlify deployments
* World class support by us! Reach out any time
* Free updates  
  - Get access to the first version today, plus new updates until we're out of ideas.


## ## How To Use

To run this application, you'll need to purchase the theme from [VueThemes](https://vuethemes.org/theme/electra) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
# Go into the repository
$ cd electra-premium-vuethemes

# Install dependencies
$ npm install

# Compiles and hot-reloads for development
$ npm run serve

# Compiles and minifies for production
$ npm run build

# Lints and fixes files
$ npm run lint
```

## Download

You can [download](https://vuethemes.org/theme/electra) the latest installable version of Electra.


## Structure

We've tried our best to develop this theme using a logical component driven structure that is easy to customize. The following section shows the theme files, structure, and plugins.

┣ public/
┃ ┣ favicon.ico
┃ ┗ index.html
┣ src/
┃ ┣ assets/
┃ ┃ ┣ css/
┃ ┃ ┃ ┗ style.css
┃ ┃ ┣ images/
┃ ┃ ┣ videos/
┃ ┣ components/
┃ ┃ ┣ common/
┃ ┃ ┃ ┣ Button.vue
┃ ┃ ┃ ┣ CTA.vue
┃ ┃ ┃ ┣ DoubleTextButton.vue
┃ ┃ ┃ ┣ DrawerNav.vue
┃ ┃ ┃ ┣ FooterSaleBox.vue
┃ ┃ ┃ ┣ HeaderCart.vue
┃ ┃ ┃ ┣ LimitedButton.vue
┃ ┃ ┃ ┣ LogoBlack.vue
┃ ┃ ┃ ┣ LogoWhite.vue
┃ ┃ ┃ ┣ PopupPhone.vue
┃ ┃ ┃ ┣ SectionDownArrow.vue
┃ ┃ ┃ ┣ SidebarCartDrawer.vue
┃ ┃ ┃ ┣ Socials.vue
┃ ┃ ┃ ┣ TextButton.vue
┃ ┃ ┃ ┣ ThemeFooter.vue
┃ ┃ ┃ ┣ ThemeHeader.vue
┃ ┃ ┃ ┗ ZipCodeBox.vue
┃ ┃ ┣ sections/
┃ ┃ ┃ ┣ AboutAccordionItem.vue
┃ ┃ ┃ ┣ CompareKits.vue
┃ ┃ ┃ ┣ CompareKitsItem.vue
┃ ┃ ┃ ┣ ContactForm.vue
┃ ┃ ┃ ┣ FaqAccordion.vue
┃ ┃ ┃ ┣ HeroBanner.vue
┃ ┃ ┃ ┣ HomeKitDetails.vue
┃ ┃ ┃ ┣ HomeKitsDetailsItems.vue
┃ ┃ ┃ ┣ HomeTextMessage.vue
┃ ┃ ┃ ┣ InstagramFeed.vue
┃ ┃ ┃ ┣ OrderAccordionItem.vue
┃ ┃ ┃ ┣ OurFaq.vue
┃ ┃ ┃ ┣ OurKits.vue
┃ ┃ ┃ ┣ OurKitsItems.vue
┃ ┃ ┃ ┣ OurMission.vue
┃ ┃ ┃ ┣ OurStoryExpert.vue
┃ ┃ ┃ ┣ OurStoryHero.vue
┃ ┃ ┃ ┣ OurStoryStars.vue
┃ ┃ ┃ ┣ PartnerAccordionItem.vue
┃ ┃ ┃ ┣ PlpItems.vue
┃ ┃ ┃ ┣ PlpProduct.vue
┃ ┃ ┃ ┣ ProductAccordionItem.vue
┃ ┃ ┃ ┣ TakeQuiz.vue
┃ ┃ ┃ ┗ TextUs.vue
┃ ┃ ┗ sliders/
┃ ┃ ┃ ┣ BragbarSlider.vue
┃ ┃ ┃ ┣ CollectionSlider.vue
┃ ┃ ┃ ┣ FaqContentSlider.vue
┃ ┃ ┃ ┣ FaqSlider.vue
┃ ┃ ┃ ┣ InstagramSlider.vue
┃ ┃ ┃ ┣ OurStorySlider.vue
┃ ┃ ┃ ┗ TestimonialSlider.vue
┃ ┣ pages/
┃ ┃ ┣ Collections.vue
┃ ┃ ┣ Contact.vue
┃ ┃ ┣ Faq.vue
┃ ┃ ┣ Home.vue
┃ ┃ ┣ OurStory.vue
┃ ┃ ┗ ProductSingle.vue
┃ ┣ store/
┃ ┃ ┗ store.js
┃ ┣ App.vue
┃ ┣ main.js
┃ ┗ routes.js
┣ README.md
┣ babel.config.js
┣ package.json
┣ postcss.config.js
┗ tailwind.config.js


## Credits

This software uses the following open source packages:

- [Vue](https://vuejs.org/)
- [npm](https://www.npmjs.com/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Babel](https://babeljs.io/)

## Related

[Vue Themes](https://vuethemes.org/premium-themes) - Vue Themes

## Support

For additional support visit [vuethemes.org](https://vuethemes.org/).

## License

For license information visit [vuethemes.org](https://vuethemes.org/).

## Contributing & Partnerships

If you're interested in contributing or partnering with us, please reach out: [yourfriends@vuethemes.org](mailto:yourfriends@vuethemes.org/)