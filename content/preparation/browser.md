---
title: "Browser"
date: 2018-04-15T13:31:47-04:00
weight: 30
---

Instructions have been tested with the following (and may work for versions just below):

- Firefox 60
- Chrome 66

Having both browsers available can sometimes be useful. Since an easy way to launch a [simple web server]({{<ref "web-server">}}) involves installing a Chrome extension, you may choose to use Chrome.

## Local Mode

When using the workshop materials in [local mode]({{<ref "local-mode">}}), you can use either Firefox or Chrome. Any recent version of Chrome or Firefox ought to work.

## Online Mode

When using these online instructions, ensure you're using them at an HTTP URL (`http://ronallo.com`) and not an HTTPS URL (`https://ronallo.com`). Our local JSON files will be served under HTTP and many IIIF resources on the web are still delivered via HTTP. Trying to deliver some HTTP resources to an HTTPS page results in mixed content security errors. Delivering the workshop materials via HTTP works around these issues for now.

You can see more information on mixed content here: https://developer.mozilla.org/en-US/docs/Web/Security/Mixed_content#Warnings_in_Web_Console

Once some of these issues are better resolved in the client code used by this workshop and are handled similarly across browsers, the materials will be delivered via HTTPS.

## Viewing JSON

As we'll be taking a look at JSON in a browser at times to make sure things are working, you may want to install an extension for your browser that will pretty up your JSON. These extensions will also validate the format of the JSON which can be helpful in finding syntax errors.

{{% notice note %}}
Note that the extensions will not validate whether a IIIF document is valid to the IIIF standards--just that the JSON format is correct.
{{% /notice %}}

### Chrome

Install the [JSONView](https://chrome.google.com/webstore/detail/jsonview/chklaanhfefbnpoihckbnefhakgolnmc) extension.

### Firefox

Recent versions of Firefox include a JSON viewer by default. Or you can use [JSONView](https://addons.mozilla.org/en-US/firefox/addon/jsonview/).

### Developer Tools

With either browser you may also need at times to open the [developer tools](https://developer.mozilla.org/en-US/docs/Tools). On Windows and Linux this is `Ctrl + Shift + I`. On Mac use `Cmd + Opt + I`.

## Clearing the Browser Cache

Sometimes the browser may cache a resource that you're working on that you've changed. To see the new data you'll need to clear your cache. It is possible in Firefox and Chrome to select an option to disable the cache while the developer tools are open.

Alternatively you may want to try the following browser extensions:

- Firefox: [Empty Cache Button](https://addons.mozilla.org/en-US/firefox/addon/empty-cache-button/)
- Chrome: Open the "Clear browsing data" window using `Cmd + Shift + Delete` on a Mac or `Ctrl + Shift + Delete` on a PC

## Ad Blockers

Sometimes ad blocker extensions (especially algorithmic blockers like Privacy Badger) can give false positives for IIIF resources. The suggestion is to be aware that this is one reason why things may not work. You may also choose to disable ad blockers for the duration of the workshop. You may need to whitelist certain sites if you leave your ad blocker enabled.

## Multiple Windows

Make sure you know how to place two browser windows next to each other. As you work through some exercises it will be helpful to have two windows open side by side.

## Open in a New Window

Make sure you know how to open a link in a new window. The context menu for a link (sometimes a right click) will give the option to open a link in a new tab or window.
