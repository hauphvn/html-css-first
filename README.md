# JACK'S BLOG

1. Install web server:
- ``npm -g install static-server``
- To change default port to your port:
``static-server -p 5000`` (ex I want to change to 5000)  
- If you want to use tunnel: let to see : ``ngrok`` keyword.  

### Basic knowledge

-   localStorage  
Using save variable on browser.  
    - set a item:``localStorage.setItem('key','value');``  
    - get a item: ``localStorage.setItem('key');``
### SessionStorage

Storing data during open a browser and end browser is closed.  

### JSON Server
- Installing a json server: ``npm install -g json-server``
- Star JSON Server: ``json-server --watch db.json`` or ``json-server --watch db.json --port 6000``  with 6000 is a your port.  

### Fetch()
- Similar creating a json server, you can use ``fetch()``.  
Viewing at [here](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Fetching_data) to more detail.  
