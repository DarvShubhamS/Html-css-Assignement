# Html-css-Assignement

## Q1.How are inline and block elements different from each other?
Main Difference between inline and block elements is that 

### In Inline Elements

•	**inline elements**  take only the required width of page also margin-top and margin-bottom have no effect on inline elements 

•	some examples are span, img, a, button tags.

### whereas In Block Elements,

•	**block elements** take the full width of the page irrespective of the space taken by the contents.

•	Some examples are div, section, header, footer tags.



## Q2.Explain the difference between visibility:hidden and display:none

Main Difference between two is that in,

•	**visibility set to hidden**, it will affect the document flow. Space will be allocated to that particular element between different elements.

•	**And in Display set to none**, it will not affect the document flow. no space will be allocated to it in the document flow.

## Q3.Explain the clear and float properties

-> **Float property** is used to float or we can say position a particular element in specified direction.

we have different types of float properties like left , right , none .

- none:	 The element does not float
- left:  The element floats to the left of its container
- right: The element floats the right of its containe

syntax: `div {
float:left
}`

-> **Clear property** is used to basically specify on which side the floating elements are not allowed.

we have different types of float properties like left , right , none , both.

- none : Allows floating elements on both sides. This is default
- left : No floating elements allowed on the left side
- right: No floating elements allowed on the right side
- both : No floating elements allowed on either the left or the right side

syntax: `div {
clear:left
}`

## Q4.explain difference between absolute, relative,fixed and static.

- Static: - It is the default property set. Elements appear in their normal flow as they are written in html document.

- Relative: - by setting relative, the elements basically move corresponding from its current position.

- Absolute: - by setting display property to absolute than the positioning of element will be relative to its first parent element. According to its parent elements it will change the positioning

- Fixed: - by setting the display property to fix, it will be fixed to a particular position. Fixed elements are relative to browser window. 

##  Q5.Write the HTML code to create a table in which there are 4 columns( ID , Employee Name, Designation, Department) and at least 6 rows. Also do some styling to it.

    <table>
            <tr>
                <th>ID</th>
                <th>Employee Name</th>
                <th>Designation</th>
                <th>Department</th>
            </tr>
            <tr>
                <td>1</td>
                <td>e1</td>
                <td>d1</td>
                <td>d1</td>
            </tr>

            <tr>
                <td>2</td>
                <td>e2</td>
                <td>d2</td>
                <td>d2</td>
            </tr>

            <tr>
                <td>3</td>
                <td>e3</td>
                <td>d3</td>
                <td>d3</td>
            </tr>

            <tr>
                <td>4</td>
                <td>e4</td>
                <td>d4</td>
                <td>d4</td>
            </tr>

            <tr>
                <td>5</td>
                <td>e5</td>
                <td>d5</td>
                <td>d5</td>
            </tr>

            <tr>
                <td>6</td>
                <td>e6</td>
                <td>d6</td>
                <td>d6</td>
            </tr>

        </table>
        
 ## Q6. Why do we use meta tags?
 
- Meta tags basically used to define metadata about an html document. 
- Meta tags are used inside the head tag of html documents.
- Each meta data serves different purpose like specifying page description, author name, list of keywords etc.
We have different types of meta tags like:

1.	`<meta name="keywords" content="HTML, CSS, XML, XHTML, JavaScript">` (For Search engines)

2.	`<meta name="description" content="Free Web tutorials on HTML and CSS">` (Description of web page)

3.	`<meta name="author" content="Shubham Saxena">` (Author of web page)

4.	`<meta name="viewport" content="width=device-width, initial-scale=1.0">` (Responsiveness)


## Q7. Explain box model. 

Every element in a html is a box. We can consider all html elements as boxes.

•	Innermost box is content of that particular html element. whatever we right inside our html tags like in `<p> content </p>` , is our content.

•	Outside the content and inside our border, the area/space or we can say box surrounding is named as padding.

•	Now outside the padding, but inside the margin the area surrounding is termed as the border.

•	The outermost box, which is above the border is known as margin. 

<img src="https://www.washington.edu/accesscomputing/webd2/student/unit3/images/boxmodel.gif" />


Keeping Box Model In Mind we apply styling to our html pages.

