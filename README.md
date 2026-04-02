# MA-CPL1

## TP Configuration

La configuration fonctionne correctement :

<img width="1870" height="763" alt="Résultat" src="https://github.com/user-attachments/assets/e4ac28b1-5f13-45b7-9cfb-004eb57c7263" />

## TP 1
Résultat :

La première fois on peut apercevoir ce résultat :

<img width="483" height="263" alt="image" src="https://github.com/user-attachments/assets/f1ff5745-cdc1-4ef3-a62d-4e35bc8a34ed" />

Ensuite on obtient le résultat suivant.

```json
{
  "requestType": "Appointment Request",
  "requestSubType": "Appointment Scheduling",
  "confidenceScore": "95%",
  "reasoning": "The email subject explicitly states a 'Demande de rendez-vous' which translates to 'Appointment Request'. The email body also requests for a meeting.",
  "outlookCategory": "Appointment Request"
}
```
On voit que le workflow est correctement exécuté.
<img width="712" height="170" alt="image" src="https://github.com/user-attachments/assets/7510b555-2110-4e05-87d6-7cdebafc57d1" />

Le TP1 est fonctionnel.

---

## TP 2

On peut voir que la création du fichier fonctionne :

<img width="311" height="305" alt="image" src="https://github.com/user-attachments/assets/ec7c88e1-927b-48ef-b6ac-b40d4e66d300" />

Les données sont bien dans le fichier et on voit que l'embedding est bien ajouté :

<img width="666" height="756" alt="image" src="https://github.com/user-attachments/assets/6af5363e-37c1-439e-87f5-aeb6b6830a94" />


On voit que le workflow est correctement exécuté.
<img width="1593" height="492" alt="image" src="https://github.com/user-attachments/assets/b2e2bd34-a817-40c0-8ace-293963991636" />

Le TP2 est fonctionnel.

## TP 3 (n8nSimilarité)

On obtient le résultat suivant :

<img width="443" height="754" alt="image" src="https://github.com/user-attachments/assets/0019d35f-f2aa-4d65-81ac-8561ff22871e" />

On voit que le workflow est correctement exécuté.

<img width="1196" height="523" alt="image" src="https://github.com/user-attachments/assets/87024f8a-9b80-4c5e-95ad-fe6549e34e1a" />

Le TP3 est fonctionnel.

## TP 4 (n8nRAG)

On obtient le résultat suivant :

<img width="447" height="443" alt="image" src="https://github.com/user-attachments/assets/9cb41aa9-2904-4b15-8eb5-1e6b0469a21d" />

Version json :

```json
[
  {
    "generated_reply": " Bonjour Christophe Fonseca,\n\nMerci pour votre demande de rendez-vous. Je suis disponible la semaine prochaine et pourraîtré répondre à votre appel de manière immédiate. Pour faciliter le choix de date, pouvez-vous me donner quelques dates qui pourraient vous convenir? Je suis à votre disposition pour discuter de manière plus détaillée.\n\nA bientôt,\n[Votre nom]\n[Votre fonction]"
  }
]
```

On voit que le workflow est correctement exécuté.

<img width="1524" height="519" alt="image" src="https://github.com/user-attachments/assets/41d1fe4a-f5d6-49ca-be3b-e3673d1a7035" />

Le TP4 est fonctionnel.


## TP 5 (AutoReply)

On obtient le résultat suivant :

<img width="1164" height="659" alt="image" src="https://github.com/user-attachments/assets/b3887ad2-7bd3-42e0-a4c3-7e7d1ba162b3" />

On voit que le workflow est correctement exécuté.

<img width="1502" height="514" alt="image" src="https://github.com/user-attachments/assets/f1363bf8-0970-4822-8674-715c98defc83" />

Version json :

