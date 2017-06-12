---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
“These Thoughts, my dear Friend, are many of them crude and hasty, and if I were merely ambitious of acquiring some Reputation in Philosophy, I ought to keep them by me, ’till corrected and improved by Time and farther Experience. But since even short Hints, and imperfect Experiments in any new Branch of Science, being communicated, have oftentimes a good Effect, in exciting the attention of the Ingenious to the Subject, and so becoming the Occasion of more exact disquisitions (as I before observed) and more compleat Discoveries, you are at Liberty to communicate this Paper to whom you please; it being of more Importance that Knowledge should increase, than that your Friend should be thought an accurate Philosopher.”

Letter from Benjamin Franklin to Peter Collinson, September 1753 
(via http://www.earningmyturns.org/2011/07/why-we-publish.html)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
