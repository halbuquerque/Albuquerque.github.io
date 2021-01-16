  <html>
<p>Bem-vindo(a) ao meu blog pessoal! Postarei aqui informações que eu considerar relevantes para compartilhar com vocês. Dada meu grande interesse por computação, ciência de dados, Big Data e inteligência artificial, você pode esperar que estes temas sejam recorrentes em meus posts. Também criarei artigos relacionados a temas como a COVID-19 ou outro tema como esse, extremamente relevantes para todos nós. Sei que todos nós temos pouco tempo para consumir o enorme volume de informações disponíveis na Internet, então meus posts normalmente serão o mais diretos ao ponto possível. Abaixo, segue a lista de artigos que já estão disponíveis para leitura. Espero que gostem!<p>
  {% for post in site.posts %}
  - <a href="https://www.henriquearutin.com.br{{ post.url }}">{{ post.title }}</a><br />
  {% endfor %}
 </html>
