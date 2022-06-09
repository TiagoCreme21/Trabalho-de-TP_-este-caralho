# Trabalho-de-TP_-este-caralho
----
Public Class Form1

    '''''''''''''''''''''''''Não esquecer de botar a variável contadora cont!!!!!!
    'Dim cont As Integer
    '''
    'Avançar
    If cont <> info.length() - 1 Then
        TextBox1.text = info(cont).nome
        ComboBox1.SelectedItem() = info(cont).escal
        TextBox2.text = info(cont).data.day
        TextBox3.text = info(cont).data.month
        TextBox4.text = info(cont).data.year
        TextBox5.text = info(cont).crs
        cont = cont + 1
    Else
        MessageBox.Show("ERRO","Encontra-se na última posição do registo.",'''Buttonsda Message Box)
    End If
    'Recuar
    Dim cont As Integer
    If cont <> 0 Then
        TextBox1.text = info(cont).nome
        ComboBox1.SelectedItem() = info(cont).escal
        TextBox2.text = info(cont).data.day
        TextBox3.text = info(cont).data.month
        PictureBox1 = info(cont).imagem
        TextBox4.text = info(cont).data.year
        TextBox5.text = info(cont).crs
        cont = cont - 1
    Else
        MessageBox.Show("ERRO","Encontra-se na primeira posição do registo.",'''Buttons da Message Box)
    End If

    'Arranjar a PictureBox

    Dim imagem As Image
    'Adicionar variavel imagem na estrutura e concatenar o add da imagem ao adicionar elementos no geral

End Class