## Q8.What are the different types of CSS Selectors? 

# Html-css-Assignement

## Q1.How are inline and block elements different from each other?
Main Difference between inline and block elements is that 

### In Inline Elements

•	**inline elements**  take only the required width of page also margin-top and margin-bottom have no effect on inline elements 

•	some examples are span, img, a, button tags.

### whereas In Block Elements,

•	**block elements** take the full width of the page irrespective of the space taken by the contents.

•	Some examples are div, section, header, footer tags.



## Q2.Explain the difference between visibility:hidden and display:none

Main Difference between two is that in,

•	**visibility set to hidden**, it will affect the document flow. Space will be allocated to that particular element between different elements.

•	**And in Display set to none**, it will not affect the document flow. no space will be allocated to it in the document flow.

## Q3.Explain the clear and float properties

-> **Float property** is used to float or we can say position a particular element in specified direction.

we have different types of float properties like left , right , none .

- none:	 The element does not float
- left:  The element floats to the left of its container
- right: The element floats the right of its containe

syntax: `div {
float:left
}`

-> **Clear property** is used to basically specify on which side the floating elements are not allowed.

we have different types of float properties like left , right , none , both.

- none : Allows floating elements on both sides. This is default
- left : No floating elements allowed on the left side
- right: No floating elements allowed on the right side
- both : No floating elements allowed on either the left or the right side

syntax: `div {
clear:left
}`

## Q4.explain difference between absolute, relative,fixed and static.

- Static: - It is the default property set. Elements appear in their normal flow as they are written in html document.

- Relative: - by setting relative, the elements basically move corresponding from its current position.

- Absolute: - by setting display property to absolute than the positioning of element will be relative to its first parent element. According to its parent elements it will change the positioning

- Fixed: - by setting the display property to fix, it will be fixed to a particular position. Fixed elements are relative to browser window. 

##  Q5.Write the HTML code to create a table in which there are 4 columns( ID , Employee Name, Designation, Department) and at least 6 rows. Also do some styling to it.

    <table>
            <tr>
                <th>ID</th>
                <th>Employee Name</th>
                <th>Designation</th>
                <th>Department</th>
            </tr>
            <tr>
                <td>1</td>
                <td>e1</td>
                <td>d1</td>
                <td>d1</td>
            </tr>

            <tr>
                <td>2</td>
                <td>e2</td>
                <td>d2</td>
                <td>d2</td>
            </tr>

            <tr>
                <td>3</td>
                <td>e3</td>
                <td>d3</td>
                <td>d3</td>
            </tr>

            <tr>
                <td>4</td>
                <td>e4</td>
                <td>d4</td>
                <td>d4</td>
            </tr>

            <tr>
                <td>5</td>
                <td>e5</td>
                <td>d5</td>
                <td>d5</td>
            </tr>

            <tr>
                <td>6</td>
                <td>e6</td>
                <td>d6</td>
                <td>d6</td>
            </tr>

        </table>
        
 ## Q6. Why do we use meta tags?
 
- Meta tags basically used to define metadata about an html document. 
- Meta tags are used inside the head tag of html documents.
- Each meta data serves different purpose like specifying page description, author name, list of keywords etc.
We have different types of meta tags like:

1.	`<meta name="keywords" content="HTML, CSS, XML, XHTML, JavaScript">` (For Search engines)

2.	`<meta name="description" content="Free Web tutorials on HTML and CSS">` (Description of web page)

3.	`<meta name="author" content="Shubham Saxena">` (Author of web page)

4.	`<meta name="viewport" content="width=device-width, initial-scale=1.0">` (Responsiveness)


## Q7. Explain box model. 

Every element in a html is a box. We can consider all html elements as boxes.

•	Innermost box is content of that particular html element. whatever we right inside our html tags like in `<p> content </p>` , is our content.

•	Outside the content and inside our border, the area/space or we can say box surrounding is named as padding.

•	Now outside the padding, but inside the margin the area surrounding is termed as the border.

•	The outermost box, which is above the border is known as margin. 

<img src="https://www.washington.edu/accesscomputing/webd2/student/unit3/images/boxmodel.gif" />

Keeping Box Model In Mind we apply styling to our html pages.








