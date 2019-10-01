
# Collapsible left nav Blazor application

![Extended](https://user-images.githubusercontent.com/13876805/65983041-a47ed880-e44a-11e9-92b7-516e7ba8545f.PNG)

![Collapsed](https://user-images.githubusercontent.com/13876805/65983047-a779c900-e44a-11e9-9092-667e7c8744c8.PNG)

## Using with IE

To use Blazor in IE you have to add the blazor polyfill to the _Host.cshtml file

```
    <script type="text/javascript" src="/blazor.polyfill.min.js"></script>

    <script autostart="false" src="_framework/blazor.server.js"></script>

    <script>
        Blazor.start();
    </script> 
    
```






