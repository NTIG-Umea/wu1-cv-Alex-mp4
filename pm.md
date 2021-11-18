# CV för fiktiv karaktär | Post Mortem

Alexander Donev Heino, 2021-11-18.

## Inledning

Målet med denna uppgift är att skapa en hemsida i formen av ett CV för en fiktiv karaktär i kollaboration med både Engelskakursen och Digitalt Skapandekursen, då självaste CV:et blivit utskrivet på det tidigare nämnt och en logotyp på det senare. I Webbutveckling fortsätter vi att utveckla det vi redan jobbat på genom en HTML och CSS baserad hemsida.

## Bakgrund

De inledande idé processerna har egentligen redan blivigt genomförda under Engelskalektionerna där vi främst började med att välja en fiktiv karaktär att jobba med. Eftersom man redan var medveten om det som ska göras på Webbutveckling var det bäst att använde lite framtidstänk när det kommer till designen man ska framföra senare. Handsome Jack (mitt val av karaktär) hade redan etablerade designteman korrelerade med honom inom Borderlands serien. På så sätt blev det relativt lätt att följa mallen när det kommer till färg och generella designprinciper.

Framöver började jag processen på att skriva CV:et för min karaktär. Det finns inte speciellt mycket att poängtera just här då det var mest forskning om karaktärens medverkan samt att få fram det som ett CV. Det blev, mer eller mindre, en slags teoretisk del för hela projektet.

På Digitalt Skapandelektionerna började vi med att brainstorma några skisser på självaste logotypen som ska användas för karaktärens hemsida. Här hade jag inga dessvärre problem tack vare "mallen" som Handsome Jack redan hade. Alltså gul och blå färg samt framtidsaktiga teman (dvs hårdakanter). Framöver arbetade vi i Illustrator för att skapa logotypen i helhet.

![Logotyp skiss](/images/logosk.png)
skiss

![HPN logotyp](/images/HPNfärgfinal.svg)
färdig produkt

Nu kommer vi in på det viktiga för just den här kursen, då vi började brainstorma fram självaste hemsidorna på papper. Vi fick fem minuter på oss att skissa fram en simpel sketch och sedan gjorde vi om detta några gånger så att det fanns val och utvecklingar bland idéerna. Med detta i åtanke började man med en mer seriös och välgjord sketch för hemsidan. 

![Skiss hemsida](/images/unknown.png)

Med denna skiss kunde man fortsätta att utveckla sin produkt digitalt på Figma. I grund och botten kan man säga att detta skapar en välpolerad sketch. Det var Figma designen jag främst använde för att dubbelkolla att det jag gör i HTML och CSS matchar med idéerna jag hade tidigare.

![Figma sketch](/images/Figma.png)

Från denna punkt frammåt kunde jag hoppa in i Visual Studio Code och börja skriva upp min hemsida med diverse taggar, attribut och stilar. Detta var definitivt den längsta processen utav allting vi hitills jobbat med. Vi använde all kunskap vi lärt oss av under tidigare Webbutvecklingslektioner för att skapa det som bara varit idéer. Det kom dessutom tillfällen då jag jämförde med andra uppgifter vi skapat innan, exempelvist "songlist" eftersom det fanns struktur som liknade min skiss. Till att börja med var denna process inte speciellt svår för att man börjar med de fundamentala stegen. Det vill säga strukturen som bygger upp grunden av hemsidan, så som header, initiella (div) delar och bilder. Därefter börjar stiliseringen av det tidigare nämnt. Med hjälp av diverse containers kunde jag dela upp CSS:en på den "nakna" strukturen för att ge den liv. Här kastade man in färger, kanter, positionering, storlekar, mm.

När detta var klappat och klart kunde man finslipa allting och börja föra in aspekt som inte var prioriterade tidigare. För mig hamnade mycket av detta på storleksanpassning, mer stilisering och bakgrundsarbete. Storlekar förändrades hit och dit för att båda mina sidor skulle vara uniform med varandra samt lika långa. Stiliseringen kom i flera former, men de viktigaste skulle jag vilja framföra i "Experience" (i.e. den högra) spalten. Här fixade jag en förövrigt relativt ful lista plus en bättre (och temariktig) struktur på de fiktiva arbetsområdena på CV:et. Till exempel en indelning på "position", "employer" och "location" istället för rader av text. Sedan kommer bagrundsarbetet. I bakgrunden av hemsidan kan man se den tidigare visade logotypen på båda sidorna. Detta tog en förvånande lång tid eftersom jag använde många attribut jag var oerfaren med (background position speciellt).

## Positiva erfarenheter

Inte bara var det kul att göra hemsidan som helhet, men jag blev faktiskt väldigt nöjd med den slutgiltiga produkten. Jämför man Figma skissen (men även orginal skissen) med hemsidan nu kan man se att mina idéer funkade i praktiken precis som jag ville. Möjligtvist på grund av den okomplexa naturen av hemsidan. Dessutom känns det bra att jag inte fastnade på något problem och bara gav upp, utan allting jag implementerade funkade förr eller senare. Mycket av detta går definitivt att tacka Jens för men att söka upp problemen på Google gav mig också ofta svaren jag sökte efter.

## Negativa erfarenheter

Helt ärligt fanns det inte några dessvärre negativa tillfällen. Dock går det att berätta om några problem som absolut kunde ha fungerat bättre. Det som jag kan tänka på direkt är bakgrunden med logotyperna eftersom den är väldigt beroende på aspect ratio:n av användaren och blir placerade på fel ställe om skärmen är för stor eller för liten. När jag väl förstår hur man anpassar detta framöver skulle jag nog kunna hoppa tillbaka och fixa det problemet. Just nu har jag dock inte nog med kunskap (i åtanke att jag inte bara söker upp det). Jag kan även ha missförstått den direkta använding av < p > taggar. Det märks att jag använt den i många förhållanden där en < div > hade fungerat lika bra, om inte bättre. Utseendemässigt gör detta absolut ingen skillnad (vad jag vet). Men den ena varianten är nog mer rätt än den andra. Så ja, < p > ska enbart användas i mer textbaseradetillfällen, ska tänka på det tills nästa gång.

## Sammanfattning

Jag har skapat en hemsida baserat på ett CV av en fiktiv karaktär. Detta var inte bara en rolig uppgift att göra från början till slut, men jag lärde mig mycket på vägen. Från diverse genomgångar, till den hjälp jag fått både fysiskt och digitalt från internet har jag fått en slutprodukt jag är nöjd med. Dock finns det än saker som kan förbättras, men de är antingen inte alltför viktiga eller så är de för komplicerade just nu (upptaget i Negativa Erfarenheter). I de största dragen är hemsidan i grund och botten färdig då det inte finns mycket att påbygga förutom storleksanpassning och dark mode tema.