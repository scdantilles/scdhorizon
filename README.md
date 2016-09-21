# scdhorizon

Horizon integration for the SCD Drupal Website

This module connects directly to the database of Horizon to

 * Display the current documents of a user
 * Allow users to download a quitus and close their accounts. A PDF is generated using TCPDF.
 
Additionaly, it also

 * Fetch some CAS variable and store them in the user fields
 * Generate a contact form (and send an email using simple_mail)

The database credentials are declared in settings.php
