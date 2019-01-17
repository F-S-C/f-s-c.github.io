---
title: FSC
---
# FSC

This team was born in 2018 to take a group exam and it's made of five collegues and _friends_ that saw in that exam the oportunity to start working together as a real group. Now we are ready to take any challenge and give life to our ideas.

## The Name: Who We Are

_"FSC"_ stands for _"Five Students of Computer Science"_: we are five Bachelor's Students of Computer Science and Digital Communication at the University of Bari "Aldo Moro".

The team is composed by:

- Alessandro _Annese_
- Davide _De Salvo_
- Andrea _Esposito_
- Graziano _Montanaro_
- Regina _Zaccaria_

## Our Public Repositories

Here is a list of all of our public repositories (excluding the repository from which this site is generated).

<ul>
    {% for repository in site.github.public_repositories %}
        {% if repository.name != "F-S-C.github.io" %}
            <li><a href="{{ repository.html_url }}" target="_blank">{{ repository.name }}</a></li>
        {% endif %}
    {% endfor %}
</ul>
