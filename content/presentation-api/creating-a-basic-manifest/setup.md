---
title: Manifest Setup
menuTitle: "Setup"
date: 2018-04-15T14:49:22-04:00
weight: 10
---

Let's get set up to create a manifest. Below each step we'll give directions on how to do this from the terminal on a Mac. Feel free though to do each step however you'd like including using a GUI application.

1. First make sure you've followed the instructions in both **[web server]({{<ref "web-server">}})** and **[web server directory]({{<ref "directory">}})**.

    You should already have:

    - A "iiif-workshop" directory with a "test.txt" file
    - A local web server running, pointed to your "iiif-workshop" directory

2. **Open and edit a file named "manifest.json" in your "iiif-workshop" directory**

    In your editor you can navigate to open up a file named "manifest.json".

    Or run the following if you're using the Atom editor:

    ```sh
    atom manifest.json
    ```

    Add the following text (curly braces) to your "manifest.json" file:

    ```json
    {
      "property": "value"
    }
    ```

3. **Open the directory in your browser**

    If you used Web Server for Chrome according to the instructions, you can visit http://localhost:3000 or http://127.0.0.1:3000. From now on we'll use "localhost" in every case, but if that does not work, substitute "127.0.0.1".

    You should see something like this in your browser:

    ![](/images/presentation-setup-open-directory.png)

4. **Open up your manifest in browser**

    Click on "manifest.json" in the directory listing in your browser or visit http://localhost:3000/manifest.json.

    You should see the JSON displayed in your browser.
