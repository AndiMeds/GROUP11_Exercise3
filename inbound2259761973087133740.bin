<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Group 11</title>
</head>
<body>

<?php

$file_path = 'testing.txt';

if (file_exists($file_path)) {
    
   
    $file_content = file_get_contents($file_path);
    echo "File Content (using file_get_contents): \n" . $file_content . "\n\n";

    
    $file_lines = file($file_path);
    echo "File Content (using file, line by line): \n";
    foreach ($file_lines as $line_number => $line) {
        echo "Line #".($line_number + 1).": " . $line;
    }

} else {
    
    echo "File doesn't exist. Creating a new file...\n";
    
    $new_content = "Heyyyaa, this is a new file!\nThis is for exercise 3!!\n";

    
    file_put_contents($file_path, $new_content);
    echo "File created and content written.\n";
}
?>

</body>
</html>