shopify-countdown-timer
Step 2: Edit your countdown timer You need to locate countdown timer code from your theme, add a new variable reset_in****. Please see example bellow:

{% include 'shopifyexplorer-countdown-timer', title: "Special Offer End In", end_date: "Sep 30, 2018" %}
and

{% include 'shopifyexplorer-countdown-timer', title: "Special Offer End In", reset_in: "1 day", end_date: "Sep 30, 2018" %}
Notice:

Now you can only set up countdown reset automatically with time more than 1 day. reset_in var accept day. See my example: 1 day
