<!doctype HTML>
<html>
  <head>
	 <meta charset=”utf-8”>
	 <meta name="viewport" content="width=device=width, intitial-scale=1">
  </head>
<body>
  <h1>Inlämningsuppgift del 2</h1>
  
  <strong>1. Förklara kort:</strong>
        
  a) Element: Ett element har en starttag- och en sluttagg för att markera vart innehållets start och slut är.
  Exempel: 
  <pre>
&lt;code&gt; Starttagg & sluttagg.&lt;/code&gt;
  </pre>   
    
  b) Attribut: Förser ytterligare information om elementen och är alltid specifierade i starttagge t.ex. när man infogar en bild.
  <pre> 
&lt;img src="img_girl.jpg" width="200" height="300"&gt;
  </pre>
  c) Värde: Generellt uttrycks attribut  som namn-värde-par samt ett = emellan. Namn-värde-paren skrivs alltid in i starttaggen efter namnet och värdet skrivs alltid mellan ”citattecken”.
  Ett exempel på HTML-element med starttagg som får attributet satt till värde.
  <pre>     
&lt;tag&gt; attribut=”värde”>Text som påverkas av tagg.&lt;/tag&gt;
  </pre>

  <strong>2. Förklara vad HTTP är för något och vad ett kommunikationsprotokoll innebär</strong>

  <strong>HyperText Transfer Protocol (HTTP)</strong> som delas upp i tre beståndsdelar.
  Hypertext: En text som innehåller hyperlänkar eller ”länkar” som sammankopplar olika texter. Hypertexter används mestadels på World Wide Web men även på intranät.
  Transfer: Transfer i HTTP står för sändning och mottagning av information.
  Protocol: Protocol bestämmer hur kommunikationen mellan flera enheter sker. För ett fungerande HTTP finns regler som syftar på ”protocol” i namnet.
  Kommunikationsprotokoll:  Ett exempel är HTTP som är ett kommunikationsprotokoll. HTTP laddar ner webbsidor på internet genom World Wide Web (WWW).


  <strong>3. Vilka är W3C och vilken är deras huvudsakliga uppgift?</strong>
 
  <strong>W3C (World wide web consortium)</strong> Är en internationell organisation som samarbetar med företag och privatpersoner för att utveckla teknisk standardiserad webbaserat innehåll och protokoll.

  <strong>4. Vad står WWW för och vad är detta för något?</strong>

  <strong>World Wide Web,</strong> en tjänst som ger tillgång till datafiler eller webbsidor genom intranät eller internet. Hypertextdokument s.k. webbsidor kan innehålla bilder, text, video samt multimedia och klickbara hyperlänkar.
  Med hjälp av datorprogram, s.k. webbläsare möjliggör nedladdning av filer lagrade på flera olika webbservrar (webbplatser). Hyperlänkarna som finns att klicka på gör det möjligt för navigering mellan webbsidorna.
  Namnet WWW kommer ifrån alla sammanlänkande dokument, både webbservrar och webbsidor som tillsammans bildar en världsvid väv.

  <strong>5.	En typisk internetadress kan se ut på följande vis http://www.facebook.com/home.php</strong>
  
  <strong>a)	Vad kallas denna internetadress på fackspråk?</strong>
  
  URL
  
  <strong>b)	Vad betyder denna förkortning?</strong>

  Uniform Resource Locator (URL) står för en enhetlig metod där man finner resurser och ger information om var och hur resursen kan hämtas.
 
  <strong>c)	Vad kallas:</strong>
  
  <strong>1) http://</strong> 	schema/protokoll
  
  <strong>2) www.facebook.com</strong>   auktoritet/server
  
  <strong>3) /home.php</strong> 	sökväg
  
  <strong>6. Vad använder vi kommunikationsprotokollet FTP till?</strong>

  <strong>Den tidigt populära File Transfer Protocol (FTP)</strong> används som ett kommandobaserat filöverföringsprotokoll via Internet för multimedia och binära filer. För säkrare filöverföring kan man även använda kryptering genom SFTP.

  <strong>7.	Vilken modell bygger HTTP på?</strong>

  Modellen baseras på kommunikationen mellan http klienten (webbläsare) som förfrågar  (webbservern) om hämtning av html fil genom att skicka en kort textsträng till serverns TCP-port, vanligtvis nr 80.
 
  <strong>8. Vad står HTML för och vilken typ av språk är detta?</strong>
 
  HTML står för Hypertext Markup Language och används som märkspråk för att utforma webbsidor. Filer med HTML innehåll anväder för det mesta filändelsen .html.
   
  <strong>9.	Varför använder vi oss av indentering (indrag) när vi skriver HTML-kod?</strong>

  Indenteringen är kotym och finns i de flesta moderna språk inom programmering för att öka läsbarheten av koden.

  <strong>10.	Blir det någon skillnad på utseendet av sidan när du indenterar din HTML-kod?</strong>

  Nej, det blir ingen skillnad
 
  <strong>11.	Varför tror du att vi lär oss behärska HTML-kod från grunden till skillnad från att generera HTML-kod med hjälp av s.k. WYSIWYG-programvaror och HTML-generatorer?</strong>

  Grundkunskaper i HTML-språket är av vikt även vid användning av generatorer och programvaror för att många gånger kontrollera eller korrigera manuellt i HTML-koden. 
 
  <strong>12.	Vilka två delar består ett HTML-dokument av? Vilken sorts information finns i respektive del?</strong>

  HTML-dokument består av block element och inline element.
  
  <strong>Block element:</strong>
  Block element innehar inbyggd padding och margin, börjar alltid från en ny rad och tar upp hela raden med automatisk radbrytning innan och efter varje block. 
  Exempel taggar div, h1-6, p.

  <strong>Inline element:</strong>

  Inline element till skillnad från block element innefattar ingen automatisk kradbrytning eller margin/padding och används direkt i texten.
  har ingen automatisk radbrytning eller padding/margin. Används direkt i text.
  Exempel taggar: a, b, em, span.

  <strong>13.	Varför har vi s.k. HTML-kommentarer i vår kod?</strong>

  Infogandet av kommentarer i sin HTML-kod är användbart när syftet är att kommentarerna inte ska synas på webbsidan. Dessa kommentarer kan handla om anvisningar om manuell filändring för andra personer eller för bättre överblick om man har för mycket koder.
  Ett exempel:
  <pre>  
&lt;!—-kommentaren visas inte på webbläsare--&gt;
  </pre>
 </body> 
</html>
