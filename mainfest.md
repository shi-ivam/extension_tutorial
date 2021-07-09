Within the Extension folder
Create a file named manifest.json file
Current version is 2 and it seems a new version is launched (v3)

The manifest.json file should look something like this
```
{
    "manifest_version":2,
    "name":"Hello World",
    "version":"1.1",
    "description":"...",
    "icons":{
        128:"128px.png",
        48:"48px.png",
        16:"16px.png"
    },
    "browser_action":{
        "default_icon":"icon16.png",
        "default_popup":"popup.html"
    }
}
```