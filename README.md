# Automatic Directory Indexing

* Automatically generates a list of links for all folders/files in the same folder as the `index.php` file.
* It will ignore itself and any files or folders starting with a period.
* It assumes any name with a period in it (but not starting with a period) is a file and not a folder. This is strictly for the purposes of adding a trailing slash to the link text to distinguish folders from files.
* Requires the server supports PHP.
* Useful for media folders containing numerous files (PDFs, images, music).
* Quick workaround when working on Apache servers with `Options -Indexes` enabled.
* Contains some basic alternate styling for link states. Delete or edit the contents of the `style` tag to change these.