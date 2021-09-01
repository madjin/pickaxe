# pickaxe

The pickaxe is used to mine resources within the virtual world, and secondary as a weapon.

![](https://i.imgur.com/9EirDxD.png)

Guide: https://docs.webaverse.com/docs/create/pickaxe


## `.metaversefile`

The `.metaversefile` goes in the directory with the GLB file in order to create the XRpackage.

```
{
  "name": "pickaxe",
  "description": "Pickaxe XRPackage",
  "xr_type": "webxr-site@0.0.1",
  "start_url": "index.js",
  "components": [
    {
      "type": "use",
      "subtype": "swing",
      "useAnimation": "combo"
    }
  ]
}
```