```json
[
  {
    "@odata.context": "https://graph.microsoft.com/v1.0/$metadata#users('ce0c5b98-a3d6-4e2b-ae56-cab375eaab92')/messages/$entity",
    "@odata.etag": "W/\"CQAAABYAAAA+PnnITCLISoEMvjruVOniAAAMUfsj\"",
    "id": "AAMkADU2YTA1MjhmLTllNDEtNDY4Yy1iYWFiLWZlNjEyMTI1ZTE0ZABGAAAAAADNWZTXUgnITLAwuaYmEkI2BwA_PnnITCLISoEMvjruVOniAAAAAAEPAAA_PnnITCLISoEMvjruVOniAAAMVmsbAAA=",
    "createdDateTime": "2026-04-02T07:23:41Z",
    "lastModifiedDateTime": "2026-04-02T07:23:41Z",
    "changeKey": "CQAAABYAAAA+PnnITCLISoEMvjruVOniAAAMUfsj",
    "categories": [],
    "receivedDateTime": "2026-04-02T07:23:41Z",
    "sentDateTime": "2026-04-02T07:23:41Z",
    "hasAttachments": false,
    "internetMessageId": "<ZR0P278MB1361736A8EBB1C93D0CF4DDC8F51A@ZR0P278MB1361.CHEP278.PROD.OUTLOOK.COM>",
    "subject": "RE: Demande de rendez-vous",
    "bodyPreview": "Bonjour Christophe Fonseca,\r\n\r\nJe remercie beaucoup votre courtoisie et votre demande de rendez-vous. Je serais heureux de confirmer que nous pouvons planifier un rendez-vous pour la semaine prochaine. Veuillez trouver ci-dessous quelques dates et heures ",
    "importance": "normal",
    "parentFolderId": "AAMkADU2YTA1MjhmLTllNDEtNDY4Yy1iYWFiLWZlNjEyMTI1ZTE0ZAAuAAAAAADNWZTXUgnITLAwuaYmEkI2AQA_PnnITCLISoEMvjruVOniAAAAAAEPAAA=",
    "conversationId": "AAQkADU2YTA1MjhmLTllNDEtNDY4Yy1iYWFiLWZlNjEyMTI1ZTE0ZAAQAH4pHmIics9DuQaEFUZlRbU=",
    "conversationIndex": "AQHcuElNfikeYiJyz0O5BoQVRmVFtbXLcrAO",
    "isDeliveryReceiptRequested": false,
    "isReadReceiptRequested": false,
    "isRead": true,
    "isDraft": true,
    "webLink": "https://outlook.office365.com/owa/?ItemID=AAMkADU2YTA1MjhmLTllNDEtNDY4Yy1iYWFiLWZlNjEyMTI1ZTE0ZABGAAAAAADNWZTXUgnITLAwuaYmEkI2BwA%2BPnnITCLISoEMvjruVOniAAAAAAEPAAA%2BPnnITCLISoEMvjruVOniAAAMVmsbAAA%3D&exvsurl=1&viewmodel=ReadMessageItem",
    "inferenceClassification": "focused",
    "body": {
      "contentType": "html",
      "content": "<html><head>\r\n<meta http-equiv=\"Content-Type\" content=\"text/html; charset=utf-8\"><style type=\"text/css\" style=\"display:none\">\r\n<!--\r\np\r\n\t{margin-top:0;\r\n\tmargin-bottom:0}\r\n-->\r\n</style></head><body dir=\"ltr\">Bonjour Christophe Fonseca,<br><br>Je remercie beaucoup votre courtoisie et votre demande de rendez-vous. Je serais heureux de confirmer que nous pouvons planifier un rendez-vous pour la semaine prochaine. Veuillez trouver ci-dessous quelques dates et heures possibles. S'il y a des heures qui conviennent à vous, merci de m'en faire savoir.<br><br>- Lundi, 25 avril à 14h30<br>- Mardi, 26 avril à 10h00<br>- Mercredi, 27 avril à 16h00<br>- Jeudi, 28 avril à 15h30<br><br>Je me suis également aperçu que vous aviez des emails de type paiement, mot de passe et contrat de travail. Je m'assure que ces emails ont été correctement reçus et que je les traiterai à l'heure.<br><br>A l'attention de votre prochaine connexion, merci de prendre en compte les dates et heures proposées. Je suis à votre disposition pour une réponse ou pour toutes questions supplémentaires.<br><br>Amitiés cordiales.<br><br>[Votre nom]<br>[Votre fonction]<br>[Votre entreprise]<br>[Votre adresse mail] <hr tabindex=\"-1\" style=\"display:inline-block; width:98%\"><div id=\"divRplyFwdMsg\" dir=\"ltr\"><font face=\"Calibri, sans-serif\" color=\"#000000\" style=\"font-size:11pt\"><b>From:</b> Christophe Fonseca Diogo &lt;christophe.fonseca@eduvaud.ch&gt;<br><b>Sent:</b> Friday, March 20, 2026 9:10:51 AM<br><b>To:</b> AIC4a Christophe Fonseca &lt;Christophe.Fonseca@cpnv.me&gt;<br><b>Subject:</b> Demande de rendez-vous</font> <div>&nbsp;</div></div><div><div class=\"elementToProof\" style=\"text-align:left; text-indent:0px; background-color:rgb(255,255,255); margin:0px; font-family:Aptos,Aptos_EmbeddedFont,Aptos_MSFontService,Calibri,Helvetica,sans-serif; font-size:12pt; color:black\">Bonjour,</div><div class=\"elementToProof\" style=\"text-align:left; text-indent:0px; background-color:rgb(255,255,255); margin:0px; font-family:Aptos,Aptos_EmbeddedFont,Aptos_MSFontService,Calibri,Helvetica,sans-serif; font-size:12pt; color:black\">Serait-il possible de planifier un rendez-vous la semaine prochaine ?</div></div></body></html>"
    },
    "sender": {
      "emailAddress": {
        "name": "AIC4a Christophe Fonseca",
        "address": "Christophe.Fonseca@cpnv.me"
      }
    },
    "from": {
      "emailAddress": {
        "name": "AIC4a Christophe Fonseca",
        "address": "Christophe.Fonseca@cpnv.me"
      }
    },
    "toRecipients": [
      {
        "emailAddress": {
          "name": "Christophe Fonseca Diogo",
          "address": "christophe.fonseca@eduvaud.ch"
        }
      }
    ],
    "ccRecipients": [],
    "bccRecipients": [],
    "replyTo": [],
    "flag": {
      "flagStatus": "notFlagged"
    }
  }
]
```
Le TP5 est fonctionnel.
