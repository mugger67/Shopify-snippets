<article class="markdown-body entry-content container-lg" itemprop="text"><h1><a id="user-content-shopify-countdown-timer" class="anchor" aria-hidden="true" href="#shopify-countdown-timer"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>shopify-countdown-timer</h1>
<p>Step 2: Edit your countdown timer
You need to locate countdown timer code from your theme, add a new variable reset_in****. Please see example bellow:</p>
<pre><code>{% include 'shopifyexplorer-countdown-timer', title: "Special Offer End In", end_date: "Sep 30, 2018" %}
</code></pre>
<p>and</p>
<pre><code>{% include 'shopifyexplorer-countdown-timer', title: "Special Offer End In", reset_in: "1 day", end_date: "Sep 30, 2018" %}
</code></pre>
<p>Notice:</p>
<p>Now you can only set up countdown reset automatically with time more than 1 day.
reset_in var accept day. See my example: 1 day</p>
</article>
