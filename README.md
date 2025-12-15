
# Problema con la versión de Ionic

El problema está en la versión de **Ionic**. Yo utilizo la versión **7**, mientras que la **8** presenta inconvenientes porque `ion-content` emplea **Shadow DOM**.

## Solución: bajar a la versión 7.5.0

Si queréis bajar a la versión que funciona correctamente (**7.5.0**), debéis seguir los siguientes pasos:

```bash
rm C:\Users\usuario\AppData\Roaming\npm\ionic
rm C:\Users\usuario\AppData\Roaming\npm\ionic.cmd
rm C:\Users\usuario\AppData\Roaming\npm\ionic.ps1
npm install rxjs@npm install rxjs@7.5.0
