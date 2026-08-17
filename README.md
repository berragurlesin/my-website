# My Website!

This project is a personal website I created for myself. It’s a platform where I can bring together my research and other things related to myself. 

## 💫**Features:**

-An “About Me” page in a scrapbook style. On this page, alongside a collage I created using images that reflect who I am,there is a text introducing me.

-An “Essays and Research” page where my personal writings and research will be featured, covering my work across various fields.

-A "Projects and Milestones" page listing my competition, award, and project history.

-A "Social and Media" page which include links to my other social media platforms.

-Hover animations that cause the images to enlarge slightly and stand out when the cursor hovers over them (using transform + transition)

-Separate and simplified mobile design to provide a cleaner and more user-friendly experience on smaller screens.



Overall, it’s a personal website that truly reflects who I am!

## 👀**Preview:**
<img width="1918" height="870" alt="Ekran görüntüsü 2026-08-16 235043" src="https://github.com/user-attachments/assets/fb9a04c7-1f2f-4a93-b852-dfd718556b0a" />
<img width="1916" height="873" alt="Ekran görüntüsü 2026-08-16 235112" src="https://github.com/user-attachments/assets/0f3819a5-e506-4cef-bc33-e8c95840caa6" />
<img width="1918" height="872" alt="Ekran görüntüsü 2026-08-16 235124" src="https://github.com/user-attachments/assets/196fb1f2-2eb3-43e1-adfd-5cdf35260df6" />
<img width="1918" height="876" alt="Ekran görüntüsü 2026-08-16 235135" src="https://github.com/user-attachments/assets/f5786413-d747-4c3a-8505-3495c80be165" />
<img width="1918" height="872" alt="Ekran görüntüsü 2026-08-16 235147" src="https://github.com/user-attachments/assets/8e4a96cc-f042-4791-90e4-01a66c586016" />








## 🔗 Live Demo Link (so you won't have trouble finding it quickly):
https://berragurlesin.github.io/my-website/

## ⚙️ **Design & Layout Details:**

### 🛠️**Tools I Used:**
-HTML5

-CSS3 (Flexbox, free-form layout using `position: absolute`, CSS variables)

-Google Fonts — Caveat (handwritten notes), Inter (body text), Syne (headings)

-Font Awesome — social media icons

### 📁 **Site Structure:**
```text
├── index.html        → About Me (homepage, scrapbook collage)
├── essays.html       → Writings and Essays
├── projects.html     → Projects and Milestones
├── socials.html      → Social media links
├── style.css         → Global stylesheet for all pages
└── images/           → Photos, stickers, and decorative assets
```

### 📱**Mobile Responsiveness & Layout Optimization:**

To improve the mobile user experience and prevent the complex scrapbook collage from breaking the layout on small screens, I restructured the CSS media queries (`@media`).
Platform-Specific View: The absolutely positioned (`absolute`) collage structure (`.scrapbook-canvas`) displayed on desktop screens is hidden on mobile devices (`≤768px`), and a simple, highly readable bio card (`.bio-single-block`) is displayed instead.
Desktop Cleanup: To prevent content added for mobile from appearing twice on the desktop screen and creating artificial vertical gaps (ghost scrolling) at the bottom of the page, the layout was reset using `@media (min-width: 769px)` rules.
Footer & Overflow Alignment: By optimizing visual canvas heights (`height`) and bottom margins/padding (`margin/padding`), the page now ends smoothly at the exact footer alignment.

### 🎨**Scrapbook Collage Positioning & Layering:**

Each image in the collage section is positioned using `position: absolute` at the top, left, and right coordinates within the `.scrapbook-canvas` element—just like pasting a photo into a physical scrapbook. The z-index controls the layering order of the images, while the `:hover` selector makes them enlarge and come to the foreground when the cursor hovers over them.

## 🤖**AI Usage:**

Throughout this project, I used AI (Claude) as a learning tool. Whenever I encountered something I did not know how to do, I asked Claude to explain the process and guide me. For example, I learned how to make images enlarge and move to the foreground when hovered over, how to integrate custom fonts into my website, and how to add a copyright section to the footer. I also used AI while debugging issues I encountered during development. For instance, when some elements overlapped on mobile screens, Claude explained how and why I should use CSS `@media` queries to create a separate layout for smaller screen sizes. In this way, I used AI to understand new concepts, fix my mistakes, and improve my coding skills throughout the development process. Also since English is not my native language, I also used DeepL to help translate and refine the English versions of the texts on my website.


