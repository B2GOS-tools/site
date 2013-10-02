---
layout: bffos
title: Lists
section: building-blocks
h2: <strong>Building Blocks:</strong> markup & examples
---

## Lists

Lists are used to display a set of consecutive items, such as a list of contacts or a list of messages.

> ### Characteristics

> * List items may vary in height (from one to three rows in a single item).
> * List items may be as simple as just a text string, to including images, text, and buttons.
> * Lists are comprised of rows, with optional section headers.

### Default

<div>
  <h4>Example</h4>
  <section class="example">
    <img src="../images/BB/lists_1.png" alt="Lists (Image replacing code)"/>
    <article class="frame">
      <section data-type="list">
        <header>Title</header>
        <ul>
          <li>
            <p>Travis Gray</p>
          </li>
          <li>
            <a href="#">
              <p>Travis Gray</p>
              <p>Clickable item</p>
            </a>
          </li>
          <li>
            <aside class="pack-end">
              <img alt="placeholder" src="myimage.jpg">
            </aside>
            <a href="#">
              <p>Travis Gray</p>
              <p>Beginning of message</p>
            </a>
          </li>
        </ul>
        <header>Another title</header>
        <ul>
          <li aria-disabled="true">
            <aside class="pack-end">
              <img alt="placeholder" src="myimage.jpg">
            </aside>
            <a href="#">
              <p>Travis Gray</p>
              <p>Disabled item</p>
            </a>
          </li>
          <li>
            <a href="#">
              <aside class="icon icon-callout">
                asidecall
              </aside>
              <p>Travis Gray <em>(2)</em></p>
              <p>
                <time datetime="17:43">5:43PM</time>
                Mobile
              </p>
            </a>
          </li>
        </ul>
      </section>
    </article>
  </section>

  <h4>Css link</h4>
  {% highlight html linenos=table %}<link href="(your styles folder)/style_unstable/lists.css" rel="stylesheet" type="text/css">{% endhighlight %}

  <h4>HTML code</h4>
  {% highlight html linenos=table %}
<section data-type="list">
  <header>Title</header>
  <ul>
    <li>
      <p>Travis Gray</p>
    </li>
    <li>
      <a href="#">
        <p>Travis Gray</p>
        <p>Clickable item</p>
      </a>
    </li>
    <li>
      <aside class="pack-end">
        <img alt="placeholder" src="myimage.jpg">
      </aside>
      <a href="#">
        <p>Travis Gray</p>
        <p>Beginning of message</p>
      </a>
    </li>
  </ul>
  <header>Another title</header>
  <ul>
    <li aria-disabled="true">
      <aside class="pack-end">
        <img alt="placeholder" src="myimage.jpg">
      </aside>
      <a href="#">
        <p>Travis Gray</p>
        <p>Disabled item</p>
      </a>
    </li>
    <li>
      <a href="#">
        <aside class="icon icon-callout">
          asidecall
        </aside>
        <p>Travis Gray <em>(2)</em></p>
        <p>
          <time datetime="17:43">5:43PM</time>
          Mobile
        </p>
      </a>
    </li>
  </ul>
</section>{% endhighlight %}
</div>

<hr>

### Edit mode

<div>
  <h4>Example</h4>
  <section class="example">
    <img src="../images/BB/lists_2.png" alt="Lists (Image replacing code)"/>
    <article class="frame">
      <section data-type="list">
        <ul data-type="edit">
          <li>
            <label class="pack-checkbox danger">
              <input type="checkbox">
              <span></span>
            </label>
            <aside class="pack-end">
              <img alt="placeholder" src="myimage.jpg">
            </aside>
            <a href="#">
              <p>Travis Gray</p>
              <p>Beginning of message</p>
            </a>
          </li>
          <li>
            <label class="pack-checkbox danger">
              <input type="checkbox">
              <span></span>
            </label>
            <a href="#">
              <aside class="icon icon-callout"></aside>
              <p>Travis Gray <em>(2)</em></p>
              <p>
                <time datetime="17:43">5:43PM</time>
                Mobile
              </p>
            </a>
          </li>
        </ul>
      </section>
    </article>
  </section>

  <h4>Css link</h4>
  {% highlight html linenos=table %}<link href="(your styles folder)/style_unstable/lists.css" rel="stylesheet" type="text/css">{% endhighlight %}

  <h4>HTML code</h4>
  {% highlight html linenos=table %}
<section data-type="list">
  <ul data-type="edit">
    <li>
      <label class="pack-checkbox danger">
        <input type="checkbox">
        <span></span>
      </label>
      <aside class="pack-end">
        <img alt="placeholder" src="myimage.jpg">
      </aside>
      <a href="#">
        <p>Travis Gray</p>
        <p>Beginning of message</p>
      </a>
    </li>
    <li>
      <label class="pack-checkbox danger">
        <input type="checkbox">
        <span></span>
      </label>
      <a href="#">
        <aside class="icon icon-callout"></aside>
        <p>Travis Gray <em>(2)</em></p>
        <p>
          <time datetime="17:43">5:43PM</time>
          Mobile
        </p>
      </a>
    </li>
  </ul>
</section>{% endhighlight %}
</div>

