schema-manage
=============

Schema-manage je nástroj pro správu a verzování schematu databáze. Aktuální
podpora je pro PostgreSQL, MySQL.

Umožňuje:

Verzování kódu, aplikování aktualizací, revertování změn.
Vytváření snapshotů a jejich správu.
Pomáhá při ukládání ručně vytvořených změn v databázi do repozitáře.
Hlídá, aby se prováděli jen správné změny, a nerozbila se databáze chybným aplikováním patchů.


Installation
------------

The recommended way to install is via Composer:

        composer require tacoberu/composer-schema-manage


And run:

        vendor/bin/schema-manage
