<!-- TITLE: Porgramas Pequenos 4 K -->
<!-- SUBTITLE: A quick summary of Porgramas Pequenos 4 K -->

# Problema de escalado con pantallas de alto DPI
1. Press  Windows Button + R, type `regedit`, and then click OK.
2. Navigate to the following registry subkey:
3. HKEY_LOCAL_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > SideBySide
4. Right-click, select NEW > DWORD (32 bit) Value
5. Type `PreferExternalManifest`, and then press ENTER.
6. Right-click PreferExternalManifest, and then click Modify.
7. Enter Value Data 1 and select Decimal.
8. Click OK. Exit Registry Editor.

Cambiar el nombre del archivo <a href="">nombrePrograma.manifest</a> y luego copiarlo en la ubicacion del programa

Fuente: http://www.danantonielli.com/adobe-app-scaling-on-high-dpi-displays-fix/