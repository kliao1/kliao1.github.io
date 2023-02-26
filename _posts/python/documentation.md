---
title: "Documentation in Python"
categories:
  - Python
---


When it comes to writing docstrings, you can choose to use the imperative, 
present tone or the... alternative tone (idk what to call it).
For e.g., 
For a function `foo()`
imperative
- return such and such value.
	- So we read it as `If we call this function, it will: return such and such value.`
alternative tone
- returns such and such value.
	- `foo() returns such and such value.`

The python community has agreed to use the imperative present tone.
- https://github.com/ethereum/snake-charmers-tactical-manual/issues/49
- https://stackoverflow.com/questions/59902102/why-is-imperative-mood-important-for-docstrings#:~:text=Why%20is%20it%20important%3F%20Because,explicitly%20specified%20in%20the%20documentation.

Documenting public methods is much more important than documenting private methods
- https://softwareengineering.stackexchange.com/questions/348873/is-it-consider-bad-practice-to-formally-document-implementation-code#:~:text=When%20it%20comes,months%20or%20years.
	- https://github.com/orkestra-energy/vippy/pull/676#discussion_r1068930127 