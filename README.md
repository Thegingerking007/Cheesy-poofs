# Cheesy-poofs
'Woah we can finally do this;
'So will it work now?

DICKS

DUCKS

DUCKS WITH DICKS

'Nic Bailey
'11.28.16
'2nd Period 
'Rates
'This will teach you about arrays

Public Class Form1
    Private Sub btnDisplay_Click(sender As Object, e As EventArgs) Handles btnDisplay.Click
        Dim ratesArr() As Double = {2.2, 2.5, 2.1, 1.9, 7}
        Array.Sort(ratesArr)
        Me.lblMessage.Text = "The lowest rate is " & ratesArr(0).ToString("#.00") & "%"
    End Sub
End Class

'Nick is a Bitch <3
