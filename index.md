layout: default
---

<div class="wrapper">
  <header>
    <h1><a href="{{ "/" | absolute_url }}">{{ site.title | default: site.github.repository_name }}</a></h1>
    <img src="{{site.logo | relative_url}}" alt="Logo" />
    {% endif %}
    <p>{{ site.description | default: site.github.project_tagline }}</p>
    {% if site.github.is_project_page %}
    <p class="view"><a href="{{ site.github.repository_url }}">View the Project on GitHub <small>{{ site.github.repository_nwo }}</small></a></p>
    {% endif %}
    {% if site.github.is_user_page %}
    <p class="view"><a href="{{ site.github.owner_url }}">View My GitHub Profile</a></p>
    {% endif %}
  </header>

  <footer>
    {% if site.github.is_project_page %}
    <p>This project is maintained by <a href="{{ site.github.owner_url }}">{{ site.github.owner_name }}</a></p>
    {% endif %}
  </footer>
</div>

## Who Am I?
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
