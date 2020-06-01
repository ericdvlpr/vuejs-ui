<template>
    <b-container fluid>
    
                 <b-row>
                    <b-col>
                        <div>
                            <b-card
                                border-variant="Drive"
                                header="Drive"
                                header-border-variant="Drive"
                                align="left"
                            >
                            <b-row>
                               
                                    <b-col> <b-button variant="outline-secondary">On</b-button></b-col>
                                     <b-col><b-button variant="outline-secondary">Off</b-button></b-col>
                                     <b-col><b-button variant="outline-secondary">setZero</b-button></b-col>
                                    <b-input-group prepend="-2800" append="2800" class="mt-3">
                                        <b-form-input type="range" min="0" max="100"></b-form-input>
                                    </b-input-group>
                            </b-row>
                            <hr />
                                <b-form inline>
                                    <b-row class="my-1">
                                        <b-col sm="6">
                                            <b-input
                                                id="input-1"
                                                class="mb-2 mr-sm-2 mb-sm-0 mr-3"
                                                type="number"
                                                required
                                                placeholder="target"
                                            ></b-input>
                                            
                                        </b-col>
                                        <b-col class="mt-2" sm="3">
                                                <label>[mm/sec]</label>
                                        </b-col>
                                        <b-col sm="3">
                                                <b-button variant="outline-secondary">setSpeed</b-button>
                                        </b-col>
                                    </b-row>
                                    
                                     <b-row class="my-1">
                                        <b-col sm="3">
                                            <label >Wheel Encoder FL </label>
                                        </b-col>
                                        <b-col sm="6">
                                            <b-input
                                            id="input-1"
                                            class="mb-2 mr-sm-2 mb-sm-0"
                                            type="number"
                                            required
                                            ></b-input>  
                                           
                                        </b-col>
                                        <b-col class="mt-2" sm="3">
                                             <label>[mm/sec]</label>
                                        </b-col>
                                    </b-row>
                                    <b-row class="my-1">
                                        <b-col sm="3">
                                             <label class="mr-3">Wheel Encoder FR </label>
                                        </b-col>
                                        <b-col sm="6">
                                           <b-input
                                            id="input-1"
                                            class="mb-2 mr-sm-2 mb-sm-0"
                                            type="number"
                                            required
                                            
                                            ></b-input>   
                                           
                                        </b-col>
                                        <b-col class="mt-2" sm="3">
                                             <label>[mm/sec]</label>
                                        </b-col>
                                    </b-row>

                                    <b-row class="my-1">
                                        <b-col sm="3">
                                             <label class="mr-3">Wheel Encoder RL </label>
                                        </b-col>
                                        <b-col sm="6">
                                           <b-input
                                            id="input-1"
                                            class="mb-2 mr-sm-2 mb-sm-0"
                                            type="number"
                                            required
                                           
                                            ></b-input>   
                                           
                                        </b-col>
                                        <b-col class="mt-2" sm="3">
                                             <label>[mm/sec]</label>
                                        </b-col>
                                    </b-row>
                                    <b-row>
                                        <b-col sm="3">
                                            <label class="mr-3">Wheel Encoder RR </label>
                                        </b-col>
                                        <b-col sm="6">
                                             <b-input
                                            id="input-1"
                                            class="mb-2 mr-sm-2 mb-sm-0"
                                            type="number"
                                            required
                                           
                                            ></b-input> 
                                        </b-col>
                                        <b-col sm="3">
                                            <label>[mm/sec]</label>
                                        </b-col>
                                    </b-row>
                                    <b-row>
                                        <b-col sm="3">
                                            <label class="mr-5">Motor Encoder </label>
                                        </b-col>
                                        <b-col sm="6">
                                            <b-input
                                            id="input-1"
                                            class="mb-2 mr-sm-2 mb-sm-0"
                                            type="number"
                                            required
                                            
                                            ></b-input>  
                                        </b-col>
                                        <b-col sm="3">
                                            <label>[cycle/sec]</label>
                                        </b-col>
                                    </b-row>
                                </b-form>
                            </b-card>
                        </div>
                    </b-col>
                    <b-col>
                        <div>
                            <b-card
                                border-variant="Steer"
                                header="Steer"
                                header-border-variant="Steer"
                                align="left"
                            >
                            <b-row>
                               
                                    <b-col> <b-button variant="outline-secondary">On</b-button></b-col>
                                     <b-col><b-button variant="outline-secondary">Off</b-button></b-col>
                                     <b-col><b-button variant="outline-secondary">setZero</b-button></b-col>
                                    <b-input-group prepend="-2800" append="2800" class="mt-3">
                                        <b-form-input type="range" min="0" max="100"></b-form-input>
                                    </b-input-group>
                            </b-row>
                            <hr />
                             
                                <b-form inline >
                                    <b-row class="mb-3">
                                        <b-col sm="6">
                                             <b-input
                                            id="input-1"
                                            class="mb-2 mr-sm-2 mb-sm-0"
                                            type="number"
                                            required
                                            placeholder="target"
                                            ></b-input>
                                        </b-col>
                                        <b-col sm="3">
                                            <label >[deg]</label>
                                        </b-col>
                                        <b-col sm="3">
                                            <b-button variant="outline-secondary">setAngle</b-button>
                                        </b-col>

                                    </b-row>
                                    
                                    <b-row>
                                        <b-col sm="3">
                                            <label >Servo angle </label>
                                        </b-col>
                                        <b-col sm="6">
                                            <b-input
                                            id="input-1"
                                            class="mb-2 mr-sm-2 mb-sm-0"
                                            type="number"
                                            required
                                            ></b-input> 
                                        </b-col>
                                        <b-col sm="3">
                                            <label>[deg]</label>
                                        </b-col>
                                    </b-row>
                                    <b-row>
                                        <b-col sm="3">
                                            <label class="mr-3">Servo temp </label>
                                        </b-col>
                                        <b-col sm="6">
                                            <b-input
                                            id="input-1"
                                            class="mb-2 mr-sm-2 mb-sm-0"
                                            type="number"
                                            required
                                            
                                            ></b-input>  
                                        </b-col>
                                        <b-col sm="3">
                                            <label>[C]</label>
                                        </b-col>
                                    </b-row>
                                    <b-row>
                                        <b-col sm="3">
                                             <label >Servo current </label>
                                        </b-col>
                                        <b-col sm="6">
                                            <b-input
                                            id="input-1"
                                            class="mb-2 mr-sm-2 mb-sm-0"
                                            type="number"
                                            required
                                            
                                            ></b-input> 
                                        </b-col>
                                        <b-col sm="3">
                                            <label>[mA]</label>
                                        </b-col>
                                    </b-row>

                                    <b-row>
                                        <b-col sm="3">
                                            <label >Servo voltage </label>
                                        </b-col>
                                        <b-col sm="6">
                                            <b-input
                                            id="input-1"
                                            class="mb-2 mr-sm-2 mb-sm-0"
                                            type="number"
                                            required
                                            ></b-input> 
                                        </b-col>
                                        <b-col sm="3">
                                            <label>[mV]</label>
                                            
                                        </b-col>
                                    </b-row>
                                    <br />
                                    <br />
                                    <br />
                                        <b-button  variant="outline-secondary">setAngle</b-button>
                                    </b-form>
                            </b-card>
                        </div>

                    </b-col>
                    <b-col>
                        <div>
                            <b-card
                                border-variant="Direct Input"
                                header="Direct Input"
                                header-border-variant="Direct Input"
                                align="left"
                            >
                                <b-form inline>
                                    <b-form-group id="input-group-4" class="mb-3">
                                        <b-form-checkbox-group id="checkboxes-4">
                                        <b-form-checkbox value="me">Direct Input Enable</b-form-checkbox>
                                        </b-form-checkbox-group>
                                    </b-form-group>  
                                        
                                    <b-row class="my-1">
                                        <b-col sm="4">
                                           <label class="mr-3">str input </label>
                                        </b-col>
                                        <b-col sm="8">
                                                <b-input
                                                id="input-1"
                                                class="mb-2 mr-sm-2 mb-sm-0"
                                                type="number"
                                                required
                                                ></b-input>  
                                        </b-col>
                                    </b-row>

                                    <b-row class="my-1">
                                        <b-col sm="4">
                                           <label class="mr-3">acc input </label>
                                        </b-col>
                                        <b-col sm="8">
                                                <b-input
                                                id="input-1"
                                                class="mb-2 mr-sm-2 mb-sm-0"
                                                type="number"
                                                required
                                                ></b-input>  
                                        </b-col>
                                    </b-row>

                                    <b-row class="my-1">
                                        <b-col sm="4">
                                           <label class="mr-3">brk input </label>
                                        </b-col>
                                        <b-col sm="8">
                                                <b-input
                                                id="input-1"
                                                class="mb-2 mr-sm-2 mb-sm-0"
                                                type="number"
                                                required
                                                ></b-input>  
                                        </b-col>
                                    </b-row>

                                    <b-row class="my-1 mb-5">
                                        <b-col sm="4">
                                           <label class="mr-3">btn input </label>
                                        </b-col>
                                        <b-col sm="8">
                                                <b-input
                                                id="input-1"
                                                class="mb-2 mr-sm-2 mb-sm-0"
                                                type="number"
                                                required
                                                ></b-input>  
                                        </b-col>
                                    </b-row>

                                   <b-row class="my-1">
                                        <b-col sm="4">
                                           <label class="mr-4">str target </label>
                                        </b-col>
                                        <b-col sm="8">
                                                <b-input
                                                id="input-1"
                                                class="mb-2 mr-sm-2 mb-sm-0"
                                                type="number"
                                                required
                                                ></b-input>  
                                        </b-col>
                                    </b-row>

                                    <b-row class="my-1">
                                        <b-col sm="4">
                                           <label class="mr-2">veloc target </label>
                                        </b-col>
                                        <b-col sm="8">
                                                <b-input
                                                id="input-1"
                                                class="mb-2 mr-sm-2 mb-sm-0"
                                                type="number"
                                                required
                                                ></b-input>  
                                        </b-col>
                                    </b-row>
                                       
                                    <b-row class="my-1">
                                        <b-col sm="4">
                                           <label class="mr-3">max veloc</label>
                                        </b-col>
                                        <b-col sm="8">
                                                <b-input
                                                id="input-1"
                                                class="mb-2 mr-sm-2 mb-sm-0"
                                                type="number"
                                                required
                                                ></b-input>  
                                        </b-col>
                                    </b-row>

                                                                   
                                    </b-form>
                            </b-card>
                        </div>
                    </b-col>
                </b-row>
                <br />
                <b-row>
                    <b-col>
                        <div>
                            <b-card
                                border-variant="IMU"
                                header="IMU"
                                header-border-variant="IMU"
                                align="left"
                            >
                                <b-form inline>
                                            
                                    <b-row class="my-1">
                                        <b-col sm="3">
                                            <label >Gyro</label>
                                        </b-col>
                                        <b-col sm="6">
                                            <b-input
                                            id="input-1"
                                            class="mb-2 mr-sm-2 mb-sm-0"
                                            type="number"
                                            required
                                            
                                            ></b-input>  
                                        </b-col>
                                        <b-col sm="3">
                                            <label class="ml-3">[deg/sec]</label>
                                        </b-col>
                                    </b-row>
                                    
                                   
                                    <b-row class="my-1">
                                        <b-col sm="3">
                                            <label class="mr-3">AccX</label>
                                        </b-col>
                                        <b-col sm="6">
                                            <b-input
                                            id="input-1"
                                            class="mb-2 mr-sm-2 mb-sm-0"
                                            type="number"
                                            required
                                            
                                            ></b-input>  
                                        </b-col>
                                        <b-col sm="3">
                                            <label class="ml-3">[G]</label>
                                        </b-col>
                                    </b-row>
                                    <b-row class="my-1">
                                        <b-col sm="3">
                                            <label class="mr-3">AccY </label>
                                        </b-col>
                                        <b-col sm="6">
                                            <b-input
                                            id="input-1"
                                            class="mb-2 mr-sm-2 mb-sm-0"
                                            type="number"
                                            required
                                            
                                            ></b-input>  
                                        </b-col>
                                        <b-col sm="3">
                                            <label class="ml-3" >[G] </label>
                                        </b-col>
                                    </b-row>
                                    <b-row class="my-1">
                                        <b-col sm="3">
                                             <label class="mr-3">AccZ</label>
                                        </b-col>
                                        <b-col sm="6">
                                            <b-input
                                            id="input-1"
                                            class="mb-2 mr-sm-2 mb-sm-0"
                                            type="number"
                                            required
                                           
                                            ></b-input>  
                                            
                                        </b-col>
                                         <b-col sm="3">
                                             <label class="ml-3">[G]</label>
                                             
                                        </b-col>
                                        
                                    </b-row>
                                    <br />
                                    <br />
                                   
                                            <b-button variant="outline-secondary">setOffset</b-button>
                                        
                                    
                                </b-form>
                            </b-card>
                        </div>
                        <br />
                        <div>
                            <b-card
                                border-variant="power"
                                header="power"
                                header-border-variant="power"
                                align="left"
                            >
                                <b-form inline>
                                            
                                    <b-row class="my-1">
                                        <b-col sm="3">
                                            <label class="mr-3">Battery Voltage</label>
                                        </b-col>
                                        <b-col sm="6">
                                            <b-input
                                            id="input-1"
                                            class="mb-2 mr-sm-2 mb-sm-0"
                                            type="number"
                                            required

                                            ></b-input>  
                                        </b-col>
                                        <b-col sm="3">
                                            <label class="mr-3">[V]</label>
                                        </b-col>
                                    </b-row>
             
                                </b-form>
                            </b-card>
                        </div>
                        
                    </b-col>
                    <b-col>
                        <div>
                            <b-card
                                border-variant="IR Obstacle"
                                header="IR Obstacle"
                                header-border-variant="IR Obstacle"
                                align="left"
                            >
                                <b-form inline >
                                   <b-row class="my-1">
                                        <b-col sm="2">
                                            <label class="mr-3">IR0</label>
                                        </b-col>
                                        <b-col sm="8">
                                            <b-input
                                            id="input-1"
                                            class="mb-2 mr-sm-2 mb-sm-0"
                                            type="number"
                                            required
                                            ></b-input>  
                                            
                                        </b-col>
                                        <b-col sm="2" class='mt-1'>
                                            <label class="mr-3">[mm]</label>
                                        </b-col>
                                    </b-row>
                                    <b-row class="my-1">
                                        <b-col sm="2">
                                            <label class="mr-3">IR1</label>
                                        </b-col>
                                        <b-col sm="8">
                                            <b-input
                                            id="input-1"
                                            class="mb-2 mr-sm-2 mb-sm-0"
                                            type="number"
                                            required
                                            ></b-input>  
                                        </b-col>
                                        <b-col sm="2" class='mt-1'>
                                            <label class="mr-3">[mm]</label>
                                        </b-col>
                                    </b-row>
                                    <b-row class="my-1">
                                        <b-col sm="2">
                                            <label class="mr-3">IR2</label>
                                        </b-col>
                                        <b-col sm="8">
                                            <b-input
                                            id="input-1"
                                            class="mb-2 mr-sm-2 mb-sm-0"
                                            type="number"
                                            required
                                            ></b-input>  
                                        </b-col>
                                        <b-col sm="2" class='mt-1'>
                                            <label class="mr-3">[mm]</label>
                                        </b-col>
                                    </b-row>
                                    <b-row class="my-1">
                                        <b-col sm="2">
                                            <label class="mr-3">IR3</label>
                                        </b-col>
                                        <b-col sm="8">
                                            <b-input
                                            id="input-1"
                                            class="mb-2 mr-sm-2 mb-sm-0"
                                            type="number"
                                            required
                                            ></b-input>  
                                        </b-col>
                                        <b-col sm="2" class='mt-1'>
                                            <label class="mr-3">[mm]</label>
                                        </b-col>
                                    </b-row>
                                    <b-row class="my-1">
                                        <b-col sm="2">
                                            <label class="mr-3">IR4</label>
                                        </b-col>
                                        <b-col sm="8">
                                            <b-input
                                            id="input-1"
                                            class="mb-2 mr-sm-2 mb-sm-0"
                                            type="number"
                                            required
                                            ></b-input>  
                                        </b-col>
                                        <b-col sm="2" class='mt-1'>
                                            <label class="mr-3">[mm]</label>
                                        </b-col>
                                    </b-row>
                                    <b-row class="my-1">
                                        <b-col sm="2">
                                            <label class="mr-3">IR5</label>
                                        </b-col>
                                        <b-col sm="8">
                                            <b-input
                                            id="input-1"
                                            class="mb-2 mr-sm-2 mb-sm-0"
                                            type="number"
                                            required
                                            ></b-input>  
                                        </b-col>
                                        <b-col sm="2" class='mt-1'>
                                            <label class="mr-3">[mm]</label>
                                        </b-col>
                                    </b-row>
                                    <b-row class="my-1">
                                        <b-col sm="2">
                                            <label class="mr-3">IR6</label>
                                        </b-col>
                                        <b-col sm="8">
                                            <b-input
                                            id="input-1"
                                            class="mb-2 mr-sm-2 mb-sm-0"
                                            type="number"
                                            required
                                            ></b-input>  
                                        </b-col>
                                        <b-col sm="2" class='mt-1'>
                                            <label class="mr-3">[mm]</label>
                                        </b-col>
                                    </b-row>
                                    <b-row class="my-1">
                                        <b-col sm="2">
                                            <label class="mr-3">IR7</label>
                                        </b-col>
                                        <b-col sm="8">
                                            <b-input
                                            id="input-1"
                                            class="mb-2 mr-sm-2 mb-sm-0"
                                            type="number"
                                            required
                                            ></b-input>  
                                        </b-col>
                                        <b-col sm="2" class='mt-1'>
                                            <label class="mr-3">[mm]</label>
                                        </b-col>
                                    </b-row>
                                </b-form>
                            </b-card>
                        </div>

                    </b-col>
                    <b-col>
                        <div>
                            <b-card
                                border-variant="Thermo"
                                header="Thermo"
                                header-border-variant="Thermo"
                                align="left"
                            >
                                <b-form inline>
   
                                    <b-row class="my-1">
                                        <b-col sm="3">
                                           <label class="mr-3">FET1</label>
                                        </b-col>
                                        <b-col sm="6">
                                                <b-input
                                                id="input-1"
                                                class="mb-2 mr-sm-2 mb-sm-0"
                                                type="number"
                                                
                                                required
                                                ></b-input>  
                                        </b-col>
                                        <b-col sm="3">
                                            <label class="ml-3">[C]</label>
                                        </b-col>
                                    </b-row>
                                    <b-row>
                                        <b-col sm="3">
                                           <label class="mr-3">FET2 </label>
                                        </b-col>
                                        <b-col sm="6">
                                                <b-input
                                                id="input-1"
                                                class="mb-2 mr-sm-2 mb-sm-0"
                                                type="number"
                                                required
                                                ></b-input>  
                                        </b-col>
                                        <b-col sm="3">
                                            <label class="ml-3">[C]</label>
                                        </b-col>
                                    </b-row>


                                                                   
                                </b-form>
                            </b-card>
                        </div>
                    </b-col>
                </b-row>
    </b-container>
</template>
<script>

export default {
  name: 'Template'
}
</script>

<style scoped>
    .container-fluid{
        margin-top: -59px;
    }
    .sidebar{
        float:left;
        background-color:#0984e3;
        width: 20%;
        padding-top: 20%;
        padding-bottom: 25%;
    }
</style>