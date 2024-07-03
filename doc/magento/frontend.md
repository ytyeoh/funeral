# Magento 2 Frontend
Suggestion for Magento 2 forntend to be done. Currently styles was control by styles-m.min.css & styles-l.min.css and many inline css.
## Less In Magento 2
Magento 2 use less to contorl over css. Will use existing styles-m.min.css & styles-l.min.css as global css, which work as backbone for jshayes website. 

will remove DRY inline css add into styles-m.min.css then assign class name for element to apply same design via styles-m.min.css to redeuce use of inline css.


## Inline Css
 Inline css run fast, but no good for dynamic web which need to implement new design time to time. Inline css good in static single page html which no need never change design and add new elements into it.
 ### Pros
 1. fast response because no need get from css file.
 2. short develope time, because can direct use after write.

  ### Cons
  1. Element cannot duplicate use for different pages, it only use in single page, mean have to keep write in other pages.
  2. Hard to maintain because it can store in many files, when changing same element acroos whole website.
     
[Example singel page website](https://rainfora.com.my/) suitable for inline css.

## Web Speed Optimise
put certain css file only for certain page, example category page filter, write in individual css file which only been call in category page. [XML to make it](https://magecomp.com/blog/apply-custom-css-for-specific-cms-page-magento-2/) with a step how to add custom css to that single page.

