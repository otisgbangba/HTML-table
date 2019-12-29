# HTML-table
html 
<table>
  <caption>A summary of the UK's most famous punk bands</caption>
  <thead>
    <tr>
      <th scope="col">Name of Class</th>
      <th scope="col">No. of Female Students</th>
      <th scope="col">No. of Male Students</th>
      <th scope="col">Total No. of Students</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">Senior Secondary School 1</th>
      <td>24</td>
      <td>30</td>
      <td>54</td>
    </tr>
    <tr>
      <th scope="row">Senior Secondary School 2</th>
      <td>30</td>
      <td>22</td>
      <td>55</td>
    </tr>
    <tr>
      <th scope="row">Senior Secondary School 3</th>
      <td>35</td>
      <td>19</td>
      <td>54</td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <th scope="row" colspan="3">Total albums</th>
      <td colspan="3">163</td>
    </tr>
  </tfoot>
</table>
{
 ....the styling code in CSS
  font-family: sans-serif;
}

table {
  border-collapse: collapse;
  border: 2px solid rgb(200,200,200);
  letter-spacing: 1px;
  font-size: 0.8rem;
}

td, th {
  border: 1px solid rgb(190,190,190);
  padding: 10px 20px;
}

th {
  background-color: rgb(235,235,235);
}

td {
  text-align: center;
}

tr:nth-child(even) td {
  background-color: rgb(250,250,250);
}

tr:nth-child(odd) td {
  background-color: rgb(245,245,245);
}

caption {
  padding: 10px;
}
