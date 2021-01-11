  <html>
  {% for post in site.posts %}
  - <a href="https://www.henriquearutin.com.br{{ post.url }}">{{ post.title }}</a><br />
  {% endfor %}
 </html>
