# TheOdinProject | Recipes

## Live View
[Click here for my website's **live view**.](https://kmaneclang.github.io/odin-recipes/)

## Some gotchas I ran into
- When nesting lists, the inner list has to live **inside** a list entry of the outer list.
```html
  <ul>
    <!-- This is an ordinary list entry -->
    <li>Entry 1</li>

    <!-- This is a proper nested list entry -->
    <li>
      Entry 2, but also:
      <ul>
        <li>Entry 2.1</li>
        <li>Entry 2.2</li>
      </ul>
    </li>
  </ul>
```
- There is a proper format when multiple attributes wrap.
```html
  <img
    src="https://www.angsarap.net/wp-content/uploads/2015/11/Bulalo-Wide.jpg"
    width="600"
    alt="A photo of Bulalo, a Filipino dish"
  >
```
- Short content stays on one line, longer content gets wrapped into indented lines.
```html
  <p>This is an ordinary paragraph</p>
  <p>
    I probably shouldn't pay that much attention to style and formatting at this
    stage, but I guess it's better to start early than late.
  </p>
```

## Final thoughts
As a complete beginner, this was a fun little way to just get something out there.
As you can see, my website is very plain and I'm sure my code isn't perfect.
I still chose to showcase it to fellow learners though, because someone else might
read my code and catch a bug or point out some mistakes.
