Package svn-prov
~~~~~~~~~~~~~~~~
Copyright (c) 2009-2022 Martin Scharrer <martin.scharrer@web.de>
See the svn-prov.dtx or svn-prov.ins file for the licence information (LPPL).


This package introduces Subversion variants of the standard LaTeX macros
\ProvidesPackage, \ProvidesClass and \ProvidesFile where the file name and date 
is extracted from Subversion Id keywords. The file name can also be given 
explicitly as an optional argument.

Syntax summary:

\ProvidesPackageSVN [file name]{$Id: ... $}[Package Information (version, description)]
\ProvidesClassSVN [file name]{$Id: ... $}[Class Information (version, description)]
\ProvidesFileSVN [file name]{$Id: ... $}[File Information (version, description)]

