---
title: "SQL"
layout: post
---

SQL is one of the most widely used tools in the world of data analytics, for which I show below some of the syntaxes that I have used in queries in my previous work as well as in university projects that have required the SQL programming language.

It should be noted that SQL is a tool that I have used to connect with other applications such as:
- Knime
- Power BI

This fusion of tools makes more powerful the process of extracting data and transforming it into results that help decision making.



To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
select ename, length(ename), nvl(NULLIF(to_char(length(ename)), to_char(5)), 'length is 5') as result, sal from emp 
where sal > 2000
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
