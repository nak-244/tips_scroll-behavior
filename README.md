# CSSだけでスムーススクロールを実装できる

CSSだけでスムーススクロールを実装するにはscroll-behaviorプロパティを使用。  
scroll-behaviorプロパティとはページ内スクロールする要素のスクロールの振る舞いを決めるもので、初期値はautoとなっております。  
スムーススクロールさせるにはautoではなくsmoothを指定してあげます。

```css:スムーススクロール
html{
  scroll-behavior: smooth;
}
```
