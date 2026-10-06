# Moje wykonanie Lab00

- Login GitHub / pseudonim: Sebstion
- System i terminal (np. Windows + WSL Ubuntu): Windows + Windows PowerShell
- Edytor / IDE: Visual Studio Code
- Wersja Git: 2.53.0.windows.1
- Wersja kompilatora C++: 16.1.0
- Wersje java i javac: java 27 + javac 27
- Link do pierwszego PR (uzupełnij w zadaniu 5): https://github.com/Sebstion/oop-lab00-Sebstion/pull/1

## Uruchomienie lokalne
Wynik programu C++:
```Hello from C++!  Author: Sebstion
...
```
Wynik programu Java:
```Hello from Java! Author: Sebstion
...
```

## Błąd i poprawka (zadanie 5)
- Krótki fragment komunikatu błędu i numer linii: "error: expected ‘;’ before ‘return’" linia nr 5
- Przyczyna oraz sposób naprawy: brak średnika, uzupełnienie brakującego średnika
- Commit z błędem (SHA lub link): https://github.com/Sebstion/oop-lab00-Sebstion/actions/runs/37456382439/job/112244908165#logs
- Czy Actions pokazały błąd, a po naprawie sukces? tak

## Krótkie odpowiedzi
1. Co różni commit od push? commit zapisuje postęp lokalnie, a push wrzuca zapisane postępy do repo
2. Dlaczego po scaleniu PR wykonuję lokalnie pull? aby synchronizwać
3. Co potwierdza zielony wynik naszego CI, a czego nie potwierdza? potwierdza kompilacje, uruchomienie, spawność pipeline'u, a nie potwierdza wydajności, logiki, jakości kodu

## Ewentualne problemy środowiska
Brak / opis problemu i sposób rozwiązania: Brak