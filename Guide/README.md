# Podium Guide Translations

**NOTE**: This document is written in preparation for a future Podium software release. The features described below are currently experimental and are not yet publicly available.

This folder contains a copy of the default US English podium-guide.md markdown document which is included with the Podium installer. The guide on GitHub may have edits that are more recent than the guide included with the latest Podium software release. The purpose of putting the guide on GitHub is to provide a place where Podium users can collaborate on translating the guide to other languages. Translated guides will have a language code suffix. For example podium-guide-de.md for the German translation.

The guide document serves two purposes:
1. It is the official user guide for the Podium app, and it can be read as a single document on GitHub or in any markdown capable viewer/editor.
2. It can be used to translate the entire UI of the Podium application.

## How to set up translation of the Podium UI

On the Podium **Preferences>Appearance** dialog page is a field where you can specify the file path of a guide document that should be used for translation. Leaving this field blank will use the default guide document included with the Podium installation. If a translation document is specified, Podium will parse through the document at startup looking for links that indicate texts that should replace the default texts in the Podium UI.

## How the translation works

Podium uses the standard markdown inline link syntax to identify UI texts. Example:

    [](#Track.Name.label)**Track name:** Specifies the name of the track.

This is an empty link, which means the link will not show up when you view the document on GitHub or any other markdown viewer app. It will just show as:

[](#Track.Name.label)**Track name:** Specifies the name of the track.

Podium will detect the "Track name:" part as the text to show in the dialog, and the "Specifies the name of the track." part as an optional description that will be shown as popup help or on the Podium **Help** tab, depending on how you have configured help in Podium.

## Translating the guide

Podium can detect two different uses of translation links:

1. Links specified on header lines (lines starting with #). All the text following the link on the header line is used as the UI text. The entire section below the header (all lines until the next header line) is used as popup help.
2. Links specified in a paragraph. If the text following the link is written in bold (using the \*\* markdown syntax) then that text is used as the UI text, and any text following the bold part (skipping any : character immediately following the bold text) is used as popup help.

When translating to another language, make sure that the URL inside the markdown links are not modified.