# BraidDatTool

Usage: BraidDatTool (-u archive_name | -r archive_name [compression_level])

```
	 -u archive_name                            Unpack the archive. 
	 -r archive_name [compression_level]        Repack the archive.
```

When repacking, optionally you can specify the compression level. Valid values are from -4 (fastest) to 9 (slowest).

Default value is 6 (devs used it), but it's pretty slow, very slow I would say, so I decided to add this compression level option at least for testing purposes.

Looking for the archive to run BraidDatTool on? Maybe it's `C:\Program Files (x86)\Steam\steamapps\common\Braid Anniversary Edition\data\braid.dat`, or in a similar location. Typically the folder where the Braid executable lives has a subfolder data/, which includes only the archive file, braid.dat.

TODO: currently, the archive_name parameter is ignored, and braid.dat or braid.dat_new (respectively) is hard-coded instead.
