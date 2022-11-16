
.space{
  font-family: Calibri; 
  font-size: 15pt;         
  font-style: normal; 
  font-weight: bold; 
  background-color:rgb(55, 63, 8);
  text-align: center; 
  text-decoration: underline
}
.overall{
  background-color:rgb(18, 42, 78);
  color:rgb(249, 250, 246);
  padding:10%
}
.table{
  font-family: Calibri; 
  color:white; 
  font-size: 16pt; 
  font-style: normal;
  font-weight: bold;
  border-collapse: collapse; 
}
.button {
  color: white;
  background-color: #6b491d;
  font-size: 11px;
  width: 90px;
  height: 32px;
  border-width: 0px;
  border-radius: 5px;
  margin-left: 25vh;
}
.edjust{
  width: 15vh;
}

.taxter{
 align: start;
}


function App() {
  return (

    <div className='overall'>
  <div className='space'>
<h1>REGISTRATION FORM </h1>
</div >
<div className='table' align="between" cellpadding = "10">
<td>FIRST NAME</td>
<td><input type="text" name="First_Name" maxlength="30"/>
(max 30 characters a-z and A-Z)
</td>
<tr>
<td>LAST NAME</td>
<td><input type="text" name="Last_Name" maxlength="30"/>
(max 30 characters a-z and A-Z)
</td>
</tr>
<tr>
<td>EMAIL ID</td>
<td><input type="text" name="Email_Id" maxlength="100" /></td>
</tr>
<tr>
<td>MOBILE NUMBER</td>
<td>
<input type="text" name="Mobile_Number" maxlength="10" />
(10 digit number)
</td>
</tr>
<tr>
<td>GENDER</td>
<td>
Male <input type="radio" name="Gender" value="Male" />
Female <input type="radio" name="Gender" value="Female" />
</td>
</tr>

<tr>
<td>ADDRESS <br /><br /><br /></td>
<td><textarea name="Address" rows="4" cols="30"></textarea></td>
</tr>

<button class="button">submit</button>
</div>
</div>

  );
}

export default App;




