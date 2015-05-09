# PC Archive

This is the PC artscene art collection hosted on
[pc.textmod.es](http://pc.textmod.es/).


# Copyright notice

The collies listed in this repository do not belong to the public domain and
are still property of the respective artists. [textmod.es](http://textmod.es/)
is not responsible for the contents or expressions in these artworks.


# Contributing

## Guidelines

[textmod.es](http://textmod.es/) upholds high standards as to what we will
display on the PC artscene collection site. The following guidelines should
be kept in mind when contributing to the project:

 * Only artscene related releases
  
   * The accepted text encodings are:

     * US-ASCII
     * All IBM Code Pages

   * Do not submit UTF-8 encoded works

 * Only original work

 * Check our supported [file formats](http://textmod.es/doc/file-formats)

## Adding files

You can either contact us by e-mail and mail your additions to
[submit@textmod.es](mailto:submit@textmod.es) or use GitHub to send a pull
request with your changes. To contribute using GitHub,
[fork the repository](https://help.github.com/articles/fork-a-repo/) and send
us a [pull request](https://help.github.com/articles/using-pull-requests/)
with your changes.

# Metadata

All packs are accompanied by a meta data file, with the following fields:

```
    name: Name of the pack without extension
    crew: List of crew names
    date: Date of the pack release (can be null if unknown)
    year: Year of the pack
    file: List of pieces in the pack
      filen.ame:
        name:   Name of the piece
        type:   Type of the piece
        date:   Creation date of the piece (can be null if unknown)
        artist: List of artists for the piece
        sauce:  SAUCE record (can be null if missing)
          title:    The title of the file
          author:   The (nick)name or handle of the creator of the file
          group:    The name of the group or company the creator is employed by
          date:     The date the file was created
          size:     The original file size not including the SAUCE information
          datatype: Type of data
          filetype: Type of file
          tinfo:    Type dependant information
```
