--- 
layout: post
title: How do I change the Ruby/Python version Textmate uses?
created: 1328766604
comments: true
categories: [ruby, textmate, how-to, python]
---
<p>&nbsp;</p>
<p>I&#39;m using textMate to develop ruby code. It&#39;s very handy because I can run it just pressing (cmd-R). But by default it&#39;s running ruby 1.8.7 and I want 1.9.2 version.</p>
<p>This is the steps to change it:</p>
<p>Find the right path with</p>
<div>
	<div>
		<strong>~$ &nbsp;which rvm-auto-ruby</strong></div>
	<div>
		/Users/adrian/.rvm/bin/rvm-auto-ruby</div>
</div>
<div>
	<strong>~$ &nbsp;which python3.2</strong></div>
<div>
	/usr/local/bin/python3.2</div>
<div>
	&nbsp;</div>
<p>Then copy it to TextMate preferences in a new variable called &quot;TM_RUBY&quot;, and &quot;TM_PYTHON&quot; as shown bellow:</p>
<p><img alt="" src="http://adrianmejiarosario.com/sites/default/files/Screen%20Shot%202012-02-09%20at%201.50.41%20AM.png" style="width: 792px; height: 402px; " /></p>
<p><img alt="" src="http://adrianmejiarosario.com/sites/default/files/Screen%20Shot%202012-02-09%20at%2012.48.17%20AM.png" style="width: 600px; height: 320px; " /></p>