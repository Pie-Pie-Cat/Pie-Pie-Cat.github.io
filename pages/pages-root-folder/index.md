---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: page-fullwidth
header: no
title:  "Connecting People In A Way You've Never Seen Before"
subheadline: "Our Mission"
teaser: "Can you imagine a social network that does not rely on Internet connectivity, and by nature does not collect user information at all?<br /><br />
Yes, you are not crazy.<br />
Using Short-Range Wireless Communication technologies, Pie Pie Cat Tech helps connect every nearby mobile phones directly with each other, without having to connect to any cell phone towers in between, creating unprecedented social experiences you've never seen before.<br /><br />
Pie Pie Cat Tech is the one stop shop where you can find social networks that
- Does not rely on the Internet.
- Will not be impacted by the repeal of Net Neutrality rules.
- Fully complies with China’s new cybersecurity law.
- And fully complies with the GDPR too<br /><br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- <i>Say no to User info collection!</i><br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- <i>Say no to User data breach!</i><br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- <i>Say no to Net Neutrality violation!</i><br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- <i>Privacy Matters!</i><br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- <i>Embrace the Next Gen Social Networks!</i><br /><br />
Check out our app listings down below:<br />"
breadcrumb: true
layout: frontpage
widget1:
  title: "HiThere: an anonymous face to face dating app"
  url: 'http://127.0.0.1:4000/hi-there/'
  image: hithere.jpg
  <!--image: widget-1-302x182.jpg-->
  text: '<i>Make your first move when you see someone attractive, realtime.</i>
<ul>
<li>No registration required. (anonymous)</li>
<li>Works without Internet connectivity.</li>
<li>Stores user profile locally.</li>
<li>Uses BLE/Wi-Fi P2P to detect a nearby user and send/receive information directly.</li>
<li>User profiles will be broadcast only to nearby users.</li>
<li>Does not have a server side.</li>
<li>Based on the nature of this implementation, it does not collect (and is not able to collect) user information.</li>
<li>Utilizes the proximity between mobile phones, instead of location data.</li>
</ul>'
widget2:
  title: "Guess What: sharing moments just with someone nearby"
  url: 'http://127.0.0.1:4000/guess-what/'
  image: guesswhat.jpg
  text: "<i>Spread information in an old fashioned way. (word of mouth way. Short-Range Based Wireless Communication technology is used, not the mouth, to be precise)</i>
<ul>
<li>Kinda like Whisper and Yik Yak combined, except there is no server side.</li>
<li>Don't even need a user name to get started.</li>
<li>Express your stories/moments to people within a visible range.</li>
<li>Forward information to nearby using BLE/Wi-Fi P2P instead of The Internet.</li>
<li>Don't have to worry about leaving any trace behind.</li>
<li>Yes all voices can be heard.</li>
</ul>"
widget3:
  title: "POOF: a near range disappearing messaging app"
  url: 'http://127.0.0.1:4000/poof/'
  image: poof.jpg
  <!--image: widget-github-303x182.jpg-->
  text: "<i>Providing a fun way to interact with nearby people, unprecedentedly.</i>
<ul>
<li>Just need a nickname to get started. (The nickname is stored locally though)</li>
<li>Only allows to communicate with someone with a visual contact.</li>
<li>Messages received and the sender's nickname will be deleted from the receiver side if the sender walks away.</li>
<li>Messages sent will also be deleted on quiting the app.</li>
<li>Messages are exchanged directly between mobile phones without a server in between.</li>
<li>Leaves no trace behind.
</ul>"
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
