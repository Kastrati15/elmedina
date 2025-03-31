[inlamning1-databas-mysig-bokhandel.zip](https://github.com/user-attachments/files/19411178/inlamning1-databas-mysig-bokhandel.zip)
Elmedina 
Kastrati
YH24
[databas inlämning1.zip](https://github.com/user-attachments/files/19445052/databas.inlamning1.zip)

Elmedina 
Kastrati 
YH24 
inlämning2 
ng2.zip](https://github.com/user-attachments/files/19476975/bokhandel-inlammning2.zip)
[readme.md](https://github.com/user-attachments/files/19487378/readme.md)# Bokhandel
![bokhandel-inläming2 drawio](https://github.com/user-attachments/assets/bf461769-772b-4f60-9083-15ce71925edd)

Det här projektet innehåller en MySQL-databas för att hantera en bokhandel, där jag lagrar information om kunder, böcker, beställningar och orderrader.

## Innehåll
1. [Introduktion](#introduktion)
2. [Databasstruktur](#databasstruktur)
3. [Installation](#installation)
4. [Användning](#användning)
5. [Backup och återställning](#backup-och-återställning)
6. [Författare](#författare)

---

## Introduktion

I denna databas lagras information om:
- Kunder
- Böcker
- Beställningar
- Orderrader

Projektet är designat för att hantera data om böcker, kunder som gör beställningar, samt varje rad i en beställning.

---

## Databasstruktur

Databasen består av följande tabeller:

1. **Bok**
   - Innehåller information om böcker i bokhandeln.
   - Fält: ISBN, Titel, Författare, Pris, Lagerstatus.

2. **Kund**
   - Innehåller information om kunder.
   - Fält: Epost (primärnyckel), Namn, Telefon, Adress.

3. **Beställning**
   - Innehåller information om kundens beställningar.
   - Fält: Ordernummer (primärnyckel), Epost (kopplat till Kund), Datum, Totalbelopp.

4. **Orderrad**
   - Innehåller information om varje rad i en beställning.
   - Fält: Ordernummer, ISBN, Antal, Pris per bok.
   - Relaterar till Beställning och Bok genom främmande nycklar.

---




The Office projektet

[the-office-projekt-er-diagram-readme.zip](https://github.com/user-attachments/files/19541265/the-office-projekt-er-diagram-readme.zip)
