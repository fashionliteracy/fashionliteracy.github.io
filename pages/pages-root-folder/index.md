---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_main.webp
widget1:
  title: "Blog & News"
  url: '/blog/'
  image: widget-1-302x182.jpg
  text: 'Our blog features frequent articles from the domains of technology, fashion & lifestyle, and entrance exams.  We focus to write our content in an easy language with minimal jargon. <br/> If you miss some of our posts then do not forget to take a look at the <a href="/blog/archive/">Blog Archive</a>.'
widget2:
  title: "Want to check our products?"
  url: '#'
  text: '<em>FashionLiteracy</em> has following four products.<br/>1.  3D printed merchandize <br/>2. Online Courses for Entrances exams<br/>3. Books <br/>4. Fashion Weekly.'
  image: header_3d_merchandize-302x182.webp
  # video: '<a href="#" data-reveal-id="videoModal"><img src="http://phlow.github.io/feeling-responsive/images/start-video-feeling-responsive-302x182.jpg" width="302" height="182" alt=""/></a>'
widget3:
  title: "Free Resources"
  url: '#'
  image: widget-github-303x182.webp
  text: '<em>FashionLiteracy</em> contributes to the community to fashion world by brining free content for our readers in the form of <a href="/resources/tutorials">Tutorials</a>, <a href="/resources/gd-topics">GD Topics</a>, <a href="/resources/quizzes">Quizzes</a>, and <a href="/resources/project-topics">Project Topics</a>. <br/>In addition, we also are quite active on social media. Please follow us on Instagram <a href="https://www.instagram.com/fashion.literacy">@Fashion.literacy</a>.'
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
callforaction:
  url: https://feedburner.google.com/fb/a/mailverify?uri=Fashionliteracy&amp;loc=en_US
  text: Inform me about new updates ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
