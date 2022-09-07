# hexo-asset-imag

Replace asset image to absolute path in Hexo. **Works fine with hexo 5 / 6, please feel free to use.**

## Usege

```shell
npm install @ppodds/hexo-asset-image
```

## Example

```shell
├─Data-Structure
├────diagram.png
└─Data-Structure.md
```

> **Notice**: You must switch the `post_asset_folder:true` in `_config.yml`, then use `![infomation](./Data-Structure/diagram.png)` to reference `diagram.png`.
