---
layout: post
title: 'Integrating razorpay into your webapp'
date: 2019-03-23 21:03:36 +0530
categories: Javascript NodeJS
---

In terms of networking, a bridge network is a Link Layer device which forwards traffic between network segments. A bridge can be a hardware device or a software device running within a host machine’s kernel.

In terms of Docker, a bridge network uses a software bridge which allows containers connected to the same bridge network to communicate, while providing isolation from containers which are not connected to that bridge network. The Docker bridge driver automatically installs rules in the host machine so that containers on different bridge networks cannot communicate directly with each other.

```javascript
const Razorpay = require('razorpay');

let rzp = Razorpay({
  key_id: 'KEY_ID',
  secret: 'name'
});

// capture request
rzp.capture(payment_id, cost).then(function(data) {
  return 2;
});
```

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]: https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
