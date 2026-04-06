# htmlcss
hello
	Basic Tags
Element	Description	Example Snippet
<html></html>	Defines the root of an HTML document	<html> ... </html>
<head></head>	Contains meta-information about the document	<head> ... </head>
<body></body>	Contains the content of an HTML document	<body> ... </body>
<title></title>	Sets the title of the webpage, shown in the browser tab	<title>Bookshop Home</title>

Text Tags
Element	Description	Example Snippet
<pre></pre>	Preformatted text	<pre>New Arrivals\nSpecial Offers\nBestsellers</pre>
<h1></h1>	Defines HTML headings (h1 to h6)	<h1>Welcome to Book Haven</h1>
<strong></strong>	Bold text	<strong>Exclusive Sale</strong>
<em></em>	Emphasized text (italic)	<em>Must-read Classics</em>
<tt></tt>	Monospaced teletype text	<tt>ISBN: 978-3-16-148410-0</tt>
<code></code>	Computer code text	<code>alert("Welcome to our bookstore!");</code>
<cite></cite>	Cited work	<cite>by Jane Austen</cite>
<address></address>	Contact information	<address>123 Book St., Bibliopolis, BK 12345</address>

Links
Element	Description	Example Snippet
<a href="URL">clickable text</a>	Hyperlink to a URL	<a href="https://bookhaven.com">Visit Our Store</a>
<a href="mailto:EMAIL_ADDRESS">clickable text</a>	Email link	<a href="mailto:info@bookhaven.com">Contact Us</a>
<a name="NAME"></a>	Anchor in the page	<a name="section1"></a>
<a href="#NAME">clickable text</a>	Link to an anchor	<a href="#section1">Learn More</a>

Formatting
Element	Description	Example Snippet
<p></p>	Paragraph	<p>Welcome to our online bookshop where you can find a wide selection of books.</p>
<br>	Line break	Line 1<br>Line 2
<blockquote></blockquote>	Block quotation	<blockquote>"Reading is to the mind what exercise is to the body." - Joseph Addison</blockquote>
<div></div>	Division or section in an HTML document	<div class="bestsellers">Our Bestsellers</div>
<span></span>	Inline container for text	<span class="highlight">Special Offer</span>

Lists
Element	Description	Example Snippet
<ul></ul>	Unordered list	<ul><li>Fiction</li><li>Non-Fiction</li><li>Children's Books</li></ul>
<ol start="?></ol>	Ordered list with start attribute	<ol start="2"><li>Second Item</li><li>Third Item</li></ol>
<li></li>	List item	<li>New Release</li>
<dl></dl>	Description list	<dl><dt>Author</dt><dd>J.K. Rowling</dd></dl>

Graphics
Element	Description	Example Snippet
<hr>	Horizontal rule	<hr>
<hr size=?>	Horizontal rule with size attribute	<hr size="5">
<hr width=?>	Horizontal rule with width attribute	<hr width="50%">
<hr noshade>	Horizontal rule without shading	<hr noshade>
<img src="URL" />	Embeds an image with a source URL	<img src="cover.jpg">
<img src="URL" align=?>	Aligns the image relatively	<img src="cover.jpg" align="left">
<img src="URL" border=?>	Sets border width around the image	<img src="cover.jpg" border="1">
<img src="URL" height=?>	Sets height of the image	<img src="cover.jpg" height="200">
<img src="URL" width=?>	Sets width of the image	<img src="cover.jpg" width="150">
<img src="URL" alt=?>	Provides alternative text for the image	<img src="cover.jpg" alt="Book Cover">

Forms
Element	Description	Example Snippet
<form></form>	Form element	<form action="/submit_form">...</form>
<select multiple name=? size=?></select>	Dropdown list with multiple selections	<select multiple name="genres" size="5">...</select>
<select name=?></select>	Dropdown list	<select name="genre">...</select>
<option>	Option within a dropdown list	<option>Fiction</option>
<textarea name=? cols="x" rows="y"></textarea>	Multiline text input	<textarea name="review" cols="30" rows="10"></textarea>
<input type="checkbox" name=? value=?>	Checkbox input	<input type="checkbox" name="newsletter" value="subscribe">
<input type="checkbox" name=? value=? checked>	Pre-checked checkbox	<input type="checkbox" name="newsletter" value="subscribe" checked>
<input type="text" name=? size=?>	Single-line text input	<input type="text" name="name" size="20">
<input type="submit" value=?>	Submit button	<input type="submit" value="Submit Review">
<input type="reset">	Reset button	<input type="reset">

Tables
Element	Description	Example Snippet
<table></table>	Table element	<table>...</table>
<tr></tr>	Table row	<tr>...</tr>
<td></td>	Table data cell	<td>Price</td>
<th></th>	Table header cell	<th>Book Title</th>

Video
Element	Description	Example Snippet
<video></video>	Video embedding	<video controls> <source src="promo.mp4" type="video/mp4"> </video>
<source>	Media source	<source src="promo.mp4" type="video/mp4">
<track>	Text tracks for video	<track kind="subtitles" src="subtitles.vtt" srclang="en">