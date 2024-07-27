//Target attribute

1. in HTML <link> target attribute is used to specify the window and frame where linked documented is loaded
2. It is not support by HTML5
3. syntax

    <link target="value">
Here target is attribute and they have some value like below:
1. _black: it opens the link in new window
2. _self : it is default value. it opens the linked document in the same frame
3. _parent : it opens the linked document in the parent frameset
4. _top : it opens the linked document in the fully body of the window.
5. framename: It opens the linked document in the named frame

//Storage

1. In HTML5 , Web storage is more secure and large amount of data can be store locally on client -side web browser

2. All data store in web like key and value pair

3. HTML5 support two type of web storage API
    local storage and session storage

// Local  storage

1. It is used to store data on the client side.
2. it has no time limit , so the data in th local storage we can store longer
3. If user want to delete it then it will delete otherwise store longer
4. Set local storage value ==> localStorage.setItem("key","value");
5 get localStorage value ==> localStorage.getItem("key");

//Session storage

1. Session is also use to store data client side.
2. Data in the sessionStorage exit till the current tab open.
3. if we close the current tab then our data will automatically erase from sessionStorage
4. Set value in sessionStorage ==> SessionStorage.setItem("key", "value");
5. get value in sessionStorage ==> SessionStorage.getItem("key");


//Drag and Drop

1. Drag and Drop is a feature of HTML5
2. It is powerful feature in HTML5 with the help of we can easily do some operation like copy, delete and reorder with help of mouse.

// HTML5 media element

<audio> - Used for sounds, audio streams, or music, embed audio content without any additional plug-in.

<video> - Used for video streams, embed video content etc.

<source> - Used for multiple media resources in media elements, such as audio, video, etc.

<embed> - Used for an external application or embedded content.

<track> - Used for subtitles in the media elements such as video or audio.

//Difference between svg and canvas

/SVG

1. It is vector based
2. Svg work better for  a large surface
3. Svg can be modified using css and scripts
4. SVG is highly scalable. So we can print at high quality with high resolution. 

/ canvas

1. It is Raster based
2. Canvas works better with a smaller surface.
3. Canvas can only be modified using scripts.
4. It is less scalable.

//Table

1. With help of Table we can arrange  data in tabular form like row and column.
2. For create table we need to use some tag in side table

Tags used in HTML Tables:

<table> => Defines the structure of table in row and column
<thead> ==> Define header section of table body.
<th> ==> Define header cell in table
<tbody> ==> Define body section of table

<tr> ==> Define row of table

<td> ==> Holding content or data.

<table >
        <thead>
              <tr>
            <th>Age</th>
        </tr>
        </thead>
        <tbody>

                <tr>
                    <td>24</td>
                </tr>
                <tr>
                    <td>32</td>
                </tr>
                <tr>
                    <td>41</td>
                </tr>
        </tbody>
             
</table>






