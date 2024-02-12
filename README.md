# Hybrid-Friday-Feb-9-CSS
<!DOCTYPE html>
<html>
<head>
<style>
#customers {
  font-family: Times New Roman;
  border-collapse: collapse;
  width: 80%;
}

#customers td, #customers th {
  border: 1px solid #ddd;
  padding: 8px;
}

#customers tr:nth-child(even){background-color: #dccee0;}

#customers tr:hover {background-color: #cea2de;}

#customers th {
  padding-top: 12px;
  padding-bottom: 12px;
  text-align: left;
  background-color: #8186e6;
  color: black;
}
</style>
</head>
<body>

<h1>CSS Tables</h1>
<p>Working with tables in CSS</p>

<table id="customers">
  <tr>
    <th>Company</th>
    <th>Contact</th>
    <th>Country</th>
  </tr>
  <tr>
    <td>Apple</td>
    <td>Thomas Williams</td>
    <td>Japan</td>
  </tr>
  <tr>
    <td>Crafttopia</td>
    <td>Kristina Alfredo</td>
    <td>Norway</td>
  </tr>
  <tr>
    <td>Amazon</td>
    <td>Jeff Bezos</td>
    <td>United States</td>
  </tr>
  <tr>
    
  </tr>
</table>

</body>
</html>


