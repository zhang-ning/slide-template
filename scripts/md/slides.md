title: 我的技术分享
subtitle: 小猫小狗的故事
class: image

![Mobile vs desktop users](images/barchart.png)

---

title: Jonathan Slide
subtitle: Subtitle
class: segue dark nobackground

---

title: Agenda
class: big
build_lists: true

Things we'll cover (list should build):

- Bullet1
- Bullet2
- Bullet3

---

title: Today
class: nobackground fill
content_class: flexbox vcenter

![Mobile vs desktop users](images/barchart.png)

<footer class="source">source: place source info here</footer>

---

title: Big Title Slide
class: title-slide

---

title: Code Example

Media Queries are sweet:

<pre class="prettyprint" data-lang="css">
@media screen and (max-width: 640px) {
  #sidebar { display: none; }
}
</pre>

---

title: Once more, with JavaScript

<pre class="prettyprint" data-lang="javascript">
function isSmall() {
  return window.matchMedia("(min-device-width: ???)").matches;
}

function hasTouch() {
  return Modernizr.touch;
}

function detectFormFactor() {
  var device = DESKTOP;
  if (hasTouch()) {
    device = isSmall() ? PHONE : TABLET;
  }
  return device;
}
</pre>

---

title: another new page
build_lists: true

### aasdf

- what do you want to do 
- and tehn
- go on
- to do.

---

title: Centered content
content_class: flexbox vcenter

This content should be centered!
