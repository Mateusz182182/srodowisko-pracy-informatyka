## Inspiracje (słowa, skojarzenia, pomysły)
- koncentracja, flow, nawyk, rytm dnia
- priorytety, lista rzeczy do zrobienia, backlog
- krótkie sesje pracy *(Pomodoro)*, przerwy regeneracyjne
- **wizualne śledzenie postępów *(progres, streak)***
- prostota, minimalizm interfejsu
- motywacja przez małe cele i nagrody
- integracja z uczelnianym planem zajęć

## Krótka lista elementów projektu
- panel główny: szybki przegląd zadań i nadchodzących terminów
- **lista zadań z priorytetami i tagami**
- edytor zadania *(tytuł, opis, termin, estymowany czas, powtarzanie)*
- kalendarz tygodniowy z przeciąganiem zadań
- timer *(start/pauza/reset, preset Pomodoro)*
- podstawowe statystyki: czas spędzony, wykonane zadania, tygodniowy wykres
- ustawienia użytkownika: kategorie, preferencje timera, powiadomienia
- onboarding / szybki tutorial

## Wstępne dane wejściowe
- lista kategorii (przykłady): Lectures, Homework, Revision, Projects, Exams, Personal
- lista funkcji/atrybutów zadania:
    - id, title, description
    - dueDate, startDate
    - priority (low, medium, high)
    - estimatedMinutes
    - tags (lista)
    - recurring (none, daily, weekly)
    - subtasks (lista)
    - completed (bool)
- ustawienia timera: defaultWork=25, defaultBreak=5, cycles=4
- preferencje tygodnia: weekStart (Mon/Sun)
- metryki do śledzenia: totalTimeToday, tasksCompletedToday, weeklyStreak
- przykładowy profil użytkownika: ```{age: 20, studyField: "Informatyka", studyYear: 2}```

## Lista źródeł pomysłu
- własna potrzeba *(trudności z koncentracją podczas nauki)*
- obserwacje znajomych/studentów i ich nawyków
- inspiracja z istniejących narzędzi do produktywności
- przypadkowe doświadczenia *(egzaminy, deadline'y)*
- warsztaty/spotkania na uczelni dotyczące zarządzania czasem

---
### Podsumowanie
Projekt zakłada stworzenie prostej i minimalistycznej aplikacji dla studentów, która poprzez priorytetyzację zadań, krótkie sesje pracy, wizualne śledzenie postępów oraz integrację z planem zajęć wspiera koncentrację, budowanie nawyków i skuteczne zarządzanie nauką.
