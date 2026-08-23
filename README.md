# Przeglad-swiata-backup-status

Publiczny kanał małych, podpisanych manifestów statusu odseparowanego backupu
pełnej historii kodu projektu Przegląd świata.

To repozytorium nie zawiera kodu, kopii, release assets, sekretów ani metod
uruchamiania backupu. `latest/scheduled` i `latest/manual` są rozdzielone, a
`runs/` zachowuje historyczne pary manifest + detached Ed25519 signature.

Poprawny podpis potwierdza oświadczenie prywatnego destination. Nie jest
niezależną atestacją wykonania przez GitHub i nie daje dostępu do destination.
