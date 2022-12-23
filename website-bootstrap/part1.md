- this repo follow the video - https://youtu.be/4sosXZsdy-s
- `nav.navbar.navbar-expand-lg.bg-dark.navbar-dark`
    - will give
        ```
        <nav class="navbar navbar-expand-lg bg-dark navbar-dark"></nav>
        ```
    - `nav` - nav tag
    - `navbar-expand` - means it is responsive
    - `lg` - breakpoint
    - `bg-dark` - dark background
    - `navbar-dark` - so letters will be white
- `a.navbar-brand`
    - will give
        - `<a href="" class="navbar-brand"></a>`
    - `a.` 
        - a tag
    - `navbar-brand`
        - will be the class
- `.collapse.navbar-collapse`
    - will give
        - `<div class="collapse navbar-collapse">   </div>`
        - this will make sure that the navbar collapses into a hamburger upon resizing
- `ul.navbar-nav`
    - this is for having unordered list in navbar
- `li.nav-item`
    - this will be for items that will be in the navbar
- `a.nav-link`
    - this will be for link inside the navigation bar
- inside the navbar-nav class putting `ms-auto` will align it to the right
- `button.navbar-toggler`
    - `<button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navmenu">`
        - type = button
        - data-bs-toggle = "collapse" will collapse the menu
        - data-bs-target="#navmenu" will render the details in id navmenu
- `section.bg-dark.text-light.p-5.text-center`
    - note all these padding can be between 1 and 5
    - `px-5`
        - x axis padding
    - `py-5`
        - y axis padding
    - `pt-1`
        - padding top
    - `pb-1`
        - padding bottom
    - `p-5`
        - to give padding all the way around
- `d-flex` 
    - to align the text and the image side by side 
    - `d-sm-flex`
        - to keep it intact till sm , once we reach sm , flex will be disabled as its the breakpoint
- ` <span class="text-warning"> web developer</h1>
                </span>`
    - this will make the content inside appear as yellow
- `class="lead"`
    - this will make the letters appear bigger
- `button.btn.btn-primary btn-lg`
    - `btn-lg`
        - will make the button appear larger
- `my-4` 
    - in the class="lead my-4"
    - this will make it move 4 pixel down
- `text-sm-start`
    - this will make the text appear at the start
    - for mobile screens it will be centered , for bigger ones it will be from start
- `d-none`
    - setting the display to none, it wont show anything
- `d-none d-sm-block`
    - it will display none when the size is smaller than mobile screen
- `align-items-center`
- `p-lg-0` 
    - padding on large screens is 0
- `btn-lg`
    - this will make the button look larger
- custom css
    ```
    @media(min-width:768px){
        .news-input{
            width:50%;
        }
    }
    ```
    - this means that , if minimum we had 768px then cut the news-input width to 50%
- `col`
    - if we use col , it will be 3 columns even on small screens
- `col-md`
    - it means it stacks on small screens
    - AND WHEN we hit md(medium) level it will activate cols
- `i.bi.bi-laptop`
    - to give laptop icon
- if we enclose the above inside a div with class as h1, it will appear larger
- `lorem12`
    - this will fill lorem ipsum text with 12 words
- `i.bi.bi-people`
    - this will create people icon
- `bg-secondary`
    - it will be grey in color
- `i.bi.bi-person-square`
    - this will add a person inside a square icon
- `g-4`
    - in line  77 means give gap on all 4 corners
- `p.lead`
    - p tag with class lead will make the p tag appear bigger
- `mt-3`
    - will give padding to top 3 spaces
- `i.bi.bi-chevron-right`
    - this will give right arrow icon
- `fixed-top`
    - on nav bar will make the navbar stay on top of the page always
- pushing the body a little down
    ```
    body::before{
        display:block;
        content:"";
        height: 60px;
    }
    ```
- `section#instructors.p-5.bg-primary`
    - this will have a blue background