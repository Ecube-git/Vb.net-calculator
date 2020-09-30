# Vb.net-calculator
Code Below



Public Class Form1
    Dim result As String
    Dim result1 As Str
    Dim operate As Str

    Private Sub Form1_Load(ByVal sender As System.Object, ByVal e As System.EventArgs) Handles MyBase.Load

    End Sub

    Private Sub Button10_Click(ByVal sender As System.Object, ByVal e As System.EventArgs) Handles Button10.Click
        TextBox1.Text += Button10.Text
    End Sub

    Private Sub btn1_Click(ByVal sender As System.Object, ByVal e As System.EventArgs) Handles btn1.Click
        TextBox1.Text += btn1.Text
    End Sub

    Private Sub btn2_Click(ByVal sender As System.Object, ByVal e As System.EventArgs) Handles btn2.Click
        TextBox1.Text += btn2.Text
    End Sub

    Private Sub btn3_Click(ByVal sender As System.Object, ByVal e As System.EventArgs) Handles btn3.Click
        TextBox1.Text += btn3.Text
    End Sub

    Private Sub btn4_Click(ByVal sender As System.Object, ByVal e As System.EventArgs) Handles btn4.Click
        TextBox1.Text += btn4.Text
    End Sub

    Private Sub btn5_Click(ByVal sender As System.Object, ByVal e As System.EventArgs) Handles btn5.Click
        TextBox1.Text += btn5.Text
    End Sub

    Private Sub btn6_Click(ByVal sender As System.Object, ByVal e As System.EventArgs) Handles btn6.Click
        TextBox1.Text += btn6.Text
    End Sub

    Private Sub btn7_Click(ByVal sender As System.Object, ByVal e As System.EventArgs) Handles btn7.Click
        TextBox1.Text += btn7.Text
    End Sub

    Private Sub btn8_Click(ByVal sender As System.Object, ByVal e As System.EventArgs) Handles btn8.Click
        TextBox1.Text += btn8.Text
    End Sub

    Private Sub btn9_Click(ByVal sender As System.Object, ByVal e As System.EventArgs) Handles btn9.Click
        TextBox1.Text += btn9.Text
    End Sub

    Private Sub btnplus_Click(ByVal sender As System.Object, ByVal e As System.EventArgs) Handles btnplus.Click
        result1 = Val(TextBox1.Text)
        TextBox1.Text = ""
        result = btnplus.Text
    End Sub

    Private Sub btnminus_Click(ByVal sender As System.Object, ByVal e As System.EventArgs) Handles btnminus.Click
        result1 = Val(TextBox1.Text)
        TextBox1.Text = ""
        result = btnminus.Text
    End Sub

    Private Sub btnmulti_Click(ByVal sender As System.Object, ByVal e As System.EventArgs) Handles btnmulti.Click
        result1 = Val(TextBox1.Text)
        TextBox1.Text = ""
        result = btnmulti.Text
    End Sub

    Private Sub btndivi_Click(ByVal sender As System.Object, ByVal e As System.EventArgs) Handles btndivi.Click
        result1 = Val(TextBox1.Text)
        TextBox1.Text = ""
        result = btndivi.Text
    End Sub

    Private Sub btnpoint_Click(ByVal sender As System.Object, ByVal e As System.EventArgs) Handles btnpoint.Click
        TextBox1.Text += btnpoint.Text
    End Sub

    Private Sub btnclear_Click(ByVal sender As System.Object, ByVal e As System.EventArgs) Handles btnclear.Click
        TextBox1.Clear()
    End Sub

    Private Sub btnper_Click(ByVal sender As System.Object, ByVal e As System.EventArgs) Handles btnper.Click
        result1 = Val(TextBox1.Text)
        TextBox1.Text = ""
        result = btnper.Text
    End Sub

    Private Sub btnsq_Click(ByVal sender As System.Object, ByVal e As System.EventArgs) Handles btnsq.Click
        result1 = Val(TextBox1.Text)
        TextBox1.Text = ""
        result = btnper.Text
    End Sub

    Private Sub btnequals_Click(ByVal sender As System.Object, ByVal e As System.EventArgs) Handles btnequals.Click
        operate = Val(TextBox1.Text)
        If result = "+" Then
            TextBox1.Text = result1 + operate
        Else
            If result = "-" Then
                TextBox1.Text = result1 - operate
            Else
                If result = "*" Then
                    TextBox1.Text = result1 * operate
                Else
                    If result = "/" Then
                        TextBox1.Text = result1 / operate
                    Else
                        If result = "%" Then
                            TextBox1.Text = result1 / 100 * operate
                        Else
                            If result = "√" Then

                            End If
                        End If
                    End If
                    End If
                End If
          End If
    End Sub
End Class
