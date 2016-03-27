Hello, this is a simple responsive test website if you want to test your website with XAMPP (or offline)

A. Your Website Content Respond to Resolution

...

body {
	min-width: 480px;
	max-width: 320px;
	margin: auto;
	padding: 0;
}

...

min-width = maximum height value of your website content
max-width = maximum width value of your website content

Example:

Portrait Respond
min-width: 480px
max-width: 320px

=================

Landscape Respond
min-width: 320px
max-width: 480px

B. Your Example Screen Resolution

...

iframe {
	height: 100%;
	width: 100%;
	max-width: 320px;
	max-height: 480px;
}

...

max-width = maximum width value of your screen resolution
max-height = maximum height value of your screen resolution

Example:

Portrait Screen
max-width: 320px
max-height: 480px

=================

Landscape Screen
max-width: 480px
max-height: 320px

C. What's this?

This is just a simple way if you don't use a framework/plugin/software/extension to resize or offline.

NB: Default url on iframe src="http://127.0.0.1"