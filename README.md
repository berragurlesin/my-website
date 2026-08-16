# My Website!
This project is a personal website I created for myself. It’s a platform where I can bring together my research and other things related to myself. 

-There is a “About Me” page in a scrapbook style. On this page, alongside a scrapbook-style collage I created using images that reflect who I am, there is a text introducing me.
-There are hover animations that cause the images to enlarge slightly and stand out when the cursor hovers over them (using transform + transition)
-There’s an “Essays and Research” page where my personal writings and research will be featured; this page will include my work across various fields.
-There’s a page listing my competition, award, and project history.
-There are links to my other social media platforms

Overall, it’s a personal website that truly reflects who I am!

🛠️Tools I Used:
-HTML5
-CSS3 (Flexbox, free-form layout using `position: absolute`, CSS variables)
-Google Fonts — Caveat (handwritten notes), Inter (body text), Syne (headings)
-Font Awesome — social media icons

📁 Site Structure:
├── index.html       → About Me (homepage, scrapbook collage)
├── essays.html       → Writings / Essays
├── projects.html     → Projects & Milestones
├── socials.html       → Social media links
├── style.css         → Common style sheet for all pages
└── images/           → Photos, stickers, and decorative images

Design Note:
Each image in the collage section is positioned using `position: absolute` at the top, left, and right coordinates within the `.scrapbook-canvas` element—just like pasting a photo into a physical scrapbook. The z-index controls the layering order of the images, while the `:hover` selector makes them enlarge and come to the foreground when the cursor hovers over them.
