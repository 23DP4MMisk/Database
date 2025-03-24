# Database

## Uzdevums 1: Izveidojiet vienīgo indeksu (Unique Index)
Izveidojiet kolekciju ar vienīgu indeksu laukam "email".

db.collection.createIndex({ email: 1 }, { unique: true })
Teorija: Vienīgais indekss nodrošina, ka vērtības konkrētā laukā būs unikālas visās dokumentu kopumā. Tas palīdz izvairīties no dublējumiem.
