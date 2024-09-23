<script>
    export default {
        data(){
            return{
            navLink:{
                nameLink:'CHARACTERS',
                
            }
            };
        },
        methods:{

        },
    }
</script>


<template>

    <header>
        <div class="container">
            <div>
                <img src="../assets/img/dc-logo.png" alt="logo">
            </div>
             <div>
                <ul>
                  
                </ul>

            </div>
        </div>
   
    </header>
 
</template>

<!-- per istallare SASS va installato nel terminale con il comando "npm add -D sass" -->
<style lang="scss" scoped>
    header{
        display: flex;
        justify-content: center;
        align-items: center;

        .container{
        width: 1300px;
        margin: 0 20px;
        padding: 0;
        background-color: #FFFFFF;
        height: 150px;
        display: flex;
        justify-content: space-between;
        align-items: center;

        ul {
            display: flex;
            list-style-type: none;
        } a{
            text-decoration: none;
            color: black;
            margin: 0 10px ;
            font-size: 0.6rem;
        }
    }


    }
    

</style>