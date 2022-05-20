# Aion Specifications

### General Principles

Aion is the name of the conventions and library use to manipulate Aion Hierarchies.

```
{
    "aionType": "file"
    "name"    : String
    "size"    : Integer
    "hash"    : Hash
    "parts"   : Array[Hash] # Hashes of the binary blobs of the file
}
```

```
{
    "aionType": "directory"
    "name"    : String
    "items"   : Array[Hash] # Hashes of serialised Aion objects
}
```

```
{
    "aionType": "indefinite"
    "name"    : String
}
```
