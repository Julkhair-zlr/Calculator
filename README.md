# Calculator
only used Html and Css
create a calculator folder
inside calculator folder create 2 files one is Calculator.html and second is Calculator,css file
open html file and i add form tag inside form tag i create unother table tag inside i take tr (table row tag) inside i take table header inside table header we use input tag with type=text close </th> tag and </tr>
again create <tr> tag inside tr we can take td table data.
i take input tag type is button id is it's name give the value, onclick event and get input.value+='value and operator'
for equals input.value=eval(input.value)
ex:-<tr>
                <td>
                    <input type="button" id="nine" value="9" onclick="input.value+='9'">
                    <input type="button" id="eight" value="8" onclick="input.value+='8'">
                    <input type="button" id="seven" value="7" onclick="input.value+='7'">
                    <input type="button" id="add" value="+" onclick="input.value+='+'">
                    
                </td>
            </tr>
             <input type="button" id="equal" value="=" onclick="input.value=eval(input.value)">
            
            use css file to style
            
            
            
            in css form contain 
            
    /* margin: 100px 0px 0px 500px */
    display: flex;
    align-items: center;
    justify-content: center;
    /* padding-top: 200px; */
    /* align-self: center; */
    height:100vh;    


table,tr,th,td{
    border: 5px groove red;
    text-align: center;
    background-color: chartreuse;
    border-radius: 10px;
}
input{
    font-size: 25px;
}
input[type=button]{
    /* padding-left: 20px; */
    width: 80px;
    border-radius: 10px;
    
}
input[type=button]:hover,input[type=text]:hover{
    border:5px groove blue;
    border-radius: 5px ;
}
h1{
    color:red;
    font-size: 30px;
    font-weight: bold;
    font-style: italic;
    text-decoration:3px underline;

}
