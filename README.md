# OAuthlogin

Instrukcja uruchomienia.
Logowanie na MacOS działa na Google Chrome. Na Safari nie działa.
Żeby było ciekawiej w pliku login.php linijka 19 musiała być zmienina z $client->setRedirectUri('http://localhost/google_login/login.php'); na 
$client->setRedirectUri('http://localhost:8080/google_login/login.php'); . W takiej konfiguracji działa na MacOS Monteray.

wersja XAMPP 8.0.13

