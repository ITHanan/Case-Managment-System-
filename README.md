# Case-Managment-System planing -

# 🗂️ Case Management System (Ärendehanteringssystem)

## 📌 Project Idea (Scenario)
The **Case Management System (CMS)** is a **web-based** application designed to help organizations manage and track various types of cases efficiently and in a structured manner. The system provides features such as:

- ✅ **Case Creation**
- 🔄 **Assignment & Status Tracking**
- 🔔 **Notifications**
- 📊 **Report Generation**

## 🎯 Background & Purpose
Many companies and organizations handle cases inefficiently—either **manually** or using **disorganized systems**. This results in:

🚫 Long processing times  
🚫 Confusion & lack of clarity  
🚫 Difficulty in tracking progress  

A **digital case management system** can solve these issues by:

✔️ Automating workflows for faster processing  
✔️ Enhancing collaboration among users  
✔️ Ensuring compliance with rules & guidelines  

Our goal is to create a **modern, secure, and user-friendly platform** that helps organizations **improve efficiency** and **maintain high-quality case management**.

## 🌍 Vision & Goals
### 🔹 Vision / Problem Statement
We aim to develop a **simple, seamless, and secure** system for case management. The system will help organizations **create, track, and resolve cases** in an organized manner while reducing manual effort and improving user communication.

### 🔹 Target Users
This system is designed for **businesses, government agencies, and organizations** dealing with a large number of cases, such as:

👥 **Customer Service Teams**  
👨‍💼 **HR Departments**  
🛠️ **Support Teams**  

### 🔹 Key Benefits
🚀 **Centralized Case Management** – Keep all cases in one place  
⚡ **Automation** – Reduce manual work and save time  
📢 **Improved Communication** – Ensure all cases are handled correctly and on time  



Funktionella krav 

Här är en lista över funktionella krav som systemet ska uppfylla: 

Användarautentisering och behörigheter 

Systemet ska tillåta användare att logga in med en säker metod (t.ex. tvåfaktorsautentisering). 

Användare ska ha olika roller (administratör, handläggare, kund) med olika behörigheter. 

Ärendehantering 

Användare ska kunna skapa, redigera och radera ärenden. 

Ärenden ska kunna tilldelas specifika handläggare. 

Varje ärende ska ha en status (öppet, pågående, avslutat). 

Notifieringar och kommunikation 

Systemet ska skicka automatiska notifieringar via e-post och/eller SMS vid statusändringar. 

Användare ska kunna kommentera och bifoga filer till ett ärende. 

Sök- och filtreringsfunktion 

Användare ska kunna söka efter ärenden baserat på ID, status, datum och handläggare. 

Systemet ska erbjuda filtrering av ärenden efter kategori och prioritet. 

Rapportering och analys 

Systemet ska kunna generera rapporter över antalet ärenden, handläggningstider och slutförda ärenden. 

Rapporter ska kunna exporteras i PDF- och Excel-format. 

Åtkomstkontroll och säkerhet 

Systemet ska säkerställa att användare endast har åtkomst till information som är relevant för deras roll. 

Alla användaraktiviteter ska loggas för spårbarhet. 

Mobilanpassning 

Systemet ska vara responsivt och fungera på både datorer, surfplattor och mobiltelefoner. 

 

 

Icke-funktionella krav (enkelt förklarat) 

1. Systemet ska vara snabbt och klara många användare 

 Systemet ska kunna hantera minst 10 000 användare samtidigt utan att bli långsamt. 

 Att öppna en sida eller ett ärende ska ta max 3 sekunder. 

 Varför är detta viktigt? 
Om systemet är långsamt blir det jobbigt att använda, och det kan ta för lång tid att lösa ärenden. 

Hur löser vi detta? 
Genom att använda snabba servrar, bra databaser och smarta tekniska lösningar. 

 

2. Systemet måste vara säkert 

 Användardata ska vara krypterad så att ingen obehörig kan läsa den. 

 Endast rätt personer ska kunna se eller ändra information genom behörigheter 

 Systemet måste följa GDPR (lagar om dataskydd). 

Varför är detta viktigt? 
Det skyddar privat information och förhindrar att någon får tillgång till känsliga uppgifter. 

Hur löser vi detta? 
Genom att använda starka lösenord, säker inloggning (t.ex. tvåfaktorsautentisering) och dataskyddsteknik. 

 

