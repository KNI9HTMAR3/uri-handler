# URI Handler

A simple web-based URI handler for **Steam** and **Epic Games Store** links. Designed as a workaround for platforms like Discord that don't support native URI schemes.

## Usage

### Steam

```
https://kni9htmar3.github.io/uri-handler/steam/{appid}
```

**Example:** [Open CS2 in Steam](https://kni9htmar3.github.io/uri-handler/steam/730)

### Epic Games

```
https://kni9htmar3.github.io/uri-handler/epic/{slug}
```

**Example:** [Open Styx in Epic](https://kni9htmar3.github.io/uri-handler/epic/styx-shards-of-darkness-77c030)

## Notes

- Requires Steam / Epic Games Launcher installed.
- Auto closes the tab after opening.

```
steam-uri-handler
├─ 404.html
├─ epic
│  └─ index.html
├─ index.html
├─ LICENSE
├─ README.md
└─ steam
   └─ index.html

```