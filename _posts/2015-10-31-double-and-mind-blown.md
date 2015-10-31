---
layout: page
title: double and....mind blown
tags: [programming, ruby, learning]
---
During class on Thursday, Brit was finishing up walking us through creating a blogging site.  He put up the following code on the screen to check whether the user was logged into the blog:

{% highlight ruby %}
def current_user
  session[:user_id] && User.find(:user_id)
end
{% endhighlight %}

As I was wondering to myself why he didn't put a ! on the end of the method name, Brit explained the method returns the ActiveRecord user object if the user is in session and exists in the database.  

![queue this](http://i3.kym-cdn.com/photos/images/newsfeed/000/897/530/642.gif)

From my many years writing in C, I fully expected the function to return a boolean value of true or false!  So many questions flew through my mind so I quickly started pry and began typing.  

{% highlight ruby %}
pry
[1] pry(main)> 5 && 2
=> 2
[2] pry(main)> 2 && 5
=> 5
[3] pry(main)> nil && 5
=> nil
[4] pry(main)> 5 && nil
=> nil
[5] pry(main)> "foo" && "bar"
=> "bar"
{% endhighlight %}

Ruby evaluates the item on the left side, and if not false or nil it evaluates and returns the results of the item on the right side of the &&.....

![wow](http://media.giphy.com/media/b8kHKZq3YFfnq/giphy.gif)

Ruby is an amazing language!  I am working hard absorb it all so I can utilize its features in thoughtful ways when I write code.  Class is starting to move faster, but I don't even care.  This is awesome!!