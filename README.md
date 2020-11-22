Hugo Sakura
---

A Hugo theme based on [@oxalorg's Sakura.css](https://github.com/oxalorg/sakura) and inspired by [Etch](https://github.com/LukasJoswiak/etch)

### Usage

#### Installation
In your site's root dir

``` shell
git submodule add https://github.com/bohrium272/hugo-sakura.git themes/sakura
```

Set the theme in your config.toml/yaml/json

``` toml
theme = "sakura"
```

#### Content placement
Assuming your posts are present in a folder `content/xyz`, add `mainSections` to your site configuration

1. config.toml
```toml
[params]
    mainSections = ["xyz"]
```

2. config.yaml

```yaml
params:
    mainSections:
    - xyz
```

3. config.json

```json
{
    "params": {
        "mainSections": ["xyz"]
    }
}
```

#### Sakura Theme
Set `params.sakuraTheme` to one of:
1. dark
2. dark-solarized
3. earthly
4. ink
5. vader

When not set, the light theme is used.

# Thanks To

1. @oxalorg for [Sakura](https://github.com/oxalorg/sakura)
2. @LukasJoswiak for [Etch](https://github.com/LukasJoswiak/etch)

# License

[GPL-v3.0](https://github.com/bohrium272/hugo-sakura/blob/master/LICENSE)
