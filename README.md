# Installing packages

`cmd+shift+P`, type "Install package", search by package name.

# Key-bindings

`super == cmd`

## Go to definition

Included thing, just make sure to re-map to whatever key-binding you like

`Preferences -> Key Bindings`

```js
[
  {
    "keys": ["super+shift+r"],
    "command": "goto_definition"
  }
]
```

## Open/Close side bar

`super+k super+b`

## Display file in a side bar

One of the options is to use a package `SyncedSideBar`, which would do an auto-sync.

## Open recent files

Install package `RecentActiveFiles` and use `super+T`