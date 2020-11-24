# Responsive Design Strategies : Max-width and Min-width

## Rule 1 : Where to write media queries?
Always use media queries at the end as it does not have any importance or specificity to selectors so code order matters

## Rule 2 : when to use min or max
if you have built your website with **Desktop First** Approach then use **`max-width`**. otherwise for **Mobile First** approach use **`min-width`**  
```scss
    1.`max-width:600px` means is width <= 600px?.
    2.`min-width:600px` means is width >= 600px?
```

## Rule 3: When to use mobile first approach
Since we have lots of mobile traffic coming, it is logical to put the content on priority over asethetics, unless it is a CMS with lots of desktop functionality or UX requrirements

## Rule 4:  Media Type
Media Types
If we don’t apply a media type, the @ media rule selects all types of devices by default. Otherwise, Media types come right after the @ media rule. There are many kinds of devices but we can group them into 4 categories:

    1.all — for all media types
    2.print — for printers
    3.screen — for computer screens, tablets and, smart-phones
    4.speech — for screen readers that “read” the page out loud

## Rule 5:  Writing Media Queries
    
You need to write for such sizes

    For mobile
    Potrait Tablet
    Landscape Tablet
    Desktop (15 inch macbook with resolution 1440 x 900)
    Big Desktop

    And while writing media queries make sure larger resolution sizes comes first then smaller ones 