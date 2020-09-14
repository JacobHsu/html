# link與@import

link與import , 本質使用上，我們都是用他來引入css，但是他們有一定的區別。

* link是一種引入資源的標籤，import是引入css的方式。所以，`import`引入的`只能是css`，而link可以引入所有的資源，包括圖片，RSS等。

* 加載順序上也有一些差異。link引用的CSS會同時被加載。`import`引用的CSS會等到頁面`全部被下載完再加載`。

* 兼容性的差別。link無任何兼容問題，import兼容IE5以上。

* 動態引入樣式link可以後期引入樣式，而`import`是`不可以後期引入`的，只能初始化頁面之前引入。

*  復用率的問題`import`可以`復用`之前的css文件，而link只能一次引用一個文件。當然，import復用文件時，在瀏覽器實際上是加載了多個文件，會有多個請求。而每一個link只是一個http請求。