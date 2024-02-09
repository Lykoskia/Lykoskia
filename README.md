<h1 align="center">Hi 👋, I'm Alan</h1>
<h3 align="center">A passionate Front end web developer from Croatia</h3>

<p align="left"> <img src="https://komarev.com/ghpvc/?username=lykoskia&label=Profile%20views&color=0e75b6&style=flat" alt="lykoskia" /> </p>

- 📖 I’m currently learning **Advanced React Concepts & Frameworks** (primarily **Next**)
- 🛠️ I'm currently working on projects involving **Headless CMS & custom APIs**
- 📚 I'm interested in learning how to wrap web apps into hybrid/webview Android/iOS apps with **Apache Cordova**
- 💡 I'm curious about **Vue** & **Nuxt** (0 experience)

<h3 align="left">Before the Web:</h3>
<p align="left">
After about a decade of boring and repetitive office work I grew increasingly curious and enamored with automation and scripting. Whether it was reducing time wasted on manipulating/reporting Excel data, or using it to power complex and exciting mail merges, calculators and other applications -- I knew that if I mastered this skill that my productivity would skyrocket, even though I was initially intimidated by code. 
</p>

<h3 align="left">Projects & History:</h3>
<p align="left">
I began my web development journey by studying HTML, CSS, JavaScript and React over the course of 6 months in late 2022, during which time I learned the ropes by building a very simple website, directly manipulating the HTML, CSS and the few scripts (mostly jQuery with a few gimmicks, an API call and not much else) that it contained. Our course eventually led into React, an initially confusing but very satisfying way to write JavaScript. We were required to build a chat application in React to graduate from the course, and mine burned me out for weeks because I barely grasped what I was doing at that point, and the deadline was pretty unforgiving.
</p>
<p align="left">
As summer rolled around I began work on my first big project: the <a href="https://github.com/Lykoskia/react-barcode-generator">Barcode Generator App</a>. The suggestion came from a seasoned developer, and the initial idea was to leverage another API to generate the barcode based on captured form data and then fetch the blob into my app. However, I immediately ran into CORS issues, and after adding most features I thought of over the summer, I decided to learn to generate the barcode myself locally, without any API calls or CORS issues (there was a possibility to host the app somewhere where I would ask the API owner to whitelist the domain, but that still had its flaws).  
</p>
<p align="left">
While working on that, I hit many roadblocks and burned out again after dealing with many complex new challenges (not to mention learning more than I really care to know about the Croatian banking standards...). During the summer, I revisited my old chat app which was hastily assembled and built with a single component, randomized usernames and lacking any real features (not very React-like). It was functional, but I knew I could now do so much more... So, I did. My new <a href="https://github.com/Lykoskia/react-chat">Chat App</a> split the app into multiple components, improved styling, integrated Linkify, reply option, alerts for new messages when the tab is out of focus, and more. When I had something I was happy with (though never really done, and never perfect), I returned to cut my teeth on the Barcode Generator further...
</p>
<p align="left">
I spent most of the (fittingly named) fall fixing, upgrading and polishing these 2 apps, but I was hungry for more. React and CSR inside a root weren't cutting it for me anymore. I started learning about Next.js, immediately fell in love with TailwindCSS after it was recommended to me (I was going to die on the Bootstrap hill, but it was love at first utility class). I came upon the idea of rebuilding that pathetic website I had made, my skills having far outgrown such an abomination. And so I decided to make it into a Next.js app (built with pages router). My initial idea was to host it as a static export (like my other 2 apps) on GitHub Pages, but since I was using internationalization and dynamic imports, that wasn't an option, and so I learned to make it SSG instead. I hit a wall trying to dynamically import variable components based on locale, page and section, but to no avail. Nothing I tried adding to getStaticPaths actually allowed me to compile the build as the dynamic imports had to be explicitly defined literals, without interpolation or any variables. My creative solution had run aground, and I had to resort to a spaghetti code solution listing all the combinations. All 30 of them. At that point I was very glad that I dodged a bullet and didn't have to make a 3rd page (15 more cases) like I thought I would. And so <a href="https://github.com/Lykoskia/next-pages-volker">my first Next.js website</a> was born.
</p>
<p align="left">Meanwhile, I discovered amazing quirks whenever I went back to expand upon the Barcode app. Here's a fun fact: Did you know that React's onChange event is NOT anything like HTML's onchange event? I see. Well I absolutely did NOT spend half a year in blissful ignorance, only to realize after having built the entire app that not only does it behave like a confusingly named oninput, AND it's a feature-not-a-bug <b>intentional, by design, working as intended</b> <i>decision</i>; someone actively and willingly decided to make it function as oninput, but name it onChange, give no equivalent for onchange, implement onInput anyway AND condescendingly write in the documentation that this was on purpose so "developers wouldn't get confused", because when they say onChange, they mean on every god damn change.</p>
<p align="left">I can't stress that enough. It means if you go into an input field, change it, then revert the change, then leave (blur) the field, the onchange event does NOT fire, because the value didn't change. That's expected. However, dealing with React's onChange, **<b><i>every</i> change you made while inside fires the event</b>. It's triggered each time something happens inside the field. Every. Single. Time. So changing it back to what it was before leaving the field doesn't prevent the event from firing (multiple times in fact). This drove me absolutely insane while debugging.</p>
<p align="left">Also, did you know that you can't intercept virtual keyboards (such as on mobile phones) with the onKeyDown event because it's not an actual physical key? Yes, I know it's obvious, which is why I learned about it immediately after attempting everything else because it was the first thing that came to mind after everything else failed.</p>

<p align="left">But all the grievances aside, I feel like the reward for that absolute hell is just as amazing as the learning process was brutal. I ended up building 3 things that I'm very proud of, cutting my teeth on every step of the way, but emerging with a much deeper understanding than 3 years of tutorials had given me. After all, a project is never done, and I will probably come back to all of them to improve upon them in some way with new ideas and features. It's not over when you lose, it's over when you quit. My hundreds of uncompiled builds and failed deployments are a testament of that. Even though I ended up deleting most of the early commits.</p>
  
<h3 align="left">Languages and Tools:</h3>
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=html,css,bootstrap,tailwind,js,react,nextjs,git" />
  </a>
</p>

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=lykoskia&show_icons=true&locale=en" alt="lykoskia" /></p>

<p><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=lykoskia&" alt="lykoskia" /></p>

<h3 align="left">Support:</h3>
<p><a href="https://www.buymeacoffee.com/lykoskia"> <img align="left" src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" height="50" width="210" alt="lykoskia" /></a><a href="https://ko-fi.com/lykoskia"> <img align="left" src="https://cdn.ko-fi.com/cdn/kofi3.png?v=3" height="50" width="210" alt="lykoskia" /></a></p><br><br>
