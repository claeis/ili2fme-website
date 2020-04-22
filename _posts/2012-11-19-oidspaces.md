---
author: ceis
title: OIDSPACES in der XTF-Transferdatei
categories: [Workbench]
tags: [OID, xtf]
---

Das Beispiel zeigt, wie man in der XTF Transferdatei die OIDSPACES Elemente erzeugt.

[Workbench]({% link /assets/20121119-oidspaces.zip %})


Datenmodell:

	CLASS ClassA =
		OID AS INTERLIS.UUIDOID;
		oidattr : INTERLIS.UUIDOID;
		txtattr: TEXT*20;
	END ClassA;


