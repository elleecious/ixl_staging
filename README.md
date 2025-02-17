Task 1
Error and Solution

Issue:
  1. XML structure mistreatment, the <database> opening tag is not closed before <api> because the parser expects a closing tag <database> but finds another element (<api>)  to be seen, causing an XML parsing error.
  2. Not well-formed XML – The & character in John & Doe is not escaped correctly. The symbol & is reserved for defining entities in XML, so it must be replaced with & when, for example, when defining entity or other reserved words.
Fixes:
  1. Make sure to properly close <database> tag before starting <api> tag.
  2. Escape & character in John & Doe as John &amp; Doe.

Task 2:
  I placed it inside the <settings> tag close to the <logging> tag because debugging is tightly coupled with logging because debug mode generally impacts logging behavior. Hence, I keep it together with the <logging> tag close to the other configurations.

Task 3:
  1. I installed and set up the staging server using XAMPP
  2. I started the XAMPP control panel and added the application files inside the web root directory - "C:\xampp\htdocs\staging"
  3. Lastly, I tested the staging set by opening a browser and visiting "http://localhost/staging"
