## Career Objectives 

As a Deepdive Java + Android student, I hope to obtain an entry level position is software development while pursuing a degree in Computer Science at night. I would hope to get a position that is willing to help me out financially to attend  classes at night.  

## Recent Repositories

<ul>
  {% assign public_repositories = site.github.public_repositories | where:'fork', false | sort: 'created_at' | reverse %}
  {% for repo in public_repositories limit: 10 %}
    <li>
      <p>
        <a href="{{ repo.html_url }}">
        {{ repo.name }}
        </a> {{ repo.created_at | date: "%B %-d, %Y" }}
      </p>
      {% if repo.description != '' %}
        <p>
          {{ repo.description | strip_html | escape }}
        </p>
      {% endif %}
    </li>
  {% endfor %}
</ul>

## Education 

CNM Inginuity Deepdive Java + Android Coding Bootcamp

## Links 

+ [LinkedIn](https://www.linkedin.com/in/quentin-dye-8a23a5192/)
+ [Github Profile](https://github.com/Quentin-D-NM)
