---
author: ceis
title: MultilingualText Attribut schreiben
categories: [Workbench, Transformer]
tags: [ MultilingualText, xtf, chbase]
---

Das Beispiel zeigt, wie man ein chbase MultilingualText Attribut schreibt.

[Workbench]({% link /assets/20131106-multilingualwrite.zip %})

Datenmodell:

	CLASS ClassA =
		text : LocalisationCH_V1.MultilingualText;
		text2 : LocalisationCH_V1.MultilingualMText;
	END ClassA;

