---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: https://mitmuseum.mit.edu/sites/default/files/cajal-webpage.jpg
widget1:
  title: "research"
  url: 'http://phlow.github.io/feeling-responsive/blog/'
  image: http://1.bp.blogspot.com/-I968nR2QUYU/VlJxuteN0DI/AAAAAAAAKJw/Rqfx_HPAVj0/s1600/bubble.png
  text: 'Researching in AHlab is one of the branches of our work'
widget2:
  title: "publications"
  url: 'http://phlow.github.io/feeling-responsive/info/'
  text: 'Through the years numerous publications from our lab has been published by the most renamed world editors'
  video: '<a href="#" data-reveal-id="videoModal"><img src="http://phlow.github.io/feeling-responsive/images/start-video-feeling-responsive-302x182.jpg" width="302" height="182" alt=""/></a>'
widget3:
  title: "lab"
  url: 'https://github.com/Phlow/feeling-responsive'
  image: widget-github-303x182.jpg
  text: 'In the Lab we believe in open knowledge and never use again wordpress'
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
  url: https://tinyletter.com/feeling-responsive
  text: Inform me about new updates and features ›
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
