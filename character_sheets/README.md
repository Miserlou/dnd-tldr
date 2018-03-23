# Ready-To-Play First Level Character Sheets

The files in this directory were made by [Ronny Hart](https://olddungeonmaster.wordpress.com/about/) of [https://olddungeonmaster.wordpress.com](https://olddungeonmaster.wordpress.com).

His website has tons of other [awesome downloads](https://olddungeonmaster.wordpress.com/downloads/) that you should check out as well.

I also made some combined PDFs, `all/all_of_them.pdf`, and `default_party/default_party.pdf`, which stitches them together.

The stitching was done with: 

`
/usr/local/bin/gs -q -dNOPAUSE -dBATCH -sDEVICE=pdfwrite -sOutputFile=default_party/default_party.pdf half-orc_barbarian.pdf human_cleric.pdf elf_ranger.pdf tiefling_rogue.pdf
`
