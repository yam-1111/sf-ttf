# sf-ttf
Collection of SF fonts and Symbols from Apple

## How to extract?

### Mac OS

- Download [SF Fonts](https://developer.apple.com/fonts/) on Apple website

- On terminal:

    ```zsh
    hdiutil attach <downloaded font>.dmg
    ```

- On finder:

    - Right click the downloaded `.dmg` file and click open
    
- Go in terminal and cd to `/Volumes/<SF fonts>

- Copy the `.pkg` file by `cp <SF fonts>.pkg <TARGET_DIRECTORY>` 

- Go on the target and extract the files by `pkgutil --expand-full <SF Font>.pkg <TARGET_FOLDER>`

- On finder navigate and find the `*.pkg` and ooen package content

- Now copy the fonts
 

