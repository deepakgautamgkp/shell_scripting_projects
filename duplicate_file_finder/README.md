How it works:

find "$dir" -type f → finds all files in the directory.

md5sum → generates a hash (fingerprint) for each file.

sort → sorts results by checksum.

uniq -d -w32 → shows only duplicate checksums (meaning duplicate files).
