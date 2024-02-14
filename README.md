![image](https://github.com/FilSalustri/my-notion-quote/assets/7852355/49789156-e286-4ad4-b33c-ec682bd69df5)# Notion Random Quote
**THIS IS A WORK IN PROGRESS!!**

I'm trying to modify the [original version](https://github.com/saman/notion-quote) to work better in Google Sites.

**ORIGINAL TEXT BELOW**

This is a widget for [Notion](https://notion.so). You can insert the URL of this repository in an [embed item](https://www.notion.so/help/embed-and-connect-other-apps).

## Settings
On the right bottom corner, you can change settings. They are developed in a way to integrate this widget perfectly.

## Add a different source
You can add a different source for random quotes. This source must be a JSON file hosted somewhere.
As an example you can use [Github Gist](https://gist.github.com/).

The valid JSON file must be in this format:
```json
[
  {
    "author": "First Author Name",
    "content": "First Quote Content."
  },
  {
    "author": "Second Author Name",
    "content": "Second Quote Content."
  }
]
```

You have to add the url of your JSON file with parameter `f` into query parameters.
If you're using a gist, make sure you use the raw version.

Here is an example for [my gist](https://gist.github.com/saman/a4326228c01f7fe15de6707655352300):
```
https://saman.dev/notion-quote/?f=https://gist.githubusercontent.com/saman/a4326228c01f7fe15de6707655352300/raw/6ae8c92baae70fb842ddf91f3465ccab5f7b1622/my-notion-quote.json
```
