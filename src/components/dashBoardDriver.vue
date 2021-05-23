<template>
 <div class="wrapper">
        <!-- Sidebar  -->
        <nav id="sidebar">
            <div class="sidebar-header">
                <h3 class="title">Welcome #user</h3>
                <div class="frame">
                <img src="../img/pp.png" alt="pp" style="width: 100%; height:100%;">
                </div>
            </div>
        </nav>
        <div class="content" >
                <button type="button" class="btn-block">Overall</button>
        
                <button type="button" class="btn-block">Employees</button>
       
                <button type="button" class="btn-block">Expenses</button>
        
                <button type="button" class="btn-block">Income</button>
        </div>
 </div>
      

            
</template>

<script>

export default {
  

}
</script>

<style>


@import "https://fonts.googleapis.com/css?family=Poppins:300,400,500,600,700";
body {
    font-family: 'Poppins', sans-serif;
    background: #fafafa;
}



.wrapper {
    display: flex;
    /* width: 100%; */
    margin-top:110px;
     
}





#sidebar .sidebar-header {
    background: #027011;
    height: 100vh;
    width: 500px;
    padding: 85px;
    
}
.title{
    
    background-color: #fff; 
    color: #027011; 
    display: block;
    padding-top: 10px;

    
}

.frame {
  width: 310px;
  height: 250px;
  margin-top: 85px;
  margin-bottom:auto;
  margin-left: auto;
  margin-right: auto;
  border: 3px solid #ccc;
  
  justify-content: center;

}
.content{
  background-color: #fff;
  
  display:flex;
  flex-direction: row;
  width: 100%;
  color: white;
  margin: 0 auto;

}

.btn-block{
  
  background-color: Green; /* Green */
  border: 2px solid #fff;
  color: white;
  /* margin-top: 90px; */
  text-align: center;
  text-decoration: none;
  /* display: inline-block; */
  font-size: 22px;
  /* width: 200px;
  height: 50px; */
  margin-left: 25px;
}


</style>