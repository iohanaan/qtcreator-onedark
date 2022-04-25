# Qt Creator One Dark Theme

Qt Creator One Dark style theme and syntax color theme


## Install
#### Theme

Copy the `themes/OneDark.creatortheme` file into the themes directory:
```bash
mkdir $HOME/.config/QtProject/qtcreator/themes
$ cp themes/OneDark.creatortheme $HOME/.config/QtProject/qtcreator/themes
```

In Qt Creator go to _Tools -> Options -> Environment_ and
select One Dark under "Theme".
Restart Qt Creator.

#### Color scheme

Copy the `styles/onedark.xml` file into the styles directory:
```bash
mkdir $HOME/.config/QtProject/qtcreator/styles
$ cp styles/onedark.xml $HOME/.config/QtProject/qtcreator/styles
```

In Qt Creator go to _Tools -> Options -> Text Editor -> Font & Colors_ and
select One Dark under "Color Scheme".


## Compatibility

For Qt Creator 3.0 and below, remove line which starts with `<style name="PrimitiveType"` in `onedark.xml`.
