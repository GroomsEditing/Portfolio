---
layout: post
title: Editing Samples
description: Before-and-after excerpts from recent projects
image: assets/images/pic03.jpg
nav-menu: true
---

{% capture edit_1 %}
Focused on pacing and interiority in the first act — trimming stage direction so the reader stays inside the character's head rather than watching from a distance.

Also flagged a handful of continuity issues around the timeline of the second chapter for the author to address in the next pass.
{% endcapture %}
{% capture before_1 %}
The old man walked slowly down the street. He was tired. He had been walking for a long time and his legs hurt. The sun was hot and there was no shade anywhere. He wanted to sit down but there was nowhere to sit.
{% endcapture %}
{% capture after_1 %}
The old man's legs ached with every step. He'd been walking for hours under a merciless sun, and the street offered no shade, no bench, nowhere to rest.
{% endcapture %}

{% include book-card.html
	title="The Long Road Home"
	book_url="https://example.com/books/the-long-road-home"
	author="Jane Doe"
	author_url="https://example.com/authors/jane-doe"
	pages="312"
	role="Developmental Editor"
	edit=edit_1
	before=before_1
	after=after_1 %}

{% capture edit_2 %}
A line edit pass to tighten sentence rhythm and cut redundant modifiers, plus a light copyedit for grammar and punctuation throughout.
{% endcapture %}
{% capture before_2 %}
She was very happy and excited to see the house for the first time, it was big and had alot of windows and she couldnt wait to move in.
{% endcapture %}
{% capture after_2 %}
She was thrilled to see the house for the first time — its wide windows caught the light, and she couldn't wait to move in.
{% endcapture %}

{% include book-card.html
	title="Windows to the Sea"
	book_url="https://example.com/books/windows-to-the-sea"
	author="Alex Rivera"
	author_url="https://example.com/authors/alex-rivera"
	pages="284"
	role="Copyeditor"
	edit=edit_2
	before=before_2
	after=after_2 %}
