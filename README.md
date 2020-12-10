Srg2Source v7.0

A tool for renaming symbols (classes, methods, fields, parameters, and variables) in Java source code using .srg mappings.

For porting, Minecraft, CraftBukkit, mods, plugins, etc.

## Usage

    java -jar Srg2Source-fatjar.jar --extract --input [SourceDir] --output [RangeMapOutput] --lib [Library]

    java -jar Srg2Source-fatjar.jar --apply --input [SourceDir] --range [RangeMap] --srg [SRGFile] --excFiles [ExcFile] --outDir [Output] --keepImports [KeepImports] --missing [MissingFile] --overrideOutput [OverrideOutput]

## See also

Inspired by the Frans-Willem's binary remapper ApplySrg, originally from https://github.com/Frans-Willem/SrgTools (updated version at https://github.com/agaricusb/SrgTools)

More remapping tools and generated .srgs: https://github.com/agaricusb/MinecraftRemapping
