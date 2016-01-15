#Parse CSS Discovery

This is an explortation into parsing shorthand CSS properties used in a style declaration

    div#element{
      border: 1px solid #000000;
    }


into their long-handed format:

    <div id="element" style="border-width: 1px; border-style: solid; border-color: #000000">
      Some content
    </div> 
