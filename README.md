# XMedicus Blazor Server App

### Nødvendig forberedelse

Vi vil bede dig om at udvikle et lille overbliksbillede i BlazorServer.
I en tom mappe skal du køre følgende kommandoer:  
dotnet new blazorserver -o BlazorApp --no-https -f net7.0    
Derefter skal du installere Newtonsoft.JSON fra nuget i projektet, på den måde du finder det nemmest.

### Struktur
Vi vil bede dig om at bruge FetchData sektionen der følger med projektet.  
Dataen der skal hentes, i programmet, findes på nedenstående link:  
https://gist.githubusercontent.com/adbir/e8b768cc854f0499034cd40fcf34a720/raw

Du skal oprette de dataclasses og services du har brug for, samt de properties du har brug for, for at kunne løse opgaven hensigtsmæssigt. 
De methods du bruger til at besvare spørgsmålene kan enten placeres i code-blokken på FetchData.razor siden ellers lægges i en seperat FetchData.razor.cs-fil.  
Vi anbefaler brugen af LINQ.

### Besvarelser
For en fuldstændig besvarelse skal nedenstående opgaver være løst:  

Hvor mange regenter er der i listen?  
Hvem regerede længst? (Og hvor længe?)  
Hvilken slægt regerede længst? (Og hvor længe?)  
Hvilket navn har været mest populært?  
Hvor længe har Danmark været uden regent?  
Indsætte antallet af objekter i listen, du har hentet, i PageTitle componenten.

### Format

Opgaven afleveres via Github, og et link til dit repository sendes til mikkel@xmedicus.com
