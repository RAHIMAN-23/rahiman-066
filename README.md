<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Biodata</title>
</head>
<style>

      table {
    border-collapse: collapse;
        border-spacacing: 0;
        margin: 150px 0;
    }
      table th {
    border: 1px solid #aaa;
    width:500px;
    height:30px;
    }    
      table td{
    border: 1px solid #ccc;
    height: 30px;
    padding:0 10px;
    text-align: center;
    }
</style>
<body>
    <table border="1">
    <tr >
            <td colspan="5">BIODATA</td>
    </tr>
        <tr>
            <td>Nama</td>
            <td>Nim</td>
            <td>Fakultas</td>
            <td>Jurusan</td>
            <td>Kelas</td>
        </tr>
        <?php
            for ($i=0; $i < 10 ; $i++) { 
                echo "<tr>";
                echo "<td>Rahiman Harith Syah</td>";
                echo "<td>19024014066</td>";
                echo "<td>Teknik</td>";
                echo "<td>Informatika</td>";
                echo "<td>Kelas B</td>";
                echo "</tr>";
            }
        ?>
    </table>
</body>
</html>
