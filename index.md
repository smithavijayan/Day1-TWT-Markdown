---
layout: template
---

# Home page

_added this change through git bash_

This is a test file for a test pull request.

-  [Raindrops keep fallin' on my head](https://www.youtube.com/watch?v=sySlY1XKlhM)
-  [Rainy days and mondays](https://www.youtube.com/watch?v=PjFoQxjgbrs)
-  [Singin' in the rain](https://www.youtube.com/watch?v=swloMVFALXw)

# Hobbies

{% for items in site.data.data_file %}
The hobby of {{ items.hobby }} needs the object {{ items.object }}.
{% endfor %}

