<html>
<head>
<title>Changing textbox value based on dropdown list using Ajax and PHP</title>
<meta http-equiv="Content-Type" content="text/html; charset=iso-8859-1">
<script>
//fuction to return the xml http object
function getXMLHTTP() { 
    var xmlhttp=false;  
    try{
        xmlhttp=new XMLHttpRequest();
    }
    catch(e)    {       
        try{            
            xmlhttp= new ActiveXObject("Microsoft.XMLHTTP");
        }
        catch(e){
            try{
            xmlhttp = new ActiveXObject("Msxml2.XMLHTTP");
            }
            catch(e1){
                xmlhttp=false;
            }
        }
    }

    return xmlhttp;
}



function getCurrencyCode(strURL)
{       
var req = getXMLHTTP();     
if (req) 
{
    //function to be called when state is changed
    req.onreadystatechange = function()
    {
        //when state is completed i.e 4
        if (req.readyState == 4) 
        {           
            // only if http status is "OK"
            if (req.status == 200)
            {                       
                document.getElementById('cur_code').value=req.responseText;                     
            } 
            else 
            {
                alert("There was a problem while using XMLHTTP:\n" + req.statusText);
            }
        }               
     }          
     req.open("GET", strURL, true);
     req.send(null);
}           
}
 </script>

 <body style="font: 12px Verdana, Arial, Helvetica, sans-serif;">
 <form style="text-align:center" method="post" action="" name="form1">
 <p>Country : <input type="text" name="country"  onChange="getCurrencyCode('code.php?country='+this.value)">
 </form>
 </body>
 </html>
