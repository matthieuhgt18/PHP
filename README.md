<!DOCTYPE html>
<html lang="fr">
    <head>

    <?php


echo "<table border='1'>";
echo "<tr><th>Table de 8</th><th>Résultat</th></tr>";

for ($i = 1; $i <= 10; $i++) {
    echo "<tr>";
    echo "<td> 8 * $i </td>";
    echo "<td>" . ( 8 * $i ) . "</td>";
    echo "<tr/>";
}

echo "</table>";

?>

</body>
    </html>
