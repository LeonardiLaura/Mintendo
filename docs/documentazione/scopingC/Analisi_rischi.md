


<style type="text/css">

.column {
    width: 100%;
}
table {
    border-collapse: collapse;
    table-layout: fixed;
    width: 100%;
}

th, td {
    border: 1px solid #ddd;
    text-align: center;
    height: 100px; /* Altezza delle celle */
}

div{
    padding:10px;
    margin:10px;
}
.medium { background-color:rgba(252, 227, 3, 0.3);border-top-style: solid;
border-top-width: 2px;border-top-color: rgb(252, 227, 3);}

.medium_low { background-color:rgba(177, 252, 3, 0.3); border-top-color: rgb(177, 252, 3);border-top-style: solid;
border-top-width: 2px;}
.low { background-color:rgba(0, 175, 0, 0.3); border-top-color: rgb(0, 175, 0);border-top-style: solid;
border-top-width: 2px;}
.medium_high { background-color:rgba(252, 132, 3, 0.3);border-top-color: rgb(252, 132, 3);border-top-style: solid;
border-top-width: 2px;}
.high { background-color:rgba(250, 0, 0, 0.3);border-top-color: rgb(250, 0, 0);border-top-style: solid;
border-top-width: 2px;}
</style>

<div class ="low">
<strong>Nota:</strong> Questo è un blocco note importante.
</div>

<div class ="medium_low">
<strong>Nota:</strong> Questo è un blocco note importante.
</div>

<div class ="medium">
<strong>Nota:</strong> Questo è un blocco note importante.
</div>

<div class ="medium_high">
<strong>Nota:</strong> Questo è un blocco note importante.
</div>

<div class ="high">
<strong>Nota:</strong> Questo è un blocco note importante.
</div>






<table>
    <tr>
        <th colspan="2" rowspan="2"></th>
        <th colspan="5">Probabilità</th>
    </tr>
    <tr>
        <th class="column">Irrilevante</th>
        <th class="column">Bassa</th>
        <th class="column">Moderata</th>
        <th class="column">Alta</th>
        <th class="column">Estrema</th>
    </tr>
    <tr>
        <th rowspan="5">Impatto</th>
        <th>Insignificante</th>
        <td class="low">1</td>
        <td class="medium_low">2</td>
        <td class="medium_low">3</td>
        <td class="medium_low">4</td>
        <td class="medium">5</td>
    </tr>
    <tr>
        <th>Minore</th>
        <td class="medium_low">2</td>
        <td class="medium_low">4</td>
        <td class="medium">6</td>
        <td class="medium">8</td>
        <td class="medium_high">10</td>
    </tr>
    <tr>
        <th>Moderato</th>
        <td class="medium_low">3</td>
        <td class="medium">6</td>
        <td class="medium">9</td>
        <td class="medium_high">12</td>
        <td class="medium_high">15</td>
    </tr>
    <tr>
        <th>Maggiore</th>
        <td class="medium_low">4</td>
        <td class="medium">8</td>
        <td class="medium_high">12</td>
        <td class="medium_high">16</td>
        <td class="high">20</td>
    </tr>
    <tr>
        <th>Catastrofico</th>
        <td class="medium">5</td>
        <td class="medium_high">10</td>
        <td class="medium_high">15</td>
        <td class="high">20</td>
        <td class="high">25</td>
    </tr>
</table>

[Menu](../../index.md)