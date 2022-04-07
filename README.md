
# Backup Projekt - Verwaltung, Test und Übersicht von Backups

## Konfiguration

Backup Ordner und Dateimuster in die Datei

  /config/backups.php 

eintragen.

Backup Cceck als Cronjob einrichten:

* 5 * * 1,2,3,4,5 `cd /var/www/html/Backup && php /var/www/html/Backup/cron/check_backup.php`

 
