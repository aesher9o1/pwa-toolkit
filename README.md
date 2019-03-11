# pwa-toolkit

## Sexy Padha re ho

## Introduction to Progressive Web Applications

Progressive Web Apps are user experiences that have the reach of the web, and are:

1. Reliable - Load instantly and never show the downasaur, even in uncertain network conditions.
2. Fast - Respond quickly to user interactions with silky smooth animations and no janky scrolling.
3. Engaging - Feel like a natural app on the device, with an immersive user experience.
This new level of quality allows Progressive Web Apps to earn a place on the user's home screen.

*Source https://developers.google.com/web/progressive-web-apps/*

## How to use the code

1. Modify the meta tags in the *index.html*. This would help in SEO and also show up when you share the website.
```html
    <meta name="Description" content="Manipal University Jaipur is back with its sixth edition of MUN conference on 9th -10th February 2019. MUJMUN has been one of the biggest, most engaging conferences in the Rajasthan circuit. With over 2000+ delegates hosted through the years, we don’t plan on slowing down. In this edition to take the level of the conference even higher, we have six committees UNGA-DISEC, UNHRC, UNSC, ECOSOC, Futuristic NATO, AIPPM along with International Press. The agendas to be discussed are relevant and demand immediate attention, both by conscious citizens and world leaders. I
    Looking forward to your presence in February.">
    <meta name="Keywords" content="MUJ MUN, International">
    <meta name="author" content="team9o1">
```
2. Replace the icons in the *fab folder* with the appropriate icon. The icons can be generated from https://www.pwabuilder.com/imageGenerator
3. Fill up the appropriate details in the *manifest.json*.
4. Fill in the URL of the pages to be cached in the *9o1.sw*
```javascript
const PRECACHE_URLS = [
  'index.html'
];
```

## Enable PWA desktop
1. Search for chrome://flags/ 
2. Enable *App Banners* or visit chrome://flags/#enable-app-banners
3. You are ready to go ❤❤❤❤ 

