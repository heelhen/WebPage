<h1>Website in the style of Sims 4</h1>

Finnish version here: <a href="https://github.com/heelhen/websivu/blob/main/README.md">https://github.com/heelhen/websivu/blob/main/README.md</a>

A portfolio site that is inspired by the Sims 4 game's style. It is made using JavaScript, HTML and CSS. This website, while still in progress, represents my skills in for example UI elements, popup windows and reusable components.

You can find it in the following repository: <a href="https://github.com/heelhen/mysite.git">https://github.com/heelhen/mysite.git</a>
Website at: <a href="https://heelhen.github.io/mysite/">https://heelhen.github.io/mysite/</a>

<img width="1536" height="816" alt="Screenshot of the website homepage" src="https://github.com/user-attachments/assets/407e7fb1-4d1b-453c-b0d0-25ef83840a7a" />

<h2>Features</h2>

- <b>Sims 4 styled UI</b>
  - Rounded panels, animations
- <b>Reusable components</b>
  - Upper and lower navigations are loaded from separate HTML files
  - Popup windows are loaded dynamically
- <b>Interactive popup windows</b>
  - Skills, education and work experience are shown in popup windows
  - Closable by clicking outside of them or with a close button
- <b>Clear structure</b>
  - HTML, CSS ja JS are separated from each other

<h2>Used technologies</h2>

- <b>HTML</b>
- <b>CSS</b>
  - Flexbox
  - Animations & transitions
  - CSS variables
- JavaScript
  - fetch() used with reusable components
  - Event handles
  - Dom-manipulations

<h2>Reusable components</h2>

<b>Navigation</b>
Upper and lower navigation panels are in their separate HTML files and added to each site using fetch()
```JavaScript
fetch("top-nav.html")
  .then(res => res.text())
  .then(html => {
    document.getElementById("nav-container").innerHTML = html;
  });
```
<img width="1920" height="1020" alt="Screenshot of Links page" src="https://github.com/user-attachments/assets/a10df17b-bc4a-4072-9404-1e3993ca1bf6" />

<b>Popup windows</b>
Popup windows are included inside popups.html-file and are controlled using a single JavaScript file

<img width="1536" height="816" alt="Screenshot of a popup of education information" src="https://github.com/user-attachments/assets/c54836e3-a8b3-46ad-80f1-28d3a8da2408" />

<h2>Style inspiration</h2>
Project was inspired by the UI from Sims 4, a game-like interaction design, simplicity and easy use.

<h2>Future improvements</h2>

- Keyboard usability (ESC to close popup windows)
- Better layout for mobile
- Graphical additions




