# Send-Mail-Wordpress


<pre>
// email data
$name = "hubert <test@test.tld>";
$to = 'info@domain.tld';
$headers = 'From: ' . $name . ' <' . $email . '>' . "\r\n";
$subject = "titel";
$body = "content";


// send email
wp_mail($to, $subject, $body, $headers );
</pre>
