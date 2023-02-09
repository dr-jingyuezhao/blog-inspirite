# Inspirite
A blogging platform with a creative writing twist

## Summary Description
Inspirite offers the user a writing prompt in form of a randomly generated quote, image, fact, or GIF. The writing can be saved in the user's history page. A writing streak counter encourages the aspiring writer to hang in there and keep their writing pratice going.

- It serves a daily writing prompt to the user, to inspire them to write. The prompts can take the form of a quote, a fun fact, a GIF etc.

- It offers a simple, no distraction interface with focus on creative writing. 

- It displays the number of consecutive days of use.

- It stores user entries and allows for browsing of entries history.

## User story

As an aspiring writer:

- I want to practise creative writing every day.
- I want to be inspired to write on a variety of topics.
- I want to keep track of my progress.

Who is the target audience?
- Anyone who wants to practise their creative writing skills daily.
- Anyone looking for writing prompts and inspiration.
- Anyone who wants to keep track of their progress in creative writing.

What is the problem that it addresses?
- Consistently practising creative writing can be challenging. 
- It’s easy to lose track of one's progress.
- Finding inspiration for creative writing can be difficult.
- Having instant, easy access to previously written texts is desirable.

How does the product solve that problem?
- Inspirite provides a simple-to-use platform to practise creative writing daily.
- It prompts the users to write creatively.
- It keeps track of the users’ progress (writing streaks), motivating them to write consistently. 
- It stores previously written texts and lets the user search for specific tags.

## Technology
### CSS
Styling elements to buttons, cards, header, footer and jumbotron are applied.

### HTML
Added links to Google Fonts, Bootstrap, links in the footer and Jumbotron. Added a second HTML file to store the user's record of daily writing submissions.

### JavaScript
Used MomentJS to access current time stamp, retrieve information from Giphy and Ninja API, as well as jQuery calls to dynamically create elements in DOM for randomly generated GIF, images, quotes and facts.

### Bootstrap
Navbar, jumbotron, buttons, and cards from bootstrap are applied and customised for the app.

### Third-party and server-side APIs
jQuery and Moment are used. Giphy, and APIs data are used for prompts. 

## Installation
The website can be accessed follwing the link to the application page:
https://dr-jingyuezhao.github.io/blog-inspirite/

GitHub Repo: https://github.com/dr-jingyuezhao/blog-inspirite
GitHub Pages: https://dr-jingyuezhao.github.io/blog-inspirite/

## Usage
The app:
* Use Bootstrap.
* Be deployed to GitHub Pages.
* Be interactive.
* Use at least two server-side APIs.
* Link to an external site.
* Use modals instead of alerts, confirms, or prompts.
* Use client-side storage to store persistent data.
* Be responsive.
* Have a polished UI.


### Website demo
The following screenshots demonstrate the web application's appearance and functionality:

![website demo](assets/images/web_demo_home-page.jpg)
![website demo](assets/images/web_demo_quote-prompt.jpg)
![website demo](assets/images/web_demo_fact-prompt.jpg)
![website demo](assets/images/web_demo_img-prompt.jpg)
![website demo](assets/images/web_demo_gif-prompt.jpg)
![website demo](assets/images/web_demo_discard_modal.jpg)
![website demo](assets/images/web_demo_save_modal.jpg)
![website demo](assets/images/web_demo_publish_modal.jpg)
![website demo](assets/images/web_demo_saved-page_2.jpg)
![website demo](assets/images/web_demo_saved-page_draft.jpg)
![website demo](assets/images/web_demo_published-page.jpg)
![website demo](assets/images/web_demo_published-page_blog_2.jpg)


## Project documents
- Proposal
https://docs.google.com/document/d/1_e-iMsE5rRu6HXCnrnoc4OajT5UvslIOAEcLzokCVnM/edit?usp=sharing
https://drive.google.com/file/d/1brsqEuIZ28dgOupK-QWiErJAWuNk4cC-/view?usp=sharing
- Presentation
https://github.com/dr-jingyuezhao/blog-inspirite/tree/main/assets/docs/Inspirite_presentation-9-Feb-23


## Credits
Sophie https://github.com/sophiedodsworth | Maciek https://github.com/manonthemon | Jingyue https://github.com/dr-jingyuezhao | Lisa https://github.com/LisaMLorenz

## License

MIT License

Copyright (c) 2023 Jasmine

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.