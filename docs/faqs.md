# FAQs

## Fix compare page messed up for many items

Go to **Storefront** > **Script Manager**, click **Create a Script**, choose:

- **Location on page** = `Head`
- **Select pages where script will be added** = `Store Pages`
- **Script type** = `Script`

Enter the script below to **Scripts contents**:

```html
<script>
(function() {
var style = document.createElement('style');
style.innerHTML = '.supermarket-pageType--compare .page-content { overflow: auto; -webkit-overflow-scrolling: touch; position: relative }'
+ '.compareTable { table-layout: auto }'
+ '.compareTable-product .card { min-width: 150px }'
+ '@media (min-width: 801px) { .compareTable-product .card { min-width: 250px } }';
document.head.appendChild(style);
})();
</script>
```


## Move the submenu dropdown to left if it exceeds the window's width

Go to **Storefront** > **Script Manager**, click **Create a Script**, choose:

- **Location on page** = `Footer`
- **Select pages where script will be added** = `All Pages`
- **Script type** = `Script`

Enter the script below to **Scripts contents**:

```html
<script>
(function($) {
    $('.navPages-item').on('mouseover', function(event) {
        var $el = $(event.currentTarget);
        $el.find('.navPage-subMenu').each(function(j, el2) {
            var $el2 = $(el2);
            $el2.css('left', '');

            var right = $el2.offset().left + $el2.width();
            var left = $el2.offset().left;

            if (right > window.innerWidth) {
                $el2.css('left', Math.floor(window.innerWidth - right));
            }
        });
    });
})(window.jQueryTheme || window.jQuerySupermarket || window.jQuery);
</script>
```
