---
title: "Kontakt"
permalink: "/contact.html"
---

<form action="https://formspree.io/{{site.email}}" method="POST">    
<p class="mb-4">Masz pytania? Napisz do {{site.name}}. Odpowiemy tak szybko jak to możliwe!</p>
<div class="form-group row">
<div class="col-md-6">
<input class="form-control" type="text" name="name" placeholder="Imię*" required>
</div>
<div class="col-md-6">
<input class="form-control" type="email" name="_replyto" placeholder="E-mail*" required>
</div>
</div>
<textarea rows="8" class="form-control mb-3" name="message" placeholder="Treść wiadomości*" required></textarea>    
<input class="btn btn-success" type="submit" value="Wyślij">
</form>
