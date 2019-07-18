
# Collapsible left nav Blazor application

![Extended](https://user-images.githubusercontent.com/13876805/61490650-7a556880-a97b-11e9-99b0-0252771d2a49.png)

![Collapsed](https://user-images.githubusercontent.com/13876805/61490712-9953fa80-a97b-11e9-8b32-bedce2e42d69.png)

## Using with IE

To use Blazor in IE you have to add the blazor polyfill to the _Host.cshtml file

```
    <script type="text/javascript" src="/blazor.polyfill.min.js"></script>

    <script autostart="false" src="_framework/blazor.server.js"></script>

    <script>
        Blazor.start();
    </script> 
    
```






