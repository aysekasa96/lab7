Realtime-intelligentie in Microsoft Fabric
Dit project heeft als doel om gegevens van de aandelenmarkt te verzamelen, analyseren en visualiseren met behulp van Real-Time Intelligence op Microsoft Fabric.

🚀 Project Samenvatting
In dit project:

Er is een realtime-gegevensstroom gecreëerd.

De gegevens werden in de tabel vastgelegd met behulp van Eventhouse.

De gegevens werden geanalyseerd met KQL-query's.

Visualisatie vond plaats via een real-time dashboard.

Waarschuwingen werden geactiveerd op basis van bepaalde voorwaarden via de Activator.

📌 Gebruikte technologieën
Microsoft Fabric

Realtime intelligentie

Eventstream & Eventhouse

KQL (Kusto Query Language)

Dashboard en waarschuwingen

🔧 Installatie en gebruik
1️⃣ Open uw Microsoft Fabric-account: Microsoft Fabric 2️⃣ Maak een werkruimte. 3️⃣ Leg realtimegegevens vast door Eventstream en Eventhouse te configureren. 4️⃣ Analyseer gegevens met KQL-query's. 5️⃣ Maak dashboards en waarschuwingen.

📊 Voorbeeld KQL-query
kql
voorraad
| waar ["tijd"] > geleden(5m)
| vat gem.prijs = gem.(todecimaal(biedprijs)) samen per symbool
| projectsymbool, gemiddelde prijs
🎯 Resultaten
Dit project is een krachtige oplossing om de Real-Time Intelligence-mogelijkheden van Microsoft Fabric te verkennen en de aandelenmarkt in realtime te analyseren.
# lab7
