<template>
    <div class="container">
        
        <div class="sidebar">
            <ul>
                <li>Dashboard</li>
                <li>Vehicle</li>
                <li>Location</li>
            </ul>
        </div>
        <div class="body">
            <div class="row">
                <div class="remote">
                    <div class="drive remote-item">
                       <div class="btn-group">
                           <button>ON</button>
                            <button>OFF</button>
                            <button>setZero</button>
                       </div>
                        
                    </div>
                     <div class="steer  remote-item">
                        <button>ON</button>
                        <button>OFF</button>
                        <button>setZero</button>
                    </div>
                    <div class="diretInpt  remote-item">
                        <button>ON</button>
                        <button>OFF</button>
                        <button>setZero</button>
                    </div>
                    <div class="drive remote-item">
                        <button>ON</button>
                        <button>OFF</button>
                        <button>setZero</button>
                    </div>
                     <div class="steer  remote-item">
                        <button>ON</button>
                        <button>OFF</button>
                        <button>setZero</button>
                    </div>
                    <div class="diretInpt  remote-item">
                        <button>ON</button>
                        <button>OFF</button>
                        <button>setZero</button>
                    </div>
                   
                </div>
                 
            </div>
        </div>
    </div>


</template>
<script>

export default {
  name: 'Template'
}
</script>

<style>
    .container{
        margin: -58px;
        padding: 0;
    }
    .sidebar{
        float:left;
        background-color:#0984e3;
        width: 20%;
        padding-top: 20%;
        padding-bottom: 25%;
    }
    .body{
        background-color: ghostwhite;
        width: 100%;
        padding-top: 20%;
        padding-bottom: 20%;
    }
    .remote{
        display: grid;
        grid-template-columns: auto auto auto;
        
        padding: 10px;
        grid-column-gap: 10px;
       
    }
    .remote-item{
        margin:10px;
        padding:10px;
        border: 1px solid black;
    }
</style>