# README

Präsentation für LV Januar 2022, Donau-Universität Krems

## Selfreminder

Set-Up following [Creating presentations with Reveal and Github pages, 21/02/2021](https://dbafromthecold.com/2021/02/21/creating-presentations-with-reveal-and-github-pages/)

#### But (!) Linux 

| Windows | Linux |
|---|----|
| not new-item test.txt | touch text.txt  |  
| copy-item ..\reveal.js\index.html  | cp - ../reveal.js/index.html |
| copy-item ..\reveal.js\css   |  cp -R ../reveal.js/css |
| copy-item ..\reveal.js\dist   |  cp -R ../reveal.js/dist |
| copy-item ..\reveal.js\js    | etc.  |
| copy-item ..\reveal.js\plugin    | etc. |

#### & changed

index.html 

	<div class="slides">
		<section data-markdown="slides.md"
			data-separator="^^\r?\n---\r?\n$"
			data-separator-vertical="^\r?\n------\r?\n$"
			data-separator-notes="^Note:"
			data-charset="iso-8859-15"
			data-transition="slide">
		</section>
	</div>

to

		<div class="slides">
				<section data-markdown="slides.md"
				data-separator="^^\r?\n---\r?\n$"
				data-separator-vertical="^\r?\n----\r?\n$"
				data-transition="slide">
			</section>
			</div>

