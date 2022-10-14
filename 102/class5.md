# Class 5 README Notes

## CSS -> Cascading Style Sheets - allows you to create great looking web pages (styles, lay-out, color, ect)
            * Controls how HTML elements look in the browser, presenting you mark-up using whatever design you like.
            * You define CSS rules by specifying groups of styles that sgould be applies to a particular element.
                - Selectors - selects HTML element that will be styled.
                    { where you place declarations } - take form of the property & value pairs
            * CSS properties have different allowable values - depends on property being specified.
            
# HOW TO ADD CSS
    **External - Change the look of entire website by changing 1 file, can be written in any text editor but must be saved with a ".CSS" extension.**
    **Internal - If 1 single HTML pages has unique style, defined inside <style> element inside head section.**
    **Inline - Used to apply style for single element, add style attrinutes to relevant elements and contains any CSS property, defined within the "style" attibute of the relevant element.**
    **Multiple StyleSheets - If some properties have been defined for the same selector (element) in different StyleSheets, the value from last read StyleSheets will be used.**

Cascending Order - If more than 1 StyleSheet is specifed, the page will "cascade" into new visual StyleSheets where numbers has highest priority.
    1) Inline 2) External & Internal 3) Browser default 

## Structure of CSS
    selector{
        property: value;
    }