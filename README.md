# \<windows-hello\>

&lt;windows-hello&gt; is a reusable custom web component used to authenticate with Windows Hello. This web component allows other web developers to easily integrate Windows Hello's Web Authentication into their web application 

## Example 

```html
<windows-hello relying-party="Outlook" display-name="Roman Canlas" account-name="roman.canlas@hotmail.com" challenge="challengefromserver"></windows-hello>
```

Note: Currently supported only in Microsoft Edge (other browsers coming soon!) with Windows 10

Please be a contributor and help improve this web component! 


## Related Links

[Windows Hello in Microsoft Edge](https://channel9.msdn.com/Events/Build/2016/P514)

[A world without passwords: Windows Hello in Microsoft Edge](https://blogs.windows.com/msedgedev/2016/04/12/a-world-without-passwords-windows-hello-in-microsoft-edge)


## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Viewing Your Application

```
$ polymer serve
```

## Building Your Application

```
$ polymer build
```

This will create a `build/` folder with `bundled/` and `unbundled/` sub-folders
containing a bundled (Vulcanized) and unbundled builds, both run through HTML,
CSS, and JS optimizers.

You can serve the built versions by giving `polymer serve` a folder to serve
from:

```
$ polymer serve build/bundled
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
