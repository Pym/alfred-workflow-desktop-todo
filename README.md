# Desktop Todo

This is an Alfred Workflow inspired by an [@holman's idea](https://github.com/holman/dotfiles/commit/d774e970a88a04aca8024178849301af6d6ac5c3):

> All `todo` does is put a file on my Desktop with the filename given. That's it. I aggressively prune my desktop of old tasks and keep one or two on there at a time. Once I've finished a todo, I just delete the file. That's it.

Desktop Todo allows you to create/delete empty items on your desktop from Alfred. That's it.

## Usage

### Create a simple todo

Open Alfred and type:

    t my todo item

will create an empty `my todo item` file on `~/Desktop`.

### Create a colorful todo

Adding the `-c` parameter followed by a color number (see below) will set the 'Label' of the file, just as you can do with the Finder.

    t -c2 my important todo item

will create an empty `my important todo item` file on `~/Desktop` labeled in red.

Available colors are:

1.  Orange
2.  Red
3.  Yellow
4.  Blue
5.  Purple
6.  Green
7.  Gray

### Delete a todo

Open Alfred and type `d` followed by a space will list you empty files without extension (assumed as todo items) from `~/Desktop`.

Selecting one and pressing `Enter` will delete it.
