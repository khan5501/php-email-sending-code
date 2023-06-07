I am using this code on laptopswish.com 
<?php
$to = 'recipient@example.com';
$subject = 'Hello from PHP!';
$message = 'This is a test email sent using PHP.';
$headers = 'From: sender@example.com' . "\r\n" .
    'Reply-To: sender@example.com' . "\r\n" .
    'X-Mailer: PHP/' . phpversion();

if (mail($to, $subject, $message, $headers)) {
    echo 'Email sent successfully!';
} else {
    echo 'An error occurred while sending the email.';
}
but its not working. whats the problem in this code. email is not sending
