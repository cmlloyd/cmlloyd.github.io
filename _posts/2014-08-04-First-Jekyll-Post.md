---
layout: post
title: First Post using Jekyll
---

This is test content.

Over several lines.

Including images:

![Alt text](http://cdn.sstatic.net/stackoverflow/img/sprites.png?v=3c6263c3453b)

And links:

[Example link](http://daringfireball.net/projects/markdown/syntax)

And blockquotes:

> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
> consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
> Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.
> 
> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
> id sem consectetuer libero luctus adipiscing.

And code:

{% highlight ruby %}
def show 
  @widget = Widget(params[:id]) 
  respond_to do |format| 
    format.html # show.html.erb 
    format.json { render json: @widget } 
  end 
end
{% endhighlight %}

So there we have it...
