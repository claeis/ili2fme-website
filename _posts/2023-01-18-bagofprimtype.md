---
author: olivergrimm
title: BAG / LIST OF mit primitiven Typen
categories: [Workbench, Transformer]
tags: [Bag Of, List Of, xtf, chbase]
---

Das Beispiel zeigt, wie mit einer BAG OF und einer LIST OF für primitive Typen (keine Struktur) gearbeitet wird.

[Workbench]({% link /assets/20230118-bagofprimtype.zip %})

Datenmodell:

	CLASS ClassA1 =
        Attr1: BAG {3} OF TEXT*16;
        Attr2: BAG {2} OF 0 .. 60;
        Attr3: BAG {1..2} OF MyEnums;
        Attr4: BAG OF MyFormattedType;
        Attr5: BAG {2..*} OF BLACKBOX XML;
        Attr6: BAG {0..1} OF TEXT*8;
        Attr7: BAG OF DATE;
        Attr8: BAG OF Lkoord;
        Attr9: Lkoord;
    END ClassA1;
