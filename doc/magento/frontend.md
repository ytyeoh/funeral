# Magento 2 Frontend
Suggestion for Magento 2 forntend to be done. Currently styles was control by styles-m.min.css & styles-l.min.css and many inline css.
## Library

Curently no library been use inside jshayes. I will  suggets use [Bootstrap V5.2](https://getbootstrap.com/docs/5.2/getting-started/introduction/) whihc is latest on Bootstrap.


### Why need library
Libray make us easy to control all design in whole website, it work as global css to control all element inside website. Example color of button, we can just change 1 line of code, then all colour will be change.

Library and external css will be use as back bone for website, it us eto control font, button, background and other element use in website.

Internal css or individual css file will be use to control seperate page design like category, product and contact us page.

Inline css will be use if need dynamic design for certain inside that page. Example title name need to be red for regal product in category page.

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

