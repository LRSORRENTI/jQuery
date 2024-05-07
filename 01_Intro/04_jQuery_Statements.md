# jQuery Statements 

Almost every single jQuery statement begins with a dollar sign $, the dollar sign in jQuery is known as the main jQuery key 

For example, in vanilla js to grab an element by it's id: 

```
document.getElementById('main-heading')
```

jQuery version:

```
$('#main-heading')
```

And we can add whichever css styles using the .css() method jqeury exposes 

```
// $(document).ready(() => {
//     alert('jquery loaded!')
// })

$('#lead-banner p').css({color: "red"})

$('h3').css({border: "2px solid blue"})

$('.wrapper').css({border: "1px solid red", paddingLeft: "20px"})

$('#clients').css({border: "1px solid yellow"})
```