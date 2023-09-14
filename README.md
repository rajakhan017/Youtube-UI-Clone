# Youtube-UI-Clone

## [Live Website Link!]https://rajakhan017.github.io/Youtube-UI-Clone/

### Structure of the web page
img src="./webpage.png" width="700px" alt="structure of the webpage"  />

---


#### \*

| Property     | Value        | Description                                                                                                                            |
| ------------ | ------------ | -------------------------------------------------------------------------------------------------------------------------------------- |
| `margin`     | `0`          | Set the margin for all elements to 0.                                                                                                  |
| `padding`    | `0`          | Set the padding for all elements to 0.                                                                                                 |
| `box-sizing` | `border-box` | Specify the box-sizing model as "border-box," which includes padding and borders in the element's total width and height calculations. |

**Selector Explanation:** The `*` selector targets all elements on the page.

#### .icons

| Property | Value     | Description                                                         |
| -------- | --------- | ------------------------------------------------------------------- |
| `color`  | `#606060` | Set the color of elements with the class "icons" to #606060 (gray). |

**Selector Explanation:** The `.icons` selector targets elements with the class "icons."
![image](https://github.com/rajakhan017/Youtube-UI-Clone/assets/135150598/eb528936-a83e-4a02-8339-f55ee4093034)


### In `header.css`

#### .header

| Property          | Value           | Description                                                                                                   |
| ----------------- | --------------- | ------------------------------------------------------------------------------------------------------------- |
| `height`          | `70px`          | Set the height of elements with the class "header" to 70px.                                                   |
| `padding`         | `15px`          | Add padding to the top and bottom (15px) and left and right (15px) sides of elements with the class "header." |
| `display`         | `flex`          | Set the element to use flexbox layout.                                                                        |
| `justify-content` | `space-between` | Distribute space evenly between flex items horizontally.                                                      |
| `align-items`     | `center`        | Align flex items vertically at the center.                                                                    |

**Selector Explanation:** The `.header` selector targets elements with the class "header."
![image](https://github.com/rajakhan017/Youtube-UI-Clone/assets/135150598/217ac339-fffb-42fe-92cc-becdc7724167)

#### .branding

| Property      | Value    | Description                                |
| ------------- | -------- | ------------------------------------------ |
| `display`     | `flex`   | Set the element to use flexbox layout.     |
| `align-items` | `center` | Align flex items vertically at the center. |

**Selector Explanation:** The `.branding` selector targets elements with the class "branding."

#### .branding img

| Property      | Value  | Description                                                                              |
| ------------- | ------ | ---------------------------------------------------------------------------------------- |
| `width`       | `50px` | Set the width of `img` elements within elements with the class "branding" to 50px.       |
| `margin-left` | `10px` | Add margin to the left side of `img` elements within elements with the class "branding." |

**Selector Explanation:** The `.branding img` selector targets `img` elements that are descendants of elements with the class "branding."

#### .branding .icons

| Property  | Value     | Description                                                                                                                                         |
| --------- | --------- | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| `padding` | `0 10px`  | Add padding to the top and bottom (0) and left and right (10px) sides of elements with the class "icons" within elements with the class "branding." |
| `cursor`  | `pointer` | Set the cursor to a pointer (hand) for elements with the class "icons" within elements with the class "branding."                                   |

**Selector Explanation:** The `.branding .icons` selector targets elements with the class "icons" that are descendants of elements with the class "branding."

#### .search

| Property  | Value               | Description                                                                         |
| --------- | ------------------- | ----------------------------------------------------------------------------------- |
| `display` | `flex`              | Set the element to use flexbox layout.                                              |
| `height`  | `35px`              | Set the height of elements with the class "search" to 35px.                         |
| `border`  | `1px solid #dddddd` | Set a 1px solid border with the color #dddddd for elements with the class "search." |

**Selector Explanation:** The `.search` selector targets elements with the class "search."
![image](https://github.com/rajakhan017/Youtube-UI-Clone/assets/135150598/c13e9eac-a747-4b59-b256-b100704b3d70)

#### .search input

| Property  | Value   | Description                                                                                            |
| --------- | ------- | ------------------------------------------------------------------------------------------------------ |
| `width`   | `500px` | Set the width of `input` elements within elements with the class "search" to 500px.                    |
| `padding` | `10px`  | Add padding to `input` elements within elements with the class "search."                               |
| `height`  | `100%`  | Set the height of `input` elements within elements with the class "search" to 100% of their container. |
| `border`  | `none`  | Remove the border on `input` elements within elements with the class "search."                         |

**Selector Explanation:** The `.search input` selector targets `input` elements that are descendants of elements with the class "search."

#### .search button

| Property | Value  | Description                                                                     |
| -------- | ------ | ------------------------------------------------------------------------------- |
| `border` | `none` | Remove the border on `button` elements within elements with the class "search." |

**Selector Explanation:** The `.search button` selector targets `button` elements that are descendants of elements with the class "search."

### In `aside.css`

#### .aside

| Property           | Value    | Description                                                                           |
| ------------------ | -------- | ------------------------------------------------------------------------------------- |
| `background-color` | `#fff`   | Set the background color of elements with the class "aside" to #fff (white).          |
| `overflow-y`       | `scroll` | Enable vertical scrolling for elements with the class "aside" when content overflows. |
| `width`            | `230px`  | Set the width of elements with the class "aside" to 230px.                            |

**Selector Explanation:** The `.aside` selector targets elements with the class "aside."

#### .categories

| Property         | Value    | Description                                                                      |
| ---------------- | -------- | -------------------------------------------------------------------------------- |
| `display`        | `flex`   | Set the element to use flexbox layout.                                           |
| `flex-direction` | `column` | Set the flex container to display its items in a column.                         |
| `margin`         | `15px 0` | Add margin to the top and bottom (15px) of elements with the class "categories." |

**Selector Explanation:** The `.categories` selector targets elements with the class "categories."

#### .category

| Property      | Value       | Description                                                                                                     |
| ------------- | ----------- | --------------------------------------------------------------------------------------------------------------- |
| `display`     | `flex`      | Set the element to use flexbox layout.                                                                          |
| `align-items` | `center`    | Align flex items vertically at the center.                                                                      |
| `padding`     | `15px 25px` | Add padding to the top and bottom (15px) and left and right (25px) sides of elements with the class "category." |

**Selector Explanation:** The `.category` selector targets elements with the class "category."
![image](https://github.com/rajakhan017/Youtube-UI-Clone/assets/135150598/eb92a7aa-c668-441e-b07c-c486feec89e2)

#### .category span:not(.icons)

| Property      | Value  | Description                                                                                                                  |
| ------------- | ------ | ---------------------------------------------------------------------------------------------------------------------------- |
| `margin-left` | `15px` | Add margin to the left side of `span` elements within elements with the class "category" that do not have the class "icons." |

**Selector Explanation:** The `.category span:not(.icons)` selector targets `span` elements that are descendants of elements with the class "category" and do not have the class "icons."

#### .category:hover

| Property           | Value     | Description                                                                                         |
| ------------------ | --------- | --------------------------------------------------------------------------------------------------- |
| `background-color` | `#e5e5e5` | Change the background color of elements with the class "category" on hover to #e5e5e5 (light gray). |
| `cursor`           | `pointer` | Set the cursor to a pointer (hand) for elements with the class "category" on hover.                 |

**Selector Explanation:** The `.category:hover` selector targets elements with the class "category" when they are hovered over.

#### .aside::-webkit-scrollbar

| Property  | Value  | Description                                                                                       |
| --------- | ------ | ------------------------------------------------------------------------------------------------- |
| `display` | `none` | Hide the scrollbar for elements with the class "aside" in WebKit (Chrome, Safari, etc.) browsers. |

**Selector Explanation:** The `.aside::-webkit-scrollbar` selector targets the scrollbar in WebKit browsers within elements with the class "aside."

#### hr

| Property           | Value     | Description                                                        |
| ------------------ | --------- | ------------------------------------------------------------------ |
| `height`           | `1px`     | Set the height of `hr` elements to 1px.                            |
| `border`           | `none`    | Remove the border of `hr` elements.                                |
| `background-color` | `#e5e5e5` | Set the background color of `hr` elements to #e5e5e5 (light gray). |

**Selector Explanation:** The `hr` selector targets `hr` elements.
![image](https://github.com/rajakhan017/Youtube-UI-Clone/assets/135150598/3c342cc4-b5e6-489d-aaea-55ca4250238c)

### In `main.css`

#### h1

| Property        | Value     | Description                                                 |
| --------------- | --------- | ----------------------------------------------------------- |
| `font-size`     | `20px`    | Set the font size of `h1` elements to 20px.                 |
| `margin-bottom` | `10px`    | Add margin to the bottom of `h1` elements.                  |
| `color`         | `#030303` | Set the text color of `h1` elements to #030303 (dark gray). |

**Selector Explanation:** The `h1` selector targets `h1` elements.

#### .main

| Property           | Value               | Description                                                                                                 |
| ------------------ | ------------------- | ----------------------------------------------------------------------------------------------------------- |
| `width`            | `100%`              | Set the width of elements with the class "main" to 100%.                                                    |
| `background-color` | `#f9f9f9`           | Set the background color of elements with the class "main" to #f9f9f9 (light gray).                         |
| `overflow-y`       | `scroll`            | Enable vertical scrolling for elements with the class "main" when content overflows.                        |
| `padding`          | `15px`              | Add padding to the top and bottom (15px) and left and right (15px) sides of elements with the class "main." |
| `border-top`       | `1px solid #dddddd` | Add a 1px solid border at the top of elements with the class "main."                                        |

**Selector Explanation:** The `.main` selector targets elements with the class "main."

#### .videos

| Property          | Value          | Description                                                              |
| ----------------- | -------------- | ------------------------------------------------------------------------ |
| `display`         | `flex`         | Set the element to use flexbox layout.                                   |
| `justify-content` | `space-around` | Distribute space evenly between flex items horizontally.                 |
| `flex-wrap`       | `wrap`         | Allow flex items to wrap to the next line when there's not enough space. |

**Selector Explanation:** The `.videos` selector targets elements with the class "videos."
![image](https://github.com/rajakhan017/Youtube-UI-Clone/assets/135150598/7f4dab51-e912-425c-9632-b3a309f5e4cb)

#### .video

| Property        | Value   | Description                                                  |
| --------------- | ------- | ------------------------------------------------------------ |
| `width`         | `310px` | Set the width of elements with the class "video" to 310px.   |
| `margin-bottom` | `30px`  | Add margin to the bottom of elements with the class "video." |

**Selector Explanation:** The `.video` selector targets elements with the class "video."
![image](https://github.com/rajakhan017/Youtube-UI-Clone/assets/135150598/b345a70e-35b2-4a74-903c-8c4c6ccfa1fe)

#### .thumb

| Property     | Value   | Description                                                 |
| ------------ | ------- | ----------------------------------------------------------- |
| `width`      | `100%`  | Set the width of elements with the class "thumb" to 100%.   |
| `height`     | `170px` | Set the height of elements with the class "thumb" to 170px. |
| `object-fit` | `cover` | Scale and crop the image to cover the entire element.       |

**Selector Explanation:** The `.thumb` selector targets elements with the class "thumb."

#### .uploader

| Property        | Value   | Description                                                         |
| --------------- | ------- | ------------------------------------------------------------------- |
| `width`         | `40px`  | Set the width of elements with the class "uploader" to 40px.        |
| `height`        | `40px`  | Set the height of elements with the class "uploader" to 40px.       |
| `object-fit`    | `cover` | Scale and crop the image to cover the entire element.               |
| `border-radius` | `50px`  | Add rounded corners (50px) to elements with the class "uploader."   |
| `margin-right`  | `10px`  | Add margin to the right side of elements with the class "uploader." |

**Selector Explanation:** The `.uploader` selector targets elements with the class "uploader."

#### .details

| Property  | Value  | Description                            |
| --------- | ------ | -------------------------------------- |
| `display` | `flex` | Set the element to use flexbox layout. |

**Selector Explanation:** The `.details` selector targets elements with the class "details."

#### .text

| Property         | Value    | Description                                              |
| ---------------- | -------- | -------------------------------------------------------- |
| `display`        | `flex`   | Set the element to use flexbox layout.                   |
| `flex-direction` | `column` | Set the flex container to display its items in a column. |

**Selector Explanation:** The `.text` selector targets elements with the class "text."

#### .text.h3

| Property        | Value     | Description                                                                                     |
| --------------- | --------- | ----------------------------------------------------------------------------------------------- |
| `color`         | `#030303` | Set the text color of elements with the class "text" and the class "h3" to #030303 (dark gray). |
| `font-size`     | `14px`    | Set the font size of elements with the class "text" and the class "h3" to 14px.                 |
| `line-height`   | `18px`    | Set the line height of elements with the class "text" and the class "h3" to 18px.               |
| `margin-bottom` | `6px`     | Add margin to the bottom of elements with the class "text" and the class "h3."                  |

**Selector Explanation:** The `.text.h3` selector targets elements with the class "text" and the class "h3."

#### .text a, span

| Property          | Value     | Description                                                                |
| ----------------- | --------- | -------------------------------------------------------------------------- |
| `text-decoration` | `none`    | Remove text decoration (underlining) for `a` elements and `span` elements. |
| `font-size`       | `14px`    | Set the font size of `a` elements and `span` elements to 14px.             |
| `color`           | `#606060` | Set the text color of `a` elements and `span` elements to #606060 (gray).  |

**Selector Explanation:** The `.text a, span` selector targets `a` elements and `span` elements.
