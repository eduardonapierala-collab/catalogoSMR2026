---
title: "Welcome to Jekyll"
layout: post
---

You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.


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


div uk-filter="target: .js-filter">

    <div class="uk-grid-small uk-flex-middle" uk-grid>
        <div class="uk-width-expand">

            <div class="uk-grid-small uk-grid-divider uk-child-width-auto" uk-grid>
                <div>
                    <ul class="uk-subnav uk-subnav-pill" uk-margin>
                        <li class="uk-active" uk-filter-control><a href="#">All</a></li>
                    </ul>
                </div>
                <div>
                    <ul class="uk-subnav uk-subnav-pill" uk-margin>
                        <li uk-filter-control="[data-color='white']"><a href="#">White</a></li>
                        <li uk-filter-control="[data-color='blue']"><a href="#">Blue</a></li>
                        <li uk-filter-control="[data-color='black']"><a href="#">Black</a></li>
                    </ul>
                </div>
                <div>
                    <ul class="uk-subnav uk-subnav-pill" uk-margin>
                        <li uk-filter-control="[data-size='small']"><a href="#">Small</a></li>
                        <li uk-filter-control="[data-size='medium']"><a href="#">Medium</a></li>
                        <li uk-filter-control="[data-size='large']"><a href="#">Large</a></li>
                    </ul>
                </div>
            </div>

        </div>
        <div class="uk-width-auto uk-text-nowrap">


            <span class="uk-active" uk-filter-control="sort: data-name"><a class="uk-icon-link" href="#" uk-icon="icon: arrow-down" aria-label="Sort ascending"></a></span>
            <span uk-filter-control="sort: data-name; order: desc"><a class="uk-icon-link" href="#" uk-icon="icon: arrow-up" aria-label="Sort descending"></a></span>

        </div>
    </div>

    <ul class="js-filter uk-child-width-1-2 uk-child-width-1-3@m uk-text-center" uk-grid="masonry: true">
        <li data-color="white" data-size="large" data-name="A">
            <div class="uk-card uk-card-default uk-card-body">
                <canvas width="600" height="800"></canvas>
                <div class="uk-position-center">A</div>
            </div>
        </li>
        <li data-color="blue" data-size="small" data-name="B">
            <div class="uk-card uk-card-primary uk-card-body">
                <canvas width="600" height="400"></canvas>
                <div class="uk-position-center">B</div>
            </div>
        </li>
        <li data-color="white" data-size="medium" data-name="C">
            <div class="uk-card uk-card-default uk-card-body">
                <canvas width="600" height="600"></canvas>
                <div class="uk-position-center">C</div>
            </div>
        </li>
        <li data-color="white" data-size="small" data-name="D">
            <div class="uk-card uk-card-default uk-card-body">
                <canvas width="600" height="400"></canvas>
                <div class="uk-position-center">D</div>
            </div>
        </li>
        <li data-color="black" data-size="medium" data-name="E">
            <div class="uk-card uk-card-secondary uk-card-body">
                <canvas width="600" height="600"></canvas>
                <div class="uk-position-center">E</div>
            </div>
        </li>
        <li data-color="black" data-size="small" data-name="F">
            <div class="uk-card uk-card-secondary uk-card-body">
                <canvas width="600" height="400"></canvas>
                <div class="uk-position-center">F</div>
            </div>
        </li>
        <li data-color="blue" data-size="medium" data-name="G">
            <div class="uk-card uk-card-primary uk-card-body">
                <canvas width="600" height="600"></canvas>
                <div class="uk-position-center">G</div>
            </div>
        </li>
        <li data-color="black" data-size="large" data-name="H">
            <div class="uk-card uk-card-secondary uk-card-body">
                <canvas width="600" height="800"></canvas>
                <div class="uk-position-center">H</div>
            </div>
        </li>
        <li data-color="blue" data-size="large" data-name="I">
            <div class="uk-card uk-card-primary uk-card-body">
                <canvas width="600" height="800"></canvas>
                <div class="uk-position-center">I</div>
            </div>
        </li>
        <li data-color="white" data-size="large" data-name="J">
            <div class="uk-card uk-card-default uk-card-body">
                <canvas width="600" height="800"></canvas>
                <div class="uk-position-center">J</div>
            </div>
        </li>
        <li data-color="blue" data-size="medium" data-name="K">
            <div class="uk-card uk-card-primary uk-card-body">
                <canvas width="600" height="600"></canvas>
                <div class="uk-position-center">K</div>
            </div>
        </li>
        <li data-color="black" data-size="small" data-name="L">
            <div class="uk-card uk-card-secondary uk-card-body">
                <canvas width="600" height="400"></canvas>
                <div class="uk-position-center">L</div>
            </div>
        </li>
    </ul>

</div>

[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
