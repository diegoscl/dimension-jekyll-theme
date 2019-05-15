---
title: contacto
---

<p>Para temas de trabajo, temas personales, o simplemente decir *¡hola!* puedes enviarme un email completando el formulario de más abajo. Aunque prefiero que me escribas por <a href="{{ site.telegram_url }}" target="_blank"><i class="fa fa-telegram" aria-hidden="true"></i> Telegram</a> o por un mensaje directo en <a href="https://twitter.com/messages/compose?recipient_id=6705812" target="_blank"><i class="fa fa-twitter-square" aria-hidden="true"></i> Twitter</a>. ¡La elección es tuya!</p>

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
