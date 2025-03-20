---
layout: about
title: about
permalink: /
subtitle: <a href='#'>Affiliations</a>. Address. Contacts. Motto. Etc.

profile:
  align: right
  image: prof_pic.jpg
  image_circular: true # crops the image to make it circular
  more_info: >
    <p>P023</p>
    <p>L7 1</p>
    <p>Mannheim</p>

selected_papers: false# includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: true
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

Write your biography here. Tell the world about yourself. Link to your favorite [subreddit](http://reddit.com). You can put a picture in, too. The code is already in, just name your picture `prof_pic.jpg` and put it in the `img/` folder.

Put your address / P.O. box / other info right below your picture. You can also disable any of these elements by editing `profile` property of the YAML header of your `_pages/about.md`. Edit `_bibliography/papers.bib` and Jekyll will render your [publications page](/al-folio/publications/) automatically.

Link to your social media connections, too. This theme is set up to use [Font Awesome icons](https://fontawesome.com/) and [Academicons](https://jpswalsh.github.io/academicons/), like the ones below. Add your Facebook, Twitter, LinkedIn, Google Scholar, or just disable all of them.

---

<div class="main-navigation-buttons">
  <a href="/research/" class="btn btn-sm z-depth-0" role="button">Research</a>
  <a href="/cv/" class="btn btn-sm z-depth-0" role="button">CV</a>
  <a href="/teaching/" class="btn btn-sm z-depth-0" role="button">Teaching</a>
</div>

.main-navigation-buttons {
  margin: 30px 0;
  text-align: center;
}

.main-navigation-buttons .btn {
  margin: 5px;
  padding: 10px 20px;
  font-size: 1.2rem;
  font-weight: 500;
  border: 2px solid var(--global-theme-color);
  color: var(--global-theme-color);
  background-color: transparent;
  transition: all 0.3s ease;
}

.main-navigation-buttons .btn:hover {
  background-color: var(--global-theme-color);
  color: var(--global-bg-color);
}