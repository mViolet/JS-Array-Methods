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
<p>Array.prototype.Map() returns a new array, with each element of that array modified based on a function that you pass into it.</p>
<p>Parameters accepted: a function which can accept the following elements as parameters:</p>
<ul>
<li>the current element of the array (required)</li>
<li>the index of the current element</li>
<li>the array that map was called on</li>
<li>a value to use as <code>this</code> when calling the callback function</li>
</ul>
<p>Basic usage:<br>
<code>someArray.Map(el =&gt; //return statement)</code></p>
<p>Some examples:</p>
<pre><code>const arr = ['Apple', 'Peach', 'Orange']
console.log(arr.map(el =&gt; el + '!'))
// Prints [ "Apple!", "Peach!", "Orange!" ]
</code></pre>
<pre><code>const arr = ['Apple', 'Peach', 'Orange']
console.log(arr.map((el, i) =&gt; i))
// Prints [ 0, 1, 2 ]
</code></pre>
<pre><code>const arr = ['Apple', 'Peach', 'Orange']
console.log(arr.map((el, i) =&gt; {
    return (i % 2 === 0) ? el.toUpperCase() : el
}))
// Prints [ "APPLE", "Peach", "ORANGE" ]
</code></pre>
<p><a href="#list-of-array-methods">Back to the list</a></p>
<h2 id="reduce">Reduce</h2>
<p>Array.prototype.Map() returns a new array, with each element of that array modified based on a function that you pass into it.</p>
<p>Parameters accepted:</p>
<ul>
<li>asdasd</li>
<li>asda</li>
<li>asd</li>
<li>asda</li>
</ul>
<p>Basic usage:<br>
<code>someArray.Reduce((acc, curr) =&gt; acc + curr, 0)</code></p>
<p>Some examples:</p>
<pre><code>some code
</code></pre>
<pre><code>some code
</code></pre>
<pre><code>// some code
</code></pre>
<p><a href="#list-of-array-methods">Back to the list</a></p>
<h2 id="filter">Filter</h2>
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

