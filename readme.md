# resources

sYamazアカウントで使用するリソース類です

## avater-square.pngからicoを作成する

```sh
brew install imagemagic
magick ./avater-square.png -define icon:auto-resize=16,32 favicon.ico
```