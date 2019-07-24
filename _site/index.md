## Hey there!

This is me Tahir from Pakistan and I'm a Software Engineer by profession for over 5 years, in my spare times you find me reading about latest trends, helping people on [Stackoverflow](https://stackoverflow.com/users/5436736/tahir-raza) & [Quora](https://www.quora.com/profile/Tahir-Raza-51), or if I'm lucky enough you'll see me in the mountains.

> I am neither especially clever nor especially gifted. I am only very, very curious. - Albert Einstein

This is my fuel to always stay hungry for knowledge. I'm curious about things, I really like to dig deeper in the depths of technology I'm using even if it takes a little more time than usual.

* * *

{% for post in site.posts %}
<div class="post-holder flex mb-10">
	<div class="post-left w-3/4 pr-5">
		<h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
		<a href="{{ post.url }}" class="show-sm bg-center bg-no-repeat" title="{{ post.title }}" style="background-image: url('{{ post.image }}'); width: 100%; height: 100px; ">
		</a>
		<p>{{ post.excerpt }}</p>
		<p> Posted on {{ post.date | date: "%b %-d, %Y" }} - {{ post.time }} min Read </p>
	</div>
	<a href="{{ post.url }}" class="block hide-sm w-1/4 bg-contain bg-center bg-no-repeat" style="background-image: url('{{ post.image }}')">
	</a>
</div>

*** 

{% endfor %}