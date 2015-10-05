# atom packages & themes

## How to install

```bash
apm install --packages-file recommend_packages.txt
```

## How to update `recommend_packages.txt`

```bash
apm list -ib > recommend_packages.txt
```

## How to change the color of selected region

Open `color.less` and edit it.

```bash
cd ~/.atom/packages/monokai/styles/
vi color.less
```

```less
@brown-gray: #393939;//#49483E;
```
