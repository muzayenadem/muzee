<!DOCTYPE html>
<html>
<head>
<style>

#kk > img{
  width: 100%;
  height: 60vh;
}
#img2{
  width: 100%;
  height: 60vh;
}
#fix2{
  position: fixed;
  margin-top: 20%;
  margin-left: 15%;
  width:70%;
  background-color: #E2E2E2;
  height: 40vh;
  border-radius: 30px;
}
#pic1{
  margin-top: 10%;
  margin-left: 30%;
  width:100px;
  height:100px;
  box-sizing: border-box;
  border-radius: 50%;
  background-color: red;
  position: relative;
}
#plc > img{
  max-width: 100%;
  border-radius: 50%;
  max-height: 100vh;
}
#btn1{
  border: 1px solid red;
  padding: 4px 8px;
  border-radius: 17px;
  background-color: red;
  margin-top:30%;
  margin-left: 65%;
  position:absolute;
}
</style>
    <title>http//:employeemanagementsystem.com</title>
     </head>
      <body>
        <div id="fix"></div>
        <div onclick="ab()">maaam</div>
        <div onclick="inp()"> muzeda</div>
        <div id="kk"></div>
        <script>
        class nam{
  constructor(a){
    this.a=a
    this.b= function(b){
      return this.a=b
    }
  }
  ret(){
    return document.getElementById("kk").innerHTML=this.a
  
  }
}

el = new nam('<img src="br.jpg"></img>')
//el.ret()

function ab(){
el.ret()
}
  function inp(){
  const ps = `<div id="fix2">
  <div id="pic1">
  <div id="plc">
  ${el.ret()}
  </div>
  </div>
  <div id="change"></div>
  <div id="btn1" onclick="as()" >Change</div>
  </div>`
  document.getElementById("fix").innerHTML=ps
  }
function ch(){
  const dd = document.getElementById("input").value;
  el.b(dd)
    document.getElementById("plc").innerHTML=el.ret()
  }
  const as = () =>{
  const sure =  confirm (' are u sure')
  if (sure == true){
    const inp = `<div>
    <input id="input" type="file" placeholder="choice photo"></input>
    </hr>
        <h2 onclick="ch()">SET</h2>
    </div>`
    document.getElementById("change").innerHTML=inp
     }
     else{
       alert("bye bye")
     }
  }
        </script>
      </body>
      </html>
