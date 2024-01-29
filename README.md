# JHU-Ajax-Module-2
Week 2 assignment for JHU Ajax Course

# Notes

- Floating elements
   
    1. Floating elements DO NOT have collapsing margins!
    2. Floating elements takes them out of the regular flow of the document
    
        - *clear: some_side* property prevents text from residing on the same line

- Absolute positioning

    1.  All offsets are relative to position of nearest ancestor that has positioning (other than static) set on it

- Media queries

    1. Syntax: @media (max-width: 767px) {...}
    2. Basically, these are boolean values - if any one evaluates to true, then the media query is executed
    3. We can use logical operators on these - e.g. @media (min-width: 767px) and (max-width: 991px) {...}
    4. Generally start with base styles **before** media queries
        - These styles apply to everything across the board
    5. We **have** to be careful not to mix range boundaries (or else both style sections apply to some said query)

- 12-col grid layout

    1. 12 columns that can be broken up into factors of 12 (1, 2, 3, 4, 6, 12)
    2. 12 columns = 100% of page width (or 100% of the parent container)