---
title: contacto
---

<p>Para temas de trabajo, temas personales o simplemente saludar me puedes enviar un email completando el formulario de más abajo. Aunque, prefiero que me escribas vía <a href="{{ site.telegram_url }}" target="_blank">Telegram</a> <i class="fa fa-telegram" aria-hidden="true"></i> o mediante un mensaje directo en <a href="https://twitter.com/messages/compose?recipient_id=6705812" target="_blank">Twitter</a> <i class="fa fa-twitter-square" aria-hidden="true"></i>. ¡La elección es tuya!</p>

<form name="contacto" method="POST" data-netlify="true" netlify-honeypot="dulcemiel" data-netlify-recaptcha="true">
	<div class="fields">
		<div class="field half first">
			<label for="name">Nombre y apellido</label>
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
		<li><input type="submit" value="Enviar mensaje" class="primary" /></li>
		<li><input type="reset" value="Borrar" /></li>
	</ul>
</form>
