# Chrome DevTool

***

* Browser three vertical dots -> `More Tools` -> `Developer Tools` -> `Network` -> `Disable cache`
    - `https://badssl.com`
    
    - `http://husseinnasser.com`
    - `http://www.husseinnasser.com` -> Redirect
    - `https://www.husseinnasser.com` -> Redirect

***

* [Demystifying the Browser Networking Tab in Developer Tools With Examples](https://www.youtube.com/watch?v=LBgfSwX4GDI)

* [DevTools Waterfall Deep Dive](https://www.youtube.com/watch?v=6TEwVDNA7bI)

***

## `HAR (HTTP Archive)` File

* [Generating a .HAR File on Chrome Browser](https://www.youtube.com/watch?v=m98WFEXbhIs)

* Go to the web-link -> Right-click `Inspect` -> `Networ` -> `Preserve log` is checked -> `Disable cache` is checked->`All` -> Refresh the web-link -> right-click on a `Name` entry -> Save all as `HAR` with content

***

* [HTTP Archive Viewer 2.0.17](http://www.softwareishard.com/har/viewer/)
    - drag / drop you .HAR file

***

* [Inspecting file download headers using Chrome developer tools](https://www.youtube.com/watch?v=BxNnYq_pLQU)

***

## StackOverflow

* [Capture Downloads in the Network Tab of Google Chrome Developer Tools](https://stackoverflow.com/questions/48921321/capture-downloads-in-the-network-tab-of-google-chrome-developer-tools)

```
It's true. The download is done in another tab, which is immediately closed upon download completion. The suggested method of Mathias is brilliant and works like a charm : foto to chrome://downloads and copy URL of the download. Then go to the page that displays the link, open the dev tools/network, and then pasted link and hit ENTER. The request is captured and you can get the curl version of the download. Brilliant @Matthias Schuchardt
```
