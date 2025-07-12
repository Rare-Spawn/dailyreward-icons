# Daily Reward Icons

This repository hosts PNG images for use with a rewards calendar in a FiveM/QBCore server.

The images here are intended to support custom reward types such as:

* Crafting materials
* Fuel vouchers
* Plush toys and collectibles
* Server-specific items from `qb-core/shared/items.lua`

Each image can be used as the `img` field in the Sky Systems reward table like so:

```lua
{
    label = "Fuel Voucher",
    sort = "item",
    name = "fuelvoucher",
    amount = 1,
    img = "https://yourusername.github.io/dailyreward-icons/fuelvoucher.png"
}
```

## How to Use

1. Upload your custom icons into this repository via GitHub.
2. Enable GitHub Pages under the repository settings (branch = `main`, folder = `/`).
3. Reference each image using a direct URL:
   `https://yourusername.github.io/dailyreward-icons/your_image_name.png`

## Notes

* Keep image file names lowercase and use underscores for spaces.
* PNG format is recommended, ideally under 100 KB.
* GitHub Pages has a soft limit of 1 GB per repo and 100 GB/month bandwidth.

## Credits

This repo was set up to support the Velocity Transit server and may also help others using reward-based tools in FiveM.

## License

Feel free to fork and reuse. Attribution appreciated but not required.

---

Maintained by: **[@Rare-Spawn](https://github.com/Rare-Spawn)**

