VIM-LOVE-EFM
------------

This tiny plugin sets up vim so that it can load errors from
a LÖVE (love2d) program. The errors are put in the quickfix list just
as if they where compiler errors. Unlike [vim-lua-ftplugin][ftplugin],
vim-love-efm not only handles syntax erros, but also runtime errors.

For this to work you need to launch your application with the vim `:make`
command.

Technically, this plugin sets the `errorformat` and `makeprg` options
whenever a `.lua` file is loaded.

See Also
--------

*    [vim-lua-ftplugin][ftplugin]


[ftplugin]: https://github.com/xolox/vim-lua-ftplugin
