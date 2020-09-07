<?php
include_once 'config.php'
?>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" type="text/css" href="azurrostyle.css" media="screen"/>
    <title>Document</title>
</head>
<body>
            <div class="header">
                    <a href="#default" class="logo">Azurro Owners</a>
                            <div class="header-right">
                                    <a class="active" href="<?php echo base_url()?>index.php">Home</a>
                                    <a class="noactive"href="<?php echo base_url()?>azurrocheck.php">Check</a>
                                    <a class="noactive" href="<?php echo base_url()?>azurrosearch.php">Search</a>
                                    <a class="noactive" href="<?php echo base_url()?>azurrogalery.php">Galery</a>

                            </div>

                            <div class = "headerpic">
                                <img src="azuro.jpg" alt="azurro1" width="72px" height="48px" style="margin-left:35px;" >
                                <img src="azuro2.jpg" alt="azurro2" width="72px" height="48px" style="margin-left:285px;">
                                <img src="azuro3.jpg" alt="azurro3" width="72px" height="48px" style="margin-left:240px;">
                            </div>

            </div>
    
</body> 
</html>
