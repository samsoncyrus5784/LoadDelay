# LoadDelay
Func StartDiablo() Run("C:\Program Files\Diablo II\Diablo II.exe -w -skiptobnet", "C:\Program Files\Diablo II") Sleep("$LoadDelay") WinActive("Diablo II") WinMove("Diablo II,,0, 0, Default, Default") Sleep(6000)  EndFunc
