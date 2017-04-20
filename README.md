# pokemon-go map boilerplate

Place your own [Bing Map key](https://msdn.microsoft.com/en-us/library/ff428642.aspx) in `myMap.js`.
```javascript
function loadMapScenario() {
    map_manager.map = new Microsoft.Maps.Map(document.getElementById('myMap'), {
        credentials: '<put your Bing map key here>'
    });
    add_pokemon_layer();
}
```

>Disclaimer: This is a POC(Proof of concept) project for education purpose.

License: MIT
