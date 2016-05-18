## mods-to-dc.xsl breakdown ##

A repository for reviewing the Library of Congress MODS to DC XSL transform in isolation.

Using the XSL debugging utility of your choice, apply the [transform](./xsl/mods_to_dc.xsl) under xsl against the files of your choice under test.

**NOTE:** You *must* use an XSLT v1 processor; e.g. Saxon 6.5.5, xsltproc, or Xalan (or something else). `xsltproc` is preferred as it is the processor called by the Islandora modules. 