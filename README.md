# homebrew-oldsqlite
I use this because sqlite 3.14 and higher on brew give a segmentation fault when used together with spatialite and django.

## How and why to install?

I only use this because the sqlite version that's current (3.14.2) gives me a segmentation fault when trying to use it in conjunction with spatialite ondjango.

This will ensure that you have version 3.13.0 installed which should work:

`brew install janezkranjc/oldsqlite/sqlite` and then `brew switch sqlite 3.13.0`.
