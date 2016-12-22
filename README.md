Recyclerview
===========================================

This module just aim to add recyclerview dependency for other modules.

BUILDING MODULE
--------------------

Simply run `ant`.


INSTALL MODULE
-------------------

Mac OS X
--------
Copy the distribution zip file into the `~/Library/Application Support/Titanium` folder

Linux
-----
Copy the distribution zip file into the `~/.titanium` folder

Windows
-------
Copy the distribution zip file into the `C:\ProgramData\Titanium` folder


REGISTER MODULE
--------------------

Register your module with your application by editing `tiapp.xml` and adding your module.
Example:

<modules>
	<module version="1.0.0">org.kisio.recyclerview</module>
</modules>

When you run your project, the compiler will combine your module along with its dependencies
and assets into the application.
