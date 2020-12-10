# html-web
<style>
        body {
            border: 3px solid black;
            padding: 35px;
            margin: 50px;
        }
        
        P.no {
            background-color: RED;
        }
        
        p.may {
            font-style: italic;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: cadetblue;
        }
        
        a:link,
        a:visited {
            color: white;
            text-align: center;
            text-decoration: none;
            background-color: blue;
            padding: 0px 0px;
            display: inline-block
        }
        
        a:hover,
        a:active {
            background-color: blueviolet;
        }
    </style>
</head>

<body style="background-image: url('IMG_20200412_094614_425_1586681390537.jpg'); background-size:cover;">
    <A HREF="#VOO"></A>
    <p title='How to cook eguisi'> Below is how to cook eguisi soup.</p>
    <strong>This is a strong text</strong> and <br /> <b>This is a bold text</b> <br /> <i>This is an italicized text</i>
    <br/><em>this is an emphasized text</em>
    <p class="no may"> i want <mark title='peanut butter'>peanut butter</mark> for my bread</p>
    my fav color is <ins>red</ins>
    <p>Here is a quote from WWF's website:</p><br>
    <p id=voo>THE CITE</p>
    <form>
        <label for=" fname ">First name:</label>
        <input type="text " id="fname " name="fname "><br><br>
        <label for="lname ">Last name:</label>
        <input type="text " id="lname " name="lname "><br><br>
        <input type="image " src="img_submit.gif " alt="Submit " width="48 " height="48 ">
    </form>

    </form>
    <form action="/action_page.php " oninput="x.value=parseInt(a.value)+parseInt(b.value) ">

        <input type="range " id="a " name="a " value="20 "> 300 +
        <input type="number " id="b " name="b " value="50 "> =
        <output name="x " for="a b "></output>
        <br><br>
        <input type="submit ">
    </form>

    <select name="cars " size="4 " multiple>cars
    <option value="volvo ">volvo</option>
    <option  value="toyota " selected>toyota</option>
    <option value="camry">camry</option>
    <option value="Nissan">Nissan</option>
    <option value="Chevrolet ">chevrolet</option></select>
    <form action="/action_page.php ">
        <input list="browsers ">
        <datalist id="browsers ">
        <option value="Internet Explorer ">
            <option value="Firefox ">
                <option value="Chrome ">
                    <option value="Opera ">
                        <option value="Safari ">
                            </datalist>
    </form>

    <blockquote cite="http://www.worldwildlife.org/who/index.html ">
        For 50 years, WWF has been protecting the future of nature. The world's leading conservation organization, WWF works in 100 countries and is supported by 1.2 million members in the United States and close to 5 million globally.
    </blockquote>
    <p>lit of</p>
    <bdo dir="rtl ">&#128525 I love to read</bdo> <address> Written by John Doe. Visit us at: Example.com Box 564, Disneyland USA
    </address>
    <p><cite>The Scream</cite> by Edvard Munch. Painted in 1893.</p>
    <a href="mailto:dikacjinwankwo@gmail.com ">SUBMIT</a>
    <button onclick="document.location='default.asp' ">HTML Tutorial</button>
    </style>
    <H3 STYLE="font-size: 48px; ">&#128516</H3>
    <form>
        <input type="radio " id="radio " name="gender " />
        <label for="male ">Male</label><br>
        <input type="radio " id="female " name="gender ">
        <label for="female ">Female</label><br>
        <input type="radio " id="other " name="gender ">
        <label for="other ">Other</label>
        <input type="submit " name="submit " />
    </form>

    <table>
        <tr>
            <th>NAME</th>
            <Td>Cindi</Td>
            <Td>James</Td>
        </tr>
        <TR>
            <TH>CLASS</TH>
            <td rowspan="2 ">A</td>
            <td></td>

        </TR>
        <TR>
            <Th>age</Th>

            <Td>8</Td>
        </TR>
        <style>
            TABLE {
                WIDTH: 100%;
                background-color: brown;
            }
            
            table,
            th,
            td {
                border: 1px solid black;
                border-collapse: collapse;
            }
            
            table {
                border-spacing: 5px;
            }
        </style>

    </table>

</body>
