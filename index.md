---

layout: col-sidebar
title: OWASP Rochester
tags: Rochester

region: North America
meetup-group: OWASP-Rochester-Chapter
country: USA
postal-code: 14602

---

## Welcome
Welcome to the Rochester, NY Chapter.

If you are interested in presenting, sponsoring, or hosting a meeting, please reach out to the chapter leaders.

## Upcoming Meetings
{% include chapter_events.html group=page.meetup-group %}

(Coming soon)

## Past Meetings
{% for meeting in site.data.meetings %}
<h3>{{ meeting.title }}</h3>
{{ meeting.presenter }}<br>
When: {{ meeting.date }}{% if meeting.time %} at {{ meeting.time }} {% endif %}<br>
{% if meeting.location %}Location: {{ meeting.location }}<br>{% endif %}
Register to attend at <a href="{{ meeting.link }}">{{ meeting.link }}</a><br>
<br>
{{ meeting.description }}<br>
{% endfor %}

## Participation
The Open Web Application Security Project (OWASP) is a nonprofit foundation that works to improve the security of software. All of our projects ,tools, documents, forums, and chapters are free and open to anyone interested in improving application security. 

Chapters are led by local leaders in accordance with the [Chapter Leader Handbook](/www-policy/rules-of-procedure/chapter-handbook). Financial contributions should only be made online using the authorized online donation button. To be a SPEAKER at ANY OWASP Chapter in the world simply review the [speaker agreement](/www-policy/speaker-agreement) and then contact the local chapter leader with details of what OWASP Project, independent research, or related software security topic you would like to present.

Everyone is welcome and encouraged to participate in our [Projects](/projects), [Local Chapters](/chapters), [Events](/events), [Online Groups](https://groups.google.com/a/owasp.com/), and [Community Slack Channel](https://owasp.slack.com/). We especially encourage diversity in all our initiatives. OWASP is a fantastic place to learn about application security, to network, and even to build your reputation as an expert. We also encourage you to be [become a member](/membership) or consider a [donation](/donate) to support our ongoing work.
