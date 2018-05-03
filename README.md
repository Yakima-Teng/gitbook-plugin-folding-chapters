# Equip your GitBook with folding chapters


> This plugin will make chapters of your GitBook collapsible.


An example snapshot (gitbook theme used: [gitbook-plugin-theme-code](https://github.com/Yakima-Teng/gitbook-plugin-theme-code)):

![](./preview.png)


### How to use it?

Add it to your `book.json` configuration:

```
{
    "plugins": ["folding-chapters"]
}
```

Install your plugins using:

```
$ gitbook install
```


### Configuration

There is no configuration needed at the moment, can be left empty.

```
{
	"pluginsConfig": {
		"folding-chapters":{}
	}
}
```

Actually, it's okay for you to ignore the above code -- you do not need to type them.


### Thanks

This plugin is built on base of [gitbook-plugin-expandable-chapters](https://github.com/DomainDrivenArchitecture/gitbook-plugin-expandable-chapters): It seems that plugin didn't fit GitBook default theme since version 3.0.0, at least I found that plugin not available in my gitbook, so I create this plugin you are seeing now on base of that plugin.
