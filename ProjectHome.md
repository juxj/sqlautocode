AutoCode is a flexible tool to autogenerate a model from an existing database.

This is a slightly different approach to SqlSoup,
that lets you use tables without explicitly defining them.

Readme excerpt (included in package):

```
Current Maintainer:
    
    Chris Perkins (percious)
    E-mail: chris (at) percious.com

    Simon Pamies (spamsch)
    E-Mail: s.pamies at banality dot de

Authors:

    Paul Johnson (original author)
    
    Christophe de Vienne (cdevienne)
    E-Mail: cdevienne at gmail dot com

    Svilen Dobrev (sdobrev)
    E-Mail: svilen_dobrev at users point sourceforge dot net
    
License:
    
    MIT
    see license.txt

Requirements:

    sqlalchemy 0.6+

Documentation:

    Call sqlautocode.py --help for a list of available self explaining options.

    Example:
    sqlautocode.py -o model.py -u postgres://postgres:user@password/MyDatabase -s myschema -t Person*,Download

```