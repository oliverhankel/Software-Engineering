# Wie setze ich unsere Dokumentationsumgebung auf

## Motivation

Um einen besseren Eindruck davon zu erhalten, wie Dokumentation in Software-Projekten gelingen kann, werden wir uns die Dokumentationsumgebung [docusaurus](https://docusaurus.io/docs) anschauen.  

## Umgebung aufsetzen

### IDE: Visual Studio Code

1. [Lade Visual Studio Code herunter](https://code.visualstudio.com/Download) und installiere es
2. Öffne Visual Studio Code
3. Öffne die `Erweiterungen` und installiere:
   1. Markdown Preview Enhanced
   2. Markdown All in One
   3. Markdown Preview Mermaid Support
   4. LanguageTool Linter
   5. LanguageTool for Visual Studio Code
   6. German Support for LanguageTool

### Javascript Runtime: NodeJS

1. [Lade NodeJs herunter](https://nodejs.org/en/download/) und installiere es


2. Öffne eine Powershell oder ein Terminal oder cmd
   
3. Teste Deine Installation
```powershell
node
```
Die sollte die Antwort sein:
```powershell
Welcome to Node.js v16.17.1.
Type ".help" for more information.
> .exit

```

### Doc-Tool: docusaurus

1. Öffne eine Powershell und führe diesen Befehl aus
   
```powershell
npx create-docusaurus@latest doc-poc classic
```

2. Probiere Deine docusaurus Installation aus:
```powershell
cd doc-poc
npm start
```
Dein Standardbrowser sollte sich öffnen und Du solltest Deine PoC sehen


### Diagramme mit Mermaid

1. Öffne eine Powershell oder dergleichen und folge der Anleitung:

https://classic.yarnpkg.com/lang/en/docs/install/#windows-stable

2. Installiere Mermaid
https://github.com/sjwall/mdx-mermaid

3. Füge Mermaid docusaurus hinzu:

    yarn add mdx-mermaid mermaid

4. Editiere `docusarus.config.js`
```javascript
 presets: [
    [
      'classic',
      ({
        docs: {
          remarkPlugins: [require('mdx-mermaid')],
          sidebarPath: require.resolve('./sidebars.js'),
```
5. Teste es 
```powershell
    yarn start
```   




## Beispiel Dokumentation

