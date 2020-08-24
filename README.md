<h1 align="center">
  <br>
    <a href="https://www.vuethemes.org/theme/electra">
  <img width=60% src="https://github.com/vuethemes/electra/blob/master/VueThemes.png" alt="Vue Themes"></a> <br>
  Electra
  <br>
</h1>

<h4 align="center">Electra is a modern ecommerce site built with Vue.js and Tailwind CSS. ✨ We made it easy to start taking action with organized directory structure and component driven development. Optimized and structured for junior devs to look like senior devs 💯 Have a look at the official Vue Themes website for a comprehensive list of Vue Themes, features, core values and use cases.</h4>

<p align="center">
  <a href="https://img.shields.io/badge/">
    <img src="https://img.shields.io/badge/code-Vue.js-informational?style=flat&logo=<vue-dot-js>&logoColor=white&color=4FC08D"
         alt="Code">
  </a>
   <a href="https://img.shields.io/badge/">
    <img src="https://img.shields.io/badge/styles-TailwindCSS-informational?style=flat&logo=<tailwindcss>&logoColor=white&color=38B2AC"
         alt="Code">
  </a>
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
  <a href="#support">Support</a> •
  <a href="#license">License</a> •
  <a href="#contributing">Contributing</a>
</p>

![screenshot](https://github.com/vuethemes/electra/blob/master/electraVueThemes.gif)


## ✅&nbsp; Key Features

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


## 🚀&nbsp; How To Use

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


## 💻&nbsp; Download

You can [download](https://vuethemes.org/theme/electra) the latest installable version of Electra.


## 🌲&nbsp; Structure

We've tried our best to develop this theme using a logical component driven structure that is easy to customize. The following section shows the theme files, structure, and plugins.

<pre>
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
</pre>


## Credits

This software uses the following open source packages:

- [Vue](https://vuejs.org/)
- [npm](https://www.npmjs.com/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Babel](https://babeljs.io/)


## 📫&nbsp; Have a question? Want to chat? Ran into a problem?

You can reach out to us anytime for support! We are happy to help. [vuethemes.org](https://vuethemes.org/).


## 🤝&nbsp; Found a bug? Missing a specific feature?

Feel free to file a new issue with a respective title and description on the vuethemes/electra repository. If you already found a solution to your problem, we would love to checkout your code! 


## 📘&nbsp; License

You are free to use Electra for your personal or client projects. For more license information visit [vuethemes.org](https://vuethemes.org/).


## ❤️&nbsp; Contributing & Partnerships

Love building with Vue.js? A big part of what makes Vue Themes great is each and every one of you in the community. Your contributions enrich the Vue Themes experience and make it better every day. We welcome all contributions from you in the community, and would be thrilled to amplify your voice. Contributions are not limited to code, and can take all shapes and forms: Your wonderful Vue.js website, starter, UI components, blog posts and anything else you can think of! Please submit your name and submission info ex. GitHub repository/post/content url to [yourfriends@vuethemes.org](mailto:yourfriends@vuethemes.org/) with the subject line: “VUE THEMES SUBMISSION”. Feel free to reach out to us if you have any questions about contributing! 