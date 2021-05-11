---


---

<h1 id="array-methods-in-javascript">Array Methods in JavaScript</h1>
<p>Here is a rundown of some useful array methods in JavaScript. Each method listed below will include the following:</p>
<ul>
<li>A description of what it does</li>
<li>Brief explanation of how it works</li>
<li>Time complexity (if appropriate)</li>
<li>three code examples</li>
</ul>
<p>Here is a list of all the methods I will cover, in case you want to jump to a particular section!</p>
<h3 id="list-of-array-methods">List of Array Methods</h3>
<p><a href="#map">Map</a><br>
<a href="#reduce">Reduce</a><br>
<a href="#filter">Filter</a><br>
<a href="#foreach">ForEach</a><br>
<a href="#sort">Sort</a><br>
<a href="#slice">Slice</a><br>
<a href="#pop">Pop</a><br>
<a href="#shift">Shift</a><br>
<a href="#push">Push</a><br>
<a href="#unshift">Unshift</a><br>
<a href="#includes">Includes</a><br>
<a href="#indexof">IndexOf</a><br>
<a href="#every">Every</a></p>
<h2 id="map">Map</h2>
<p>Array.prototype.map() returns a new array, with each element of that array modified based on a function that you pass into it.<br>
Map is not destructive to the original array.</p>
<p>Parameters accepted: a function which can accept the following elements as parameters:</p>
<ul>
<li>the current element of the array (required)</li>
<li>the index of the current element</li>
<li>the array that map was called on</li>
<li>a value to use as <code>this</code> when calling the callback function</li>
</ul>
<p>Basic usage:<br>
<code>someArray.map(el =&gt; //return statement)</code></p>
<p>Some examples:</p>
<pre><code>const arr = ['Apple', 'Peach', 'Orange']
arr.map(el =&gt; el + '!')

// returns [ "Apple!", "Peach!", "Orange!" ]
</code></pre>
<pre><code>const arr = ['Apple', 'Peach', 'Orange']
arr.map((el, i) =&gt; i)

// returns [ 0, 1, 2 ]
</code></pre>
<pre><code>const arr = ['Apple', 'Peach', 'Orange']
arr.map((el, i) =&gt; {
    return (i % 2 === 0) ? el.toUpperCase() : el
})

// returns [ "APPLE", "Peach", "ORANGE" ]
</code></pre>
<p><a href="#list-of-array-methods">Back to the list</a></p>
<h2 id="reduce">Reduce</h2>
<p>Array.prototype.reduce() uses something called a reducer function, which is called on the array that reduce is called on. What happens is the array is eventually reduced to one value, which becomes the return value of .reduce()!<br>
Reduce is unique in that it also takes in a special (optional) initial value to kick off the .reduce() function.<br>
Reduce will not affect the original array.</p>
<p>Parameters accepted: The reducer function is passed to reduce, and can take four arguments:</p>
<ul>
<li>the accumulator (required)</li>
<li>the current value (required)</li>
<li>the current index</li>
<li>the array that .reduce() was called on<br>
Don’t forget - .reduce() can also take an optional initial value.</li>
</ul>
<p>Basic usage:<br>
<code>someArray.reduce(reducerFunction, initialValue)</code><br>
or<br>
<code>someArray.reduce((acc, curr) =&gt; acc + curr, 0)</code></p>
<p>Some examples:</p>
<pre><code>const arr = [1,2,3,4,5]
arr.reduce((a, b) =&gt; a + b)

// returns 15
</code></pre>
<pre><code>const arr = ['1','2','3','4','5'] arr.reduce((a, b) =&gt; a + b)  

// returns "12345"
</code></pre>
<pre><code>const arr = ['1','2','3','4','5'] arr.reduce((a, b) =&gt; a - b, 15)

// returns 0
</code></pre>
<p><a href="#list-of-array-methods">Back to the list</a></p>
<h2 id="filter">Filter</h2>
<p>Array.prototype.filter() will ‘filter’ an array based on a function that is passed into it. The function checks each element of the array, and the elements that pass the test will be returned in a new array!<br>
Filter is not destructive to the original array.</p>
<p>Parameters accepted: .filter() takes in a function which itself can take up to four parameters.</p>
<ul>
<li>the current element (required)</li>
<li>index of the current element</li>
<li>the array that .fliter() was called on</li>
<li>a value to use as <code>this</code> when the function is called</li>
</ul>
<p>Basic usage:<br>
<code>someArray.filter(el =&gt; callbackFunction)</code></p>
<p>Some examples:</p>
<pre><code>const arr = [1,2,3,4,5,6,7,8]
arr.filter(el =&gt; el % 2 === 0)  

//returns [ 2, 4, 6, 8 ]
</code></pre>
<pre><code>const arr = ['short', 'sesquipedalian', 'words', 'obsequious', 'only']
arr.filter(el =&gt; el.length &lt; 6) //returns [ 2, 4, 6, 8 ]  

//returns [ "short", "words", "only" ]
</code></pre>
<pre><code>const arr = ['foo', 'bar', 'buzz', 'bat', 'hello']
arr.filter((el, i) =&gt; i % 2 === 0)  

// returns even index items only: [ "foo", "buzz", "hello" ]
</code></pre>
<p><a href="#list-of-array-methods">Back to the list</a></p>
<h2 id="foreach">forEach</h2>
<p>Array.prototype.Method() does xyz…</p>
<p>Parameters accepted:</p>
<ul>
<li>thing</li>
<li>thing</li>
<li>thing</li>
</ul>
<p>Basic usage:<br>
<code>someArray.Method()</code></p>
<p>Some examples:</p>
<pre><code>some code
</code></pre>
<pre><code>some code
</code></pre>
<pre><code>// some code
</code></pre>
<p><a href="#list-of-array-methods">Back to the list</a></p>
<h2 id="sort">Sort</h2>
<p>Array.prototype.Method() does xyz…</p>
<p>Parameters accepted:</p>
<ul>
<li>thing</li>
<li>thing</li>
<li>thing</li>
</ul>
<p>Basic usage:<br>
<code>someArray.Method()</code></p>
<p>Some examples:</p>
<pre><code>some code
</code></pre>
<pre><code>some code
</code></pre>
<pre><code>// some code
</code></pre>
<p><a href="#list-of-array-methods">Back to the list</a></p>
<h2 id="slice">Slice</h2>
<p>Array.prototype.Method() does xyz…</p>
<p>Parameters accepted:</p>
<ul>
<li>thing</li>
<li>thing</li>
<li>thing</li>
</ul>
<p>Basic usage:<br>
<code>someArray.Method()</code></p>
<p>Some examples:</p>
<pre><code>some code
</code></pre>
<pre><code>some code
</code></pre>
<pre><code>// some code
</code></pre>
<p><a href="#list-of-array-methods">Back to the list</a></p>
<h2 id="pop">Pop</h2>
<p>Array.prototype.Method() does xyz…</p>
<p>Parameters accepted:</p>
<ul>
<li>thing</li>
<li>thing</li>
<li>thing</li>
</ul>
<p>Basic usage:<br>
<code>someArray.Method()</code></p>
<p>Some examples:</p>
<pre><code>some code
</code></pre>
<pre><code>some code
</code></pre>
<pre><code>// some code
</code></pre>
<p><a href="#list-of-array-methods">Back to the list</a></p>
<h2 id="shift">Shift</h2>
<p>Array.prototype.Method() does xyz…</p>
<p>Parameters accepted:</p>
<ul>
<li>thing</li>
<li>thing</li>
<li>thing</li>
</ul>
<p>Basic usage:<br>
<code>someArray.Method()</code></p>
<p>Some examples:</p>
<pre><code>some code
</code></pre>
<pre><code>some code
</code></pre>
<pre><code>// some code
</code></pre>
<p><a href="#list-of-array-methods">Back to the list</a></p>
<h2 id="push">Push</h2>
<p>Array.prototype.Method() does xyz…</p>
<p>Parameters accepted:</p>
<ul>
<li>thing</li>
<li>thing</li>
<li>thing</li>
</ul>
<p>Basic usage:<br>
<code>someArray.Method()</code></p>
<p>Some examples:</p>
<pre><code>some code
</code></pre>
<pre><code>some code
</code></pre>
<pre><code>// some code
</code></pre>
<p><a href="#list-of-array-methods">Back to the list</a></p>
<h2 id="unshift">Unshift</h2>
<p>Array.prototype.Method() does xyz…</p>
<p>Parameters accepted:</p>
<ul>
<li>thing</li>
<li>thing</li>
<li>thing</li>
</ul>
<p>Basic usage:<br>
<code>someArray.Method()</code></p>
<p>Some examples:</p>
<pre><code>some code
</code></pre>
<pre><code>some code
</code></pre>
<pre><code>// some code
</code></pre>
<p><a href="#list-of-array-methods">Back to the list</a></p>
<h2 id="includes">Includes</h2>
<p>Array.prototype.Method() does xyz…</p>
<p>Parameters accepted:</p>
<ul>
<li>thing</li>
<li>thing</li>
<li>thing</li>
</ul>
<p>Basic usage:<br>
<code>someArray.Method()</code></p>
<p>Some examples:</p>
<pre><code>some code
</code></pre>
<pre><code>some code
</code></pre>
<pre><code>// some code
</code></pre>
<p><a href="#list-of-array-methods">Back to the list</a></p>
<h2 id="indexof">IndexOf</h2>
<p>Array.prototype.Method() does xyz…</p>
<p>Parameters accepted:</p>
<ul>
<li>thing</li>
<li>thing</li>
<li>thing</li>
</ul>
<p>Basic usage:<br>
<code>someArray.Method()</code></p>
<p>Some examples:</p>
<pre><code>some code
</code></pre>
<pre><code>some code
</code></pre>
<pre><code>// some code
</code></pre>
<p><a href="#list-of-array-methods">Back to the list</a></p>
<h2 id="every">Every</h2>
<p>Array.prototype.Method() does xyz…</p>
<p>Parameters accepted:</p>
<ul>
<li>thing</li>
<li>thing</li>
<li>thing</li>
</ul>
<p>Basic usage:<br>
<code>someArray.Method()</code></p>
<p>Some examples:</p>
<pre><code>some code
</code></pre>
<pre><code>some code
</code></pre>
<pre><code>// some code
</code></pre>
<p><a href="#list-of-array-methods">Back to the list</a></p>

