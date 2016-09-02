#Content layout for the web 

In determining a page layout for the web there are two considerations:  1) The **apparent page layout** on a larger display (i.e., what a person sees on screen) and 2) the **actual content order** in the document (i.e., how it is ordered in the DOM). Let’s begin with the second consideration. On a small phone screen a website should no longer display in two or more columns as this would probably be unreadable. The content needs to stack up. The order of this stacking is most elegantly determined by the actual (read: semantic) order of content in your document. 

So imagine a page of content with three sections and we will name these sections Primary, Secondary and Tertiary. Think of these regions as containers into which content can be poured. On a phone or similar small display, this content would stack with Primary on top, Secondary next and Tertiary at the bottom. For the sake of simplicity, this is always the small display view:  document content order = single-column, stacked display order.

[image]

As we expand the size of the display we are afforded the luxury of more layout choices. Perhaps Primary is a left-hand sidebar column that occupies 1/4 the width of the display. Secondary occupies the remaining 3/4 of the display and Tertiary hangs out under both and is full width. This is a pretty common layout.
 
[image]

As long as the display is wide enough, this two-column layout is great, but it will need to cutover to a single-column stack at some point on a display that is narrower. This exact cutover width is arbitrary and is selected subjectively to enhance usability of the page, but we will not care about that width here.

[image] > [image]
