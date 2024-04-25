<h1>How to create a new dynamic class in Django</h1>

<h3>example</h3>
<img src="./1.png" alt="">

<h3>To:</h3>
<img src="./2.png" alt="">
<p>
    <br>
    {% with request.resolver_match.url_name as url_name %}
    {% endwith %}
</p>
<p>
    <br>
    class="{% if url_name == 'name_url' %}name class active{% endif %}"
</p>