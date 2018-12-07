# Sticky-Notes
Sticky To-Do Notes made with vue.js, you can embed in your project

Requirements:

    Latest Version Of Vue.js v2 Download Vue
    Latest Version Of httpVueLoader.js v2 Download From Github
    Latest Version Of fontawesome.css Download From Github
    Version 3 bootstrap.css Download
    - You can customize the style anyway

Plugin Content
Once downloaded or clone the repo,compressed folder to see the structure of (the compiled) Sticky To-Do Notes. You'll see below like this:

Sticky to-do Notes/<br>
	└── plugin/<br>
		├── components/<br>
		│   ├── multiNotes.vue<br>
		│   ├── sharedNote.vue<br>
		│   └── singleNote.vue<br>
		├── css/<br>
		│   └── stickyNotes.css<br>
		├── js/<br>
		│   └── stickyNotes.js<br>
		└── fonts/<br>
			├── Poppins-Light.ttf<br>
			├── Poppins-Medium.ttf<br>
			├── Poppins-Regular.ttf<br>
			├── Poppins-SemiBold.ttf<br>
			├── toriom-light.ttf<br>
			└── toriom-medium.ttf<br>
	
<h3>How To Embed In My Project</h3>
				<p>Just use the tag <code>&lt;sticky-notes&gt;</code> inside a div with <code>id="notes"</code> and <code>class="notes"</code></p>
				<pre>
&lt;div id="notes" class="notes"&gt;
  &lt;div class="container"&gt;
   &lt;sticky-notes&gt;&lt;/sticky-notes&gt;
  &lt;/div&gt;
&lt;/div&gt;
				</pre>

<h3>For Shared Note !</h3>
				<p>To make your note sharable you need to create HTML page called <code>shared.html</code> and use <code>&lt;shared-note&gt;</code> tag as following :</p>
				<pre>
&lt;div id="notes" class="notes"&gt;
  &lt;div class="container"&gt;
   &lt;shared-note&gt;&lt;/shared-note&gt;
  &lt;/div&gt;
&lt;/div&gt;
				</pre>
				
<h3>Contribute</h3>
<p>If you have a feature request, please add it as an issue or make a pull request.</p>
