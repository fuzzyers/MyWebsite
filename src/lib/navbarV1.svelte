<script>

</script>
  
<div class="navbar">
    <div class="innersection">
        
    </div>
    <div class="innersection">
        <h4>Managment</h4>
        <ul class="managment">
            <li>Home</li>
            <li>Account</li>
            <li>About</li>
            <li>Generic</li>
            <li>Generic</li>
        </ul>
    </div>
    <div class="innersection"></div>
</div>

<style>
    .navbar {
        height: 100vh;
        display: grid;
        grid-template-rows: 1fr 1fr 1fr;
        width: 300px;
        border: 1px solid white;
    }

    .managment {
        display: flex;
        flex-direction: column;
        height: inherit;
        width: inherit;
        gap: 5px;
        padding: 0;
    }
    

    /**
      * How content should look when clicked on
    **/
    li {
        list-style: none;
        background-color:grey;
        height: 40px;
        margin-left: 10px;
        margin-right: 10px;
        border-radius: 3px;
        justify-self: center;
        
    }


</style>
  