# table-formation
<!--hosted link -->
https://ajit7568.github.io/table-formation/ 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Table Formation</title>
</head>
<body oncontextmenu="return false;">
    <!-- Table for displaying images, links, and descriptions -->
    <table frame="box" rules="all" border="2" cellpadding="4" cellspacing="5">
        <!-- Table Header (First Row) -->
        <thead>
            <tr>
                <th>IMAGE</th>
                <th>VISIT LINK</th>
                <th>DESCRIPTION</th>
            </tr>
        </thead>
        <!-- Table Body (Data Rows) -->
        <tbody>
            <!-- Cars Section -->
            <tr>
                <th colspan="3">CARS</th>
            </tr>
            <tr>
                <!-- Image Column -->
                <td>
                    <img
                        width="200px"
                        height="150px"
                        src="https://vid.alarabiya.net/images/2023/04/12/2d220739-e6e3-4f4a-86f0-672691659959/2d220739-e6e3-4f4a-86f0-672691659959.jpg?crop=1:1&width=1000"
                        alt="car"
                    />
                </td>
                <!-- Description Column -->
                <td>
                    <p>
                        Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                        Aspernatur quidem voluptate repellat ratione nam. Ipsam nisi fugit a
                        dolorum. Quia, necessitatibus. Eos nulla maiores reiciendis.
                        Perspiciatis, officia, veniam maiores culpa modi adipisci nisi expedita
                        nobis nostrum recusandae amet. Accusantium animi nostrum consequuntur
                        similique illo commodi ullam asperiores blanditiis ducimus placeat!
                    </p>
                </td>
                <!-- Visit Link Column -->
                <td>
                    <a href="https://vid.alarabiya.net/images/2023/04/12/2d220739-e6e3-4f4a-86f0-672691659959/2d220739-e6e3-4f4a-86f0-672691659959.jpg?crop=1:1&width=1000"
                        >Link</a
                    >
                </td>
            </tr>
            <!-- Watches Section -->
            <tr>
                <th colspan="3">WATCHES</th>
            </tr>
            <tr>
                <!-- Image Column -->
                <td>
                    <img
                        width="200px"
                        height="150px"
                        src="https://www.fashionbeans.com/wp-content/uploads/2016/11/expensivewatchestop1.jpg"
                        alt="watch"
                    />
                </td>
                <!-- Description Column -->
                <td>
                    <p>
                        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aspernatur
                        quidem voluptate repellat ratione nam. Ipsam nisi fugit a dolorum.
                        Quia, necessitatibus. Eos nulla maiores reiciendis. Perspiciatis,
                        officia, veniam maiores culpa modi adipisci nisi expedita nobis
                        nostrum recusandae amet. Accusantium animi nostrum consequuntur
                        similique illo commodi ullam asperiores blanditiis ducimus placeat!
                    </p>
                </td>
                <!-- Visit Link Column -->
                <td>
                    <a href="https://www.fashionbeans.com/wp-content/uploads/2016/11/expensivewatchestop1.jpg"
                        >Link</a
                    >
                </td>
            </tr>
            <!-- Shoes Section -->
            <tr>
                <th colspan="3">Shoes</th>
            </tr>
            <tr>
                <!-- Image Column -->
                <td>
                    <img
                        width="200px"
                        height="150px"
                        src="https://www.inventiva.co.in/wp-content/uploads/2022/03/Top-35-Most-Expensive-Shoes-For-Men-Best-Luxury-Brands.jpg"
                        alt="shoes"
                    />
                </td>
                <!-- Description Column -->
                <td>
                    <p>
                        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aspernatur
                        quidem voluptate repellat ratione nam. Ipsam nisi fugit a dolorum.
                        Quia, necessitatibus. Eos nulla maiores reiciendis. Perspiciatis,
                        officia, veniam maiores culpa modi adipisci nisi expedita nobis
                        nostrum recusandae amet. Accusantium animi nostrum consequuntur
                        similique illo commodi ullam asperiores blanditiis ducimus placeat!
                    </p>
                </td>
                <!-- Visit Link Column -->
                <td>
                    <a href="https://www.pinkvilla.com/images/2023-02/1676613650_screenshot_20230217-112813_instagram.jpg"
                        >Link</a
                    >
                </td>
            </tr>
        </tbody>
    </table>
</body>
</html>
<!-- I have added comments to the HTML code to explain the purpose of each section and the role of different elements within the table, such as table header, data rows, and columns for images, links, and descriptions. This should help you understand the structure and content of the table formation.
<!DOCTYPE html>: This declaration specifies the document type and version (HTML5) of the document.
<html lang="en">: The <html> tag represents the root element of an HTML document. The lang attribute is used to declare the language of the document (in this case, English).
<head>: The <head> element contains meta-information about the document, such as character encoding, viewport settings, and the document's title.
<meta charset="UTF-8">: This meta tag specifies the character encoding for the document, which is UTF-8 (Unicode Transformation Format - 8-bit). It ensures proper handling of special characters and symbols.
<meta http-equiv="X-UA-Compatible" content="IE=edge">: This meta tag is used to define the compatibility mode for Internet Explorer (IE). In this case, it sets the mode to "edge," which means the latest version of IE should be used to render the page.<meta name="viewport" content="width=device-width, initial-scale=1.0">: This meta tag is used to control the layout and scaling of the web page on different devices. It ensures that the content fits the screen width and is initially scaled to 1.0 (no zooming).
<title>Table Formation</title>: The <title> element sets the title of the web page, which is displayed in the browser's title bar or tab.
<body oncontextmenu="return false;">: The <body> tag represents the content of the HTML document visible in the browser. The oncontextmenu attribute with the value "return false;" disables the right-click context menu on the page.
<table frame="box" rules="all" border="2" cellpadding="4" cellspacing="5">: This creates a table with a border (box frame) and specifies spacing and padding for cells. The rules="all" attribute adds inner grid lines to all table cells, and the border="2" attribute sets the border width to 2 pixels.
<thead>: The <thead> element defines the table header section, which contains header cells (<th> elements) describing the content of each column.
<tr>: The <tr> element represents a table row, and it contains table cells (<td> or <th> elements) representing the data in the table.
<th>: The <th> element defines a header cell within the table. It is used to display column or row headers.
<tbody>: The <tbody> element groups the table body content, which includes the data rows.
<td>: The <td> element represents a data cell within the table. It contains the actual content of the table cells.
<img>: The <img> tag is used to embed images in the web page. It has attributes like src (source URL of the image), alt (alternative text if the image cannot be displayed), width, and height (dimensions of the image).
<a>: The <a> element creates a hyperlink, allowing users to navigate to another web page or resource when clicked. It has an href attribute specifying the URL to link to.
<p>: The <p> element represents a paragraph of text.
<ul>: The <ul> element creates an unordered list, where each item is represented by an <li> (list item) element.
<ol>: The <ol> element creates an ordered list, where each item is represented by an <li> element.
<dl>: The <dl> element creates a description list, consisting of terms (<dt> elements) and their descriptions (<dd> elements).
<pre>: The <pre> element represents preformatted text, preserving white spaces and line breaks.
<h1>, <h2>, <h3>: These heading elements represent different levels of headings, with <h1> being the highest level and <h3> being the lowest level.
<b>, <i>: The <b> element is used to apply bold formatting to text, and the <i> element is used to apply italic formatting to text.
<hr>: The <hr> element creates a horizontal rule (a line) to visually separate content sections.-->
