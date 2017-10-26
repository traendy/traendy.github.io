---
layout: post
title:  JSON value '<null>'...
date:   2017-10-26 18:41:18 +0200
categories: React Native
---
# JSON value '<null>' of type NSNull cannot be converted to NSString

This error is the most annoying error that occurred in my short React Native Carrer so far. I had such a hard time to solve this Issue that I try to abstract it in this blog post.

If you are a React Native geek, this is not for you. But for all beginners like me. This might help you.

At my company is a huge Summit event in a couple of weeks. The idea was to build an App and every attendee can download it to read the schedule, vote presentations, have a map with all locations marked on it and a small facebook for all the people involved.

So we started and after a short time we already had quite a lot to show and play around. I mean it is just a fancy UI with a firebase back end.

Anyway after we implemented a objective C library for some reasons and its pendent in java, we faced a cryptic error:
> JSON value '<null>' of type NSNull cannot be converted to NSString

You might think, well, thats an easy solveable problem. This guy is nuts.

But the error occoured so far away from its actual origin, that I had no idea.

I downloaded some Ide enhancements like flow and linter and nuclide and then I deleted half of it because it sloved everything down for some reason. 

Understanding flow and starting to rewrite our code  


To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
