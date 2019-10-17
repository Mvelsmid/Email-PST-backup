# Email-PST-backup
záloha pst súborov (nie len pst)

Ako makro pracuje:
1. Po spustení makro zapíše do logu informáciu o spustení a zistí či je Outlook spustený.  
  Ak je spustený, zatvorí ho a informáciu opäť zapíše do logu. 
2. Z predvoleného priečinka potom skopíruje všetky súbory a pridá k ním dátum zálohovania.
3. Následne skontroluje či sa v priečinku nachádzajú staršie súbory. 
  Ak nájde staršie súbory ako je uvedený počet dní v konfigurácií, zmaže ich. 
4. Ďalším krokom odošle email. 
  Ako predlohu použije uložený email. 
-Ak bol pred spustením makra Outlook otvorený, skript ho opäť otvorí.

podrobnejší návod nájdete v Ako zálohovať pst súbory Outlooku na NAS Synology.docx
https://github.com/Mvelsmid/Email-PST-backup/raw/master/Ako%20z%C3%A1lohova%C5%A5%20pst%20s%C3%BAbory%20Outlooku%20na%20NAS%20Synology.docx


