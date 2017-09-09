# SOMEONE FIGURE OUT HOW TO EMBED STUFF
### ALSO THIS IS DANIEL'S RESPONSIBILITY.
[//]: # let's see if this works
<div class="home">

  <h1 class="page-heading">Posts</h1>

  <ul class="post-list">
    {% for post in site.posts %}
      <li>
        <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>

        <h2>
          <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
        </h2>
      </li>
    {% endfor %}
  </ul>

  <p class="rss-subscribe">subscribe <a href="{{ "/feed.xml" | prepend: site.baseurl }}">via RSS</a></p>

</div>

[//]: # daniel only touch this page and nothing else. only edit within the github page, and not using the app. if you don't you WILL screw something up and michael and I will be upset
