---
title: contacto
---

<form name="contacto" method="POST" data-netlify="true" netlify-honeypot="dulcemiel" data-netlify-recaptcha="true">
	<div class="fields">
		<div class="field half first">
			<label for="name">Nombre</label>
			<input type="text" name="name" id="name" />
		</div>
		<div class="field half">
			<label for="email">Email</label>
			<input type="text" name="_replyto" id="email" />
		</div>
		<div class="field">
			<label for="message">Mensaje</label>
			<textarea name="message" id="message" rows="4"></textarea>
		</div>
		<div class="field half first">
			<div data-netlify-recaptcha="true"></div>
		</div>
		<div class="field half">
			<label style="visibility:hidden">Si eres humano dejalo en blanco: <input name="dulcemiel" /></label>
		</div>
	</div>
	<ul class="actions">
		<li><input type="submit" value="Enviar" class="primary" /></li>
		<li><input type="reset" value="Borrar" /></li>
	</ul>
</form>
<ul class="icons">

{% if site.twitter_url %}
	<li><a href="{{ site.twitter_url }}" class="icon fa-twitter" target="_blank"><span class="label">Twitter</span></a></li>
{% endif %}
{% if site.telegram_url %}
	<li><a href="{{ site.telegram_url }}" class="icon fa-telegram" target="_blank"><span class="label">Telegram</span></a></li>
{% endif %}
{% if site.facebook_url %}
	<li><a href="{{ site.facebook_url }}" class="icon fa-facebook" target="_blank"><span class="label">Facebook</span></a></li>
{% endif %}
{% if site.instagram_url %}
	<li><a href="{{ site.instagram_url }}" class="icon fa-instagram" target="_blank"><span class="label">Instagram</span></a></li>
{% endif %}
{% if site.pinterest_url %}
	<li><a href="{{ site.pinterest_url }}" class="icon fa-pinterest" target="_blank"><span class="label">Pinterest</span></a></li>
{% endif %}
{% if site.gitlab_url %}
	<li><a href="{{ site.gitlab_url }}" class="icon fa-gitlab" target="_blank"><span class="label">GitLab</span></a></li>
{% endif %}
{% if site.github_url %}
	<li><a href="{{ site.github_url }}" class="icon fa-github" target="_blank"><span class="label">GitHub</span></a></li>
{% endif %}
{% if site.slack_url %}
	<li><a href="{{ site.slack_url }}" class="icon fa-slack" target="_blank"><span class="label">Slack</span></a></li>
{% endif %}
{% if site.linkedin_url %}
	<li><a href="{{ site.linkedin_url }}" class="icon fa-linkedin" target="_blank"><span class="label">LinkedIn</span></a></li>
{% endif %}

</ul>
