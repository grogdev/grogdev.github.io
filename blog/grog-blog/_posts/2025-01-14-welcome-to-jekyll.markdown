---
layout: post
title:  "Welcome to Jekyll!"
date:   2025-01-14 17:16:51 -0400
categories: jekyll update
---
Yo whaddup

You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

Jekyll requires blog post files to be named according to the following format:

`YEAR-MONTH-DAY-title.MARKUP`

Where `YEAR` is a four-digit number, `MONTH` and `DAY` are both two-digit numbers, and `MARKUP` is the file extension representing the format used in the file. After that, include the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight javascript %}
walk_neutral = function(_callback){
  image_angle = sin(tick*.5)*8
  var _spd = .5;
  if point_distance(x, y, dest_x, dest_y) > _spd {
    var _dir = point_direction(x, y, dest_x, dest_y);
    xspeed = lengthdir_x(_spd, _dir);
    yspeed = lengthdir_y(_spd, _dir);
  } else {
    x = dest_x;
    y = dest_y;
    image_angle = 0;
    reset_speeds();
    _callback.finish();
  }
}

{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
