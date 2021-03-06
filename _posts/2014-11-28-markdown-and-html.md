---
layout: post
title: Markdown and HTML
---

Story time. Living in sunny Bradenton, Florida, the toughest career decision I faced as a young, ambitious high school student was a simple one: What kind of Doctor would I be? Growing up the son of a Cardiologist and a pharmacist, there was never a doubt in my mind that I would venture into the medical field. While many of my peers faced many tough decisions and unanswered questions, my view of the next 10 years seemed like an easy one. The path, in fact, was all laid out for me. I would go to the University of Miami, where my sister was currently studying, to obtain my undergraduate degree on the pre-med track. I would then, of course, take the natural next steps of going to medical school and completing my residency. At the end of it all, which I could somehow see so clearly at the time, I would finally be a licensed physician just like my father, maybe even working alongside him one day. While this track seemed daunting and luminous to some, to me it was a comforting one. School was always rather easy for me. Sure I had some bad studying habits, but I knew at the end of the day that as the stakes grew higher, my focus and attention would follow suit. The hardest part for me, in fact, lied in making decisions and I didn't know it at the time but I would soon be faced with

The inklings of doubt began to creep in during my senior year of high school. I was volunteering at my parents' hospital as a courier. As a courier, you receive phone calls with all kinds of requests, usually deliveries that require you to travel through nearly every department of the hospital. As I walked through those dimly lit, cold hallways, patients and visitors whirling past me, I couldn't help but fight this nagging feeling in the pit of my stomach. This feeling can best be summed up in the form of one question: "Is this really what you want to do for the rest of your life?". It wasn't long before I realized this question had not been a new one and, in fact, had loomed in the background for quite some time. It was a question that was repressed by my fear of the answer; the fear that medicine wasn't my future and that I actually had no idea where my life was headed. After all, I didn't like the sight of blood, I despised needles, and while I did well in my science classes, they never sparked much interest in me. It wasn’t until my first semester of undergrad at the University of Miami that I finally came to terms with this fear, realizing that I couldn't let it waste any more of my time or my parent's money.




Jeykll supports the use of [Markdown](http://daringfireball.net/projects/markdown/syntax) with inline HTML tags which makes it easier to quickly write posts with Jekyll, without having to worry too much about text formatting. A sample of the formatting follows.

Tables have also been extended from Markdown:

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

Here's an example of an image, which is included using Markdown:

![Geometric pattern with fading gradient]({{ site.baseurl }}/img/blocflix.png)

Highlighting for code in Jekyll is done using Pygments or Rouge. This theme makes use of Pygments by default.

{% highlight js %}
// count to ten
for (var i = 1; i <= 10; i++) {
    console.log(i);
}
{% endhighlight %}

{% highlight ruby %}
def show
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }
  end
end
{% endhighlight %}

{% highlight js %}
// count to twenty
var j = 0;
while (j < 20) {
    j++;
    console.log(j);
}
{% endhighlight %}

Type Theme uses KaTeX to display maths. Equations such as $$S_n = a \times \frac{1-r^n}{1-r}$$ can be displayed inline.

Alternatively, they can be shown on a new line:

$$ f(x) = \int \frac{2x^2+4x+6}{x-2} $$
