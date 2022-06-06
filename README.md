# GoogleLogin
Google Login
<br>
Use Command to Install  The  Client Service <br>

composer require google/apiclient:^2.0
<br>
Then Include The "google_config.php" File WHere you Want to Integrate It 
<br>
button in html for Login <br>
<a href="<?php echo $google_client->createAuthUrl() ?>"></a>
