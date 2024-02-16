# recoveryOfflineCert
Odzyskiwanie certyfikatu osobistego

  Scenariusz:
  Masz pliki z żółta kłódką, których nie jesteś w stanie otowrzyć - zostały zaszyfrowane (ESF) certyfikatem osobistym użytkownika. Certyfikat został usunięty. Plików takich nie otworzysz korzystając z konta administratora systemu.

  Pliki te można jednak odszyfrować, jeżeli:
    - zachowały się dane w folderach użytkownika, który stracił certyfikat:
        * %APPDATA%\Microsoft\Protected
        * %APPDATA%\Microsotf\Crypto
        * %APPDATA%\Microsoft\SystemCertificates
    - użytkonik zna/pamięta hasło do swojego profilu
 
 Środowisko:
  - wirtualny Windows 10 z oprogramowaniem mimikatz
  - wirtualny Kali linux
  - dostep z tych systemów do w/w katalogoów
Ja korzytam z wirtualizatora Hyper-V. Na nim ma 2 maszyny wirtualne z Windows 10 oraz Kali. Udostępniam w/w foldery.

![obraz](https://github.com/michalkatra/recoveryOfflineCert/assets/53582987/8df7d91d-70a1-43c3-bc5f-952f6685b56d)



