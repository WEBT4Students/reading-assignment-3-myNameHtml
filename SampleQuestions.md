### IF.03.01 Basic Web Techniques
# Reading Assignment 1: Lists and Tables

## Html for Lists
1. Start tags for
   - an ordered list
   ``<ol>``
   - an unordered list
   ``<ul>``
   - a description list
   ``<dl>``
   - a list item
   ``<li>``
   - a description term
   ``<dt>``
   - a description data
   ``<dd>``

## Css for Lists
1. Make bullet a square
``list-style-type: disc;``
2. Make bullet an image named "my-bullet.png"
``list-style-image: url("my-bullet.png");``
3. Make bullet an uppercase roman number
``ist-style-type: upper-roman;``
4. Set bullet position to be inside the list item's text flow
``list-style-position: inside;``
5. Set bullet position to be outside the list item's text flow
``list-style-position: outside;``

## Html for Tables
1. Start tags for
   - a table
   ``<table>``
   - a table row
   ``<tr>``
   - a table header
   ``<theade>``
   - a table header cell
   &lt;tr&gt;
      &lt;th&gt; HEADER 1 &lt;/th>
      &lt;th&gt; HEADER 2 &lt;/th>
   &lt;/tr&gt;
   - a table body
   ``<tbody>``
   - a table cell
   ``<td>``
   - a table footer
   ``<tfoot>``
   - a table footer cell
   &lt;tfoot>
        &lt;tr>
            &lt;th scope="row">Totals</th>
            &lt;td>21,000</td>
        &lt;/tr>
   &lt;/tfoot>

## Css for Tables
1. Black dotted border of 1 px width.
``border: 1px dotted;``
2. Solid border of 1 px width having a red color and rounded corners
``border: 1px solid;``
``border-color: red;``
``border-color: red;``
``border-radius: 10px;``
3. Merge the borders of table cells so that they appear as one line
``border-collapse: collapse;``