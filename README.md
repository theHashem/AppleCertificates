# AppleCr
Anleitung zur Erstellung von Apple-Zertifikaten


### Auf dem Mac
1. Öffne die Keychain "Schlüsselbundverwaltung".
2. Klick in der Menüleiste neben dem Apfel-Symbol auf "Schlüsselbundverwaltung". Im Dropdown-Menü wählst du "Zertifikatsassistent" und dann "Zertifikat einer Zertifizierungsinstanz anfordern".  
3. Gib deine E-Mail-Adresse und einen allgemeinen Namen ein. Der Name ist nur für dich zur Wiedererkennung.
4. Wähle "Auf der Festplatte sichern" aus und klicke auf "Fortfahren". Es wird eine Datei (z.B. CertificateSigningRequest.certSigningRequest) erstellt. 

### Im Browser 
1. Öffne https://developer.apple.com/account/resources/certificates/list und klicke auf "Neues Zertifikat".
2. Wähle aus, ob du ein "Development" oder "Distribution" Zertifikat brauchst und klicke auf "Weiter".
3. Wähle die CertificateSigningRequest-Datei aus, die du vorhin erstellt hast, und lade das neue Zertifikat herunter.

### Zurück auf dem Mac
1. Füge das Zertifikat in deine Keychain hinzu.
2. Klicke unter "Meine Zertifikate" mit der rechten Maustaste auf das neue Zertifikat und exportiere es im Format "p12".

### Nochmal im Browser 
1. Erstelle auf https://developer.apple.com/account/resources/identifiers/list neue Identifiers (entweder "Explicit" wie com.hashem.it oder "Wildcard" wie com.hashem*).
2. Zum Schluss erstellst und lädst du auf der Profiles-Seite neue Profile für deine ausgewählten Geräte herunter.
