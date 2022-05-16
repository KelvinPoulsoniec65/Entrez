# Entrez
$nom = InputBox("Information nécessaire", "Entrez le nom de votre personnage"&amp; @CRLF &amp; @CRLF &amp; "(Avec les majuscules)")                      WinSetState($nom,"",@SW_MINIMIZE)                      WinSetState($nom,"",@SW_RESTORE)                      WinMove($nom, "", 0, 0, 1024, 768)                      MsgBox(0,"Information","Fenêtre de " &amp; $nom &amp; " redimensionnée")
