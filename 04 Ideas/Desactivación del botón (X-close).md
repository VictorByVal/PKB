---
Periodo: Ordinario
aliases:
---
Materia::[[Programación (VBA)]]

Con el código siguiente se puede desactivar el botón "x-close" de un formulario en VBA:
```VBA
Private Sub UserForm_QueryClose(Cancel As Integer, CloseMode As Integer)
	If CloseMode = vbFormControlMenu Then 
		MsgBox "No es posible cerrar la ventana de esa manera"
		Cancel = True 
	End If 
End Sub 
```
