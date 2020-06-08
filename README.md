# AppAssets-Scripts

Batch decode script collection for LoveLive! SIF resources (`AppAssets.zip`)

## Usage

```bash
python3 decode.py
```

## Dependencies

- [MikuAuahDark/HonokaMiku](https://github.com/MikuAuahDark/HonokaMiku) - General file decoding
- [iebb/SIF40_Decrypt](https://github.com/iebb/SIF40_Decrypt) - SQLite 3 database decoding
- [skufes/LLSIF-JsonBinaryCC](https://github.com/skufes/LLSIF-JsonBinaryCC) - JSON decoding
- [MikuAuahDark/Itsudemo](https://github.com/MikuAuahDark/Itsudemo) - Unpack 2D texture banks (`.texb` files) to PNG images
- [HansWessels/unluac](https://github.com/HansWessels/unluac) - Lua Decompiler
