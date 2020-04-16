---
author: ceis
title: Geometrie in Struktur schreiben
categories: [Workbench]
tags: [ STRUCTURE, xtf]
---

Um eine Geomtrie zu schreiben, die im INTERLIS Modell nicht direkt als Attrubt der Klasse modelliert ist, 
sondern als Attribut innerhalb einer Struktur, muss die FME-Geometrie in ein FME-Listen-Attribut extrahiert werden.

[Workbench]({% link /assets/20131106-multilingualwrite.zip %})

Datenmodell:

	STRUCTURE Adresse (ABSTRACT)=
	END Adresse;
	
	STRUCTURE GeografischeAdresse EXTENDS Adresse =
		position : MANDATORY LKoord;
	END GeografischeAdresse;
	
	CLASS Unfall =
		ort : MANDATORY Adresse;
	END Unfall;