3. Systemet ska alltid fungera 

 Systemet ska vara tillgängligt 99,9% av tiden, så att det inte plötsligt slutar fungera. 

Om något går fel ska det finnas säkerhetskopior av all information. 

 

 Varför är detta viktigt? 
Om systemet kraschar kan viktiga ärenden försvinna, vilket skapar stora problem. 

 Hur löser vi detta? 
Genom att använda säkra servrar och göra regelbundna säkerhetskopior. 

 

4. Systemet ska vara enkelt att använda 

Gränssnittet ska vara enkelt och lätt att förstå. 

Det ska fungera både på dator, mobil och surfplatta. 

 

 Varför är detta viktigt? 
Om systemet är krångligt att använda, tar det längre tid att arbeta och kan skapa misstag. 

 Hur löser vi detta? 
Genom att skapa en tydlig design och testa systemet med riktiga användare. 

 

5. Systemet ska logga alla viktiga händelser 

 Alla inloggningar, ändringar och viktiga händelser ska sparas i en logg. 

 Loggarna ska sparas i minst 12 månader. 

 

 Varför är detta viktigt? 
Om något går fel, eller om någon gör något olämpligt, måste det finnas spårbarhet. 

Hur löser vi detta? 
Genom att lagra loggar automatiskt och ge administratörer tillgång till dem. 

 

 

 

 

 

 

 

 

Must Have (M) – Måste finnas med 

Dessa funktioner måste vara på plats för att systemet ska fungera bra: 

Inloggning och behörigheter 

Säker inloggning (t.ex. tvåfaktorsautentisering) 

Användare ska ha olika roller (t.ex. admin, handläggare, kund) med olika rättigheter. 

Ärendehantering 

Möjlighet att skapa, ändra och ta bort ärenden 

Ärenden ska kunna tilldelas en specifik handläggare 

Ärenden ska ha en status (öppet, pågående, avslutat) 

Sök och filtrering 

Kunna söka efter ärenden baserat på t.ex. ID, status och datum 

Filtrera ärenden efter kategori och prioritet 

Notifieringar och kommunikation 

Skicka automatiska meddelanden (e-post/SMS) när status ändras 

Användare ska kunna kommentera och lägga till filer i ärenden 

Åtkomstkontroll och säkerhet 

Användare ska bara kunna se information som är relevant för deras roll 

Should Have (S) – Bör vara med 

Dessa funktioner är viktiga, men systemet kan ändå fungera utan dem: 

Rapportering och analys 

Kunna skapa rapporter om ärenden och handläggningstider 

Möjlighet att exportera rapporter till PDF eller Excel 

Mobilanpassning 

Systemet ska fungera bra på både datorer, surfplattor och mobiltelefoner 

Could Have (C) – Skulle vara bra att ha 

Dessa funktioner är inte nödvändiga, men kan vara bra att ha om tiden räcker till: 

Loggning och spårbarhet 

Logga viktiga händelser, som inloggningar och ändringar av ärenden 

Loggar ska vara tillgängliga för administratörer i minst 12 månader 

Anpassningsbara gränssnitt 

Möjlighet att ändra gränssnittet för en bättre användarupplevelse 

Won't Have (W) – Kommer inte vara med 

Dessa funktioner ingår inte i den här versionen, men kan övervägas senare: 

Det finns inga funktioner här för nu, men i framtiden kan det finnas om behov uppstår. 

 

 

 

 

 
---
## 🛠️ Tech Stack (Planned)
- 💻 **Frontend**: Blazor / ASP.NET MVC
- 🖥️ **Backend**: C# / .NET Core
- 🗄️ **Database**: SQL Server
- ☁️ **Hosting**: Azure / On-Premise

## 📌 Getting Started
### 🔹 Prerequisites
Ensure you have the following installed:
- [ ] .NET SDK
- [ ] SQL Server
- [ ] Git

### 🔹 Installation
```bash
# Clone the repository
git clone https://github.com/your-repo/case-management-system.git

# Navigate to the project directory
cd case-management-system

# Restore dependencies
dotnet restore

# Build the project
dotnet build

# Run the application
dotnet run
```

## 📜 License
This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

---
🚀 **Contributions & Feedback are Welcome!** 🎉
