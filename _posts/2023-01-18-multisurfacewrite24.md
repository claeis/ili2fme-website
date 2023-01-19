---
author: ceis
title: MultiSurface schreiben (2.4)
categories: [Workbench, Transformer]
tags: [MultiSurface, xtf, chbase]
---

Das Beispiel zeigt, wie man ein MultiSurface Attribut gemäss INTERLIS 2.4 liest und schreibt.

[Workbench]({% link /assets/20230118-multisurfacewrite2.4.zip %})

Datenmodell:

	CLASS ClassA =
		geometry : GeometryCHLV03_V2.MultiSurface;
	END ClassA;
