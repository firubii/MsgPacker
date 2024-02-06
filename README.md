# MsgPacker

A very simple MsgPack/JSON command line converter.

## Usage

```
MsgPacker.exe <file> [output]
```
The conversion operation (MsgPack to JSON, JSON to MsgPack) is inferred through the input file's file extension.

MsgPack files are detected by the `.msg` extension and JSON files are detected by the `.json` extension. If an output path isn't given, the program defaults to the same location as the input file.
