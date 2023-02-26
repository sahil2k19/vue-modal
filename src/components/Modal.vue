<template>
    <div class="backdrop">
        <div class="modal">
            <h1>Modal content</h1>

            <p>Modal content</p>
        </div> 
    </div>
</template>


<script>
export default{
    components:[],             
    props:[],
    data(){

    },
    methods:{

    }
}
</script>


<style >
    .backdrop{
        top:0;
        position:fixed;
        background: rgba(0, 0, 0, 0.589);
        width: 100%;
        height:100%;
    }
    .modal{
        width:400px;
        padding:20px;
        margin: 129px auto;
        background : white;
        border-radius: 10px ;
    }

    .modal h1{
        color:aqua;
        border:none;
        padding:0;
    }
</style>