# TrackMania 2020 Custom Skid Marks

<p align="center">
  <img src="https://github.com/snixtho/tm2020-skids/blob/master/Images/header.png" />
</p>

## How to install
**WARNING: This will override all texture mods on custom maps.**

To change your skids follow these steps:
1. [Download](https://github.com/snixtho/tm2020-skids/releases/latest/download/Skids.zip) the ZIP file and extract the `Skids` folder.
2. Find your local `Trackmania` folder in your `Documents` directory - it may also be called `Trackmania2020`. To keep it simple, it'll just be called `Trackmania` from now on.
3. Then inside `Documents\Trackmania\Skins\Stadium`, create a folder called `ModWork`.
4. Follow the instructions below for each surface.

### Asphalt/Tarmac Skids
1. Create a folder called `CarFxImage` inside `Documents\Trackmania\Skins\Stadium\ModWork`.
2. Inside the downloaded and extracted `Skids` folder, open the `Asphalt` folder.
3. Choose your skid marks represented as a .dds file, and copy them to `Documents\Trackmania\Skins\Stadium\ModWork\CarFxImage`.
4. Rename the copied file inside `Documents\Trackmania\Skins\Stadium\ModWork\CarFxImage` to `CarAsphaltMarks.dds` so that the file path looks like this: `Documents\Trackmania\Skins\Stadium\ModWork\CarFxImage\CarAsphaltMarks.dds`.

### Dirt Skids
1. Inside the downloaded and extracted `Skids` folder, open the `Dirt` folder.
2. Choose your skid marks represented as a .dds file, and copy them to `Documents\Trackmania\Skins\Stadium\ModWork`.
3. Rename the copied file inside `Documents\Trackmania\Skins\Stadium\ModWork` to `DirtMarks.dds` so that the file path looks like this: `Documents\Trackmania\Skins\Stadium\ModWork\DirtMarks.dds`.
4. As a bonus, you can disable the smoke effect by copying the `DirtSmoke.dds` file into `Documents\Trackmania\Skins\Stadium\ModWork`.

### Grass Skids
1. Create a folder called `CarFxImage` inside `Documents\Trackmania\Skins\Stadium\ModWork`.
2. Inside the downloaded and extracted `Skids` folder, open the `Grass` folder.
3. Choose your skid marks represented as a .dds file, and copy them to `Documents\Trackmania\Skins\Stadium\ModWork\CarFxImage`.
4. Rename the copied file inside `Documents\Trackmania\Skins\Stadium\ModWork\CarFxImage` to `CarGrassMarks.dds` so that the file path looks like this: `Documents\Trackmania\Skins\Stadium\ModWork\CarFxImage\CarGrassMarks.dds`.

### You're done!
Here is an example of how it looks with all surfaces installed and no dirt smoke:
![](Images/modwork_example.png)

You can repeat the process for changing skids, just replace the files for the new skids. You do not need to restart the game or reload the map, changing skids will update live ingame. However, if you remove the skids, you will need to restart your game first.

## How to uninstall
To remove the custom skid marks, either rename or remove the `ModWork` folder in `Documents\Trackmania\Skins\Stadium`. You will need to restart the game, otherwise skid marks will appear solid black.

You can also replace the skids with the `Default.dds` for each surface so you don't have to restart the game. But keep in mind that this still overrides map mods.

## How to create your own custom skid marks
Each surface includes a `Default.dds` file, which should be the original skids used by the game. You can use these as templates in any program that allows editing of DDS (DirectDraw Surface) files. Save the DDS files with **DXT5** or higher versions.
