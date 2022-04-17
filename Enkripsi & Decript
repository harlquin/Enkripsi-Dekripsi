<?php
//$key should have been previously generated in cryptograpgically safe way, like openssl_random_pseudo_bytes
$plaintext = "1914000038 Alfian";
$cipher = "aes-128-gcm";
$key ="secret";
echo "Cipher Method : ".$cipher;
echo "<br>";
echo "Pesan asal : ".$plaintext;
echo "<br>";

if (in_array($cipher, openssl_get_cipher_methods()))
{
    $ivlen = openssl_cipher_iv_length($cipher);
    $iv = openssl_random_pseudo_bytes($ivlen);
    $ciphertext = openssl_encrypt($plaintext, $cipher, $key, $options=0, $iv, $tag);
    echo "Enkripsi : ".$ciphertext;
    echo "<br>";
    //store $cipher, $iv, and $tag for decryption later
    $original_plaintext = openssl_decrypt($ciphertext, $cipher, $key, $options=0, $iv, $tag);
    echo "Deskripsi : ".$original_plaintext."\n";
}
echo "<br>";
echo "<br>";
$plaintext = "1914000038 Alfian";
$cipher = "aes-192-gcm";
$key ="secret";
echo "Cipher Method : ".$cipher;
echo "<br>";
echo "Pesan asal : ".$plaintext;
echo "<br>";

if (in_array($cipher, openssl_get_cipher_methods()))
{
    $ivlen = openssl_cipher_iv_length($cipher);
    $iv = openssl_random_pseudo_bytes($ivlen);
    $ciphertext = openssl_encrypt($plaintext, $cipher, $key, $options=0, $iv, $tag);
    echo "Enkripsi : ".$ciphertext;
    echo "<br>";
    //store $cipher, $iv, and $tag for decryption later
    $original_plaintext = openssl_decrypt($ciphertext, $cipher, $key, $options=0, $iv, $tag);
    echo "Deskripsi : ".$original_plaintext."\n";
}
echo "<br>";
echo "<br>";
$plaintext = "1914000038 Alfian";
$cipher = "aes-256-gcm";
$key ="secret";
echo "Cipher Method : ".$cipher;
echo "<br>";
echo "Pesan asal : ".$plaintext;
echo "<br>";

if (in_array($cipher, openssl_get_cipher_methods()))
{
    $ivlen = openssl_cipher_iv_length($cipher);
    $iv = openssl_random_pseudo_bytes($ivlen);
    $ciphertext = openssl_encrypt($plaintext, $cipher, $key, $options=0, $iv, $tag);
    echo "Enkripsi : ".$ciphertext;
    echo "<br>";
    //store $cipher, $iv, and $tag for decryption later
    $original_plaintext = openssl_decrypt($ciphertext, $cipher, $key, $options=0, $iv, $tag);
    echo "Deskripsi : ".$original_plaintext."\n";
}
?>
