Assessment

Task 1
Error and Solution

Issue:
  1. XML structure mistreatment, the &lt;database&gt; opening tag is not closed before <api> because the parser expects a closing tag &lt;database&gt; but finds another element (&lt;api&gt;)  to be seen, causing an XML parsing error.
  2. Not well-formed XML – The & character in John & Doe is not escaped correctly. The symbol & is reserved for defining entities in XML, so it must be replaced with & when, for example, when defining entity or other reserved words.
Fixes:
  1. Make sure to properly close &lt;database&gt; tag before starting &lt;api&gt; tag.
  2. Escape & character in John & Doe as John &amp ; Doe.

Task 2:
  I placed it inside the &lt;settings&gt; tag close to the &lt;logging&gt; tag because debugging is tightly coupled with logging because debug mode generally impacts logging behavior. Hence, I keep it together with the &lt;logging&gt; tag close to the other configurations.

Task 3:
  1. I installed and set up the staging server using XAMPP
  2. I started the XAMPP control panel and added the application files inside the web root directory - "C:\xampp\htdocs\staging"
  3. Lastly, I tested the staging set by opening a browser and visiting "http://localhost/staging"
