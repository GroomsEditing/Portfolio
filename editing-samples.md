---
layout: post
title: Editing Samples
description: Before-and-after excerpts from recent projects
image: assets/images/pic03.jpg
nav-menu: true
---

{% capture before_1 %}
The old man walked slowly down the street. He was tired. He had been walking for a long time and his legs hurt. The sun was hot and there was no shade anywhere. He wanted to sit down but there was nowhere to sit.
{% endcapture %}
{% capture after_1 %}
The old man's legs ached with every step. He'd been walking for hours under a merciless sun, and the street offered no shade, no bench, nowhere to rest.
{% endcapture %}

{% include book-card.html
	title="The Long Road Home"
	author="Jane Doe"
	pages="312"
	role="Developmental Editor"
	edit="Developmental Edit"
	before=before_1
	after=after_1 %}

{% capture before_2 %}
She was very happy and excited to see the house for the first time, it was big and had alot of windows and she couldnt wait to move in.
{% endcapture %}
{% capture after_2 %}
She was thrilled to see the house for the first time — its wide windows caught the light, and she couldn't wait to move in.
{% endcapture %}

{% include book-card.html
	title="Windows to the Sea"
	author="Alex Rivera"
	pages="284"
	role="Copyeditor"
	edit="Line Edit"
	before=before_2
	after=after_2 %}
