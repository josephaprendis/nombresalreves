# nombresalreves
Sub lista()     a = Hoja1.Cells(2, 1)     b = Len(a)     For i = b To 1 Step -1         d = Mid(a, i, 1)         e = e + d         Next i         Hoja1.Cells(2, 4) = e          End Sub
