## Hey there!

This is me Tahir from Pakistan and I'm a Software Engineer by profession for over 5 years, in my spare times you find me reading about latest trends, helping people on [Stackoverflow](https://stackoverflow.com/users/5436736/tahir-raza) & [Quora](https://www.quora.com/profile/Tahir-Raza-51), or if I'm lukcy enough you'll see me in the mountains.

> I am neither especially clever nor especially gifted. I am only very, very curious. - Albert Einstein

This is my fuel to always stay hungry for knowledge. I'm curious about things, I really like to dig deeper in the depths of technology I'm using even if it takes a little more time than usual.

* * *

{% for post in site.posts %}
<div class="post-holder">
	<div class="post-left col-8">
		<h3>{{post.title}}</h3>
		<p>{{post.excerpt}}</p>
		<p> Posted on Dec 13, 2018 - 1 min Read </p>
	</div>
	<div class="post-right col-4">
		<img src="{{ post.image }}" title="{{ post.title }}" alt="{{ post.title }}" />
	</div>
</div>
{% endfor %}