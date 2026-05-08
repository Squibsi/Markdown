# Markdown Dokumentation

## Fordele ved markdown
* Simpel og letlæselig syntax
  * Det er nemt at skrive og læse selv uden at skulle se på tung HTML- eller CSS-kode.
* Platform-uafhængig
  * Markdown-filer (.md) kan åbnes på næsten alle systemer og editorer.
* Fokus på indhold frem for styling
  * Du koncentrerer dig om teksten og strukturen, mens styling håndteres automatisk eller via konvertering.
* Let at versionere med Git
  * Fordi Markdown er ren tekst, er det nemt at se forskelle mellem versioner.
* Understøtter links, billeder og kodeblokke
* Konverterbar til andre formater

## Kodeeksempler
### JavaScript Kodeeksempel for et array med for-loop
```
const biler = [BMW, Mercedes, Opel, Porsche, Kia, Citroën]

for(let i = 0; i < biler.length; i++){
  console.log(biler[i]);
}
```

### HTML kodeeksempel for en navigation med 3 links
```
<html lang="da">
<head>
  <meta charset="UTF-8">
  <title>Eksempel på navigation</title>
  <!-- Link til eksternt stylesheet -->
  <link rel="stylesheet" href="css/style.css">
</head>
<body>

  <nav>
    <a href="#home">Hjem</a>
    <a href="#om-os">Om os</a>
    <a href="#kontakt">Kontakt</a>
  </nav>

</body>
</html>
```

## Billede
![En sød kat.](/img/kat.jpg "En sød kat.")

## Citat med kilde
>
"With great power comes great responsibility"

_-Uncle Ben_
>
Quote: [Uncle Ben](https://www.youtube.com/shorts/a-CBxFjKZ-s).