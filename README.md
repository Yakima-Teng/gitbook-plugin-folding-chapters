#Enable your GitBook with folding chapters
==============

| This plugin adds an icon to each chapter, that has a child and css states for the child list to collapse/expand ones.

This plugin is built on base of [gitbook-plugin-expandable-chapters](https://github.com/DomainDrivenArchitecture/gitbook-plugin-expandable-chapters): I found that plugin not available in my gitbook, so I made some changes to it.


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

### Thanks

- [gitbook-plugin-expandable-chapters](https://github.com/DomainDrivenArchitecture/gitbook-plugin-expandable-chapters)
