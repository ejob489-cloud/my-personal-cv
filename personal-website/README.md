# JOB ELIJAH — Personal website

This responsive, four-page website is built with HTML and CSS. It includes the requested Home, Personal experience, Contacts, and Hobbies pages; matching top and bottom menus; a left-to-right animated 48px name banner; and green copyright text. The animation respects the visitor's reduced-motion setting.

## Pages and files

- `public/index.html` — Home page, profile photo, course, and editable personal biography.
- `public/experience.html` — Curriculum vitae table with exactly three columns, light-blue headings, and 1px green borders.
- `public/contacts.html` — Contact details and the email form.
- `public/hobbies.html` — Ordered and unordered hobby lists on a light-blue page background.
- `public/styles.css` — Shared styles, responsive layout, colors, and name animation.
- `public/assets/job-elijah.png` — The portrait image supplied for the website.

## Complete your personal details

The site uses **JOB ELIJAH** and **Information Technology**. The Home page now describes Kisii County as the user's background and presents an IT and cloud-computing career direction. The CV includes Kisii University (2026–2030, First Class Lower), Chavakali High School (2020–2024, B Plain), St Angelas Primary School (2013–2019, 373 marks), and IBM Cloud Computing (2025–2026). The Contacts page uses `ejob489@gmail.com`, `0757005868`, and Kisii County. The Hobbies page includes technology, cloud computing, music, reading, photography, and time with friends.

## Photo

Your supplied portrait is bundled at `public/assets/job-elijah.png`. The Home page in this downloadable copy uses the local path `assets/job-elijah.png`, so the photo appears when you extract the folder and open `public/index.html` directly. The live Preview uses managed website storage for the same image.

## Contact form

The **Email me** link and the native HTML form use `mailto:ejob489@gmail.com`. They open a configured email application rather than sending messages automatically. The checkbox includes a request for a copy in the draft; it does not send a copy on its own. Automatic delivery would require a backend or email service, which is not included in this HTML/CSS assignment.

## Run locally

To serve the site from this project directory, run `python3 -m http.server 3000 --directory public` and visit `http://localhost:3000`. Lora and DM Sans are loaded from Google Fonts when internet access is available, with Georgia and Arial fallbacks.
