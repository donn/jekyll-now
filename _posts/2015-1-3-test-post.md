---
layout: post
title: Test page
---
Does this text appear?

{% highlight ruby %}
def show
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }
  end
end
{% endhighlight %}



Some code:
```C#
//valac --pkg gee-1.0 etc.

using Gee;
public class Obj : Object {
  public string id;
  public Obj(string id) {
    this.id = id;
  }
}

public void foo( Obj o) {
  stdout.printf("In func foo, o ref:%u\n",o.ref_count);
}
```


Fucking kramdown
~~~
//valac --pkg gee-1.0 etc.

using Gee;
public class Obj : Object {
  public string id;
  public Obj(string id) {
    this.id = id;
  }
}

public void foo( Obj o) {
  stdout.printf("In func foo, o ref:%u\n",o.ref_count);
}
~~~

