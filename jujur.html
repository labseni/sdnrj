<!DOCTYPE html>
<!--
To change this license header, choose License Headers in Project Properties.
To change this template file, choose Tools | Templates
and open the template in the editor.
-->
<html>
    <head>
        <meta charset="UTF-8">
        <title></title>
    </head>
    <body>
        <?php
        // put your code here
        $username="root";
        $password="password";
        $database="temp_database";
  
        mysql_connect(localhost,$username,$password);
        @mysql_select_db($database) or die( "Unable to select database");
  
        $query="SELECT * FROM tempLog";
        $result=mysql_query($query);
  
        $num=mysql_numrows($result);
  
        mysql_close();
  
        $tempValues = array();
  
        $i=0;
        while ($i < $num)
        {
            $dateAndTemps = array();
            $datetime = mysql_result($result,$i,"datetime");
            $temp = mysql_result($result,$i,"temperature");
  
            $dateAndTemps["Date"] = $datetime;
            $dateAndTemps["Temp"] = $temp;
  
            $tempValues[$i]=$dateAndTemps;
            $i++;
        }
  
        echo json_encode($tempValues);
  
?>
        
    </body>
</html>
