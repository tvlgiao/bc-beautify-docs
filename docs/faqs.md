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

