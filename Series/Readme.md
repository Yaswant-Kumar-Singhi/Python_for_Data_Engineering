# Series in python

Series is a one-dimensional labeled array capable of holding data of any type (integer, string, float, python objects, etc.). The axis labels are collectively called index.

Syntax
> pandas.Series( data, index, dtype, copy)

<table style="width:100%">
  <tr>
    <th>data</th>
    <th>index</th>
    <th>dtype</th>
    <th>copy</th>
  </tr>
  <tr>
    <td><strong><em>data</em></strong> takes various forms like ndarray, list, constants</td>
    <td><strong><em>Index </em></strong>values must be unique and hashable, same length as data. Default np.arrange(n) if no index is passed.</td>
    <td><strong><em>dtype </em></strong>is for data type. If None, data type will be inferred</td>
    <td><strong><em>Copy </em></strong>data. Default False</td>
  </tr>
</table>

A series can be created using various inputs like <br>
1.Array <br>
2.Dict  <br> 
3.Scalar value or constant
<br>

<p> Let's dive deeper by practical examples </p><br>
1. <a href="https://github.com/Yaswant-Kumar-Singhi/Python_for_Data_Engineering/blob/main/Series/Create_first_series_object-1.ipynb">Practical Examples - 1</a> <br>
2. <a href="https://github.com/Yaswant-Kumar-Singhi/Python_for_Data_Engineering/blob/main/Series/Assignment-1.ipynb">Assignments</a> <br>

<br>

> This was all about the basic and lets move on and check with attributes and methods of a series object

1. <a href="https://github.com/Yaswant-Kumar-Singhi/Python_for_Data_Engineering/blob/main/Series/Series_Attributes_Methods-2.ipynb">Practical Examples on Attributes and methods - 2</a> <br>

<p> Till now we, know about Series object creation from list, dict. We have also got some familiarity with attributes and methods associated with series. Now, can we create a custom series object having index and values as different list. Lets check <a href="https://github.com/Yaswant-Kumar-Singhi/Python_for_Data_Engineering/blob/main/Series/Arguments_Parameters-3.ipynb">Practical Example 3</a> for this and get a clear understanding of it. <br>
  
