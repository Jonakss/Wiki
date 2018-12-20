<!-- TITLE: Porgramas Pequenos 4 K -->
<!-- SUBTITLE: A quick summary of Porgramas Pequenos 4 K -->

# Problema de escalado con pantallas de alto DPI
Press  Windows Button + R, type `regedit`, and then click OK.
Navigate to the following registry subkey:
HKEY_LOCAL_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > SideBySide
Right-click, select NEW > DWORD (32 bit) Value
Type `PreferExternalManifest`, and then press ENTER.
Right-click PreferExternalManifest, and then click Modify.
Enter Value Data 1 and select Decimal.
Click OK. Exit Registry Editor.

Cambiar el nombre del archivo <a href="">nombrePrograma.manifest</a> y luego copiarlo en la ubicacion del programa

Fuente: http://www.danantonielli.com/adobe-app-scaling-on-high-dpi-displays-fix/