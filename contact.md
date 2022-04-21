---
layout: contact
title: Contact
---
{% capture styles %}
    {% include contact.scss %}
{% endcapture %}
<style>
    {{ styles | scssify }}
</style>
<script src="https://kit.fontawesome.com/ec81ee530b.js" crossorigin="anonymous"></script>

<div class="wrapper">
	<div class="top-icons"></div>
	<div class="profile">
		<img src="/images/Prianka2.jpg" class="thumbnail" alt="Photo of Prianka Mandal">
		<h3 class="name">{{ site.name }}</h3>
		<p class="title">{{ site.description }}</p>
		<p class="description">{{ site.search_result_description }}</p>
		<a href="{{ site.url }}" class="btn"><button type="button" class="btn">Website</button></a>
	</div>
	<div class="bottom">
		<div class="social-icons">
			<div class="icon">
				<a href="tel:+17578395803" aria-label="Call Prianka"><i class="fa-solid fa-phone" style="line-height: 2"></i></a>
				<h4>Phone</h4>
			</div>
			<div class="icon">
				<a href="mailto:priankamandal17@gmail.com" aria-label="Email  Amit"><i class="fa-solid fa-envelope-circle-check" style="line-height: 2"></i></a>
				<h4>Email</h4>
			</div>
			<div class="icon">
				<a href="https://www.linkedin.com/in/prianka-mandal-9726891a8" aria-label="LinkedIn Profile of Prianka"><i class="fa-brands fa-linkedin" style="line-height: 2"></i></a>
				<h4>LinkedIn</h4>
			</div>
			<div class="icon">
				<a href="/cv" aria-label="CV of Prianka"><i class="fa-solid fa-file-lines" style="line-height: 2"></i></a>
				<h4>CV</h4>
			</div>
		</div>
	</div>
	<div class="qrcode">
		<img src="/images/prianka_qr.png"
				alt="contact QR Code"
				srcset="/images/prianka_qr.svg"
				class="qrimg"/>
	</div>
</div>
