<script>

</script>
  
<div class="navbar">
    <div class="innersection sidebarhead">
        <img alt="Alt goth girl" src="src/images/logo.png"/>
    </div>
    <div class="innersection">
        <h4>Managment</h4>
        <ul class="managment">
            <li>
                <span class="tabtext">
                    Home
                </span>
            </li>
            <li>
                <span class="tabtext">
                    Account
                </span>
            </li>
            <li>
                <span class="tabtext">
                    About
                </span>
            </li>
            <li>
                <span class="tabtext">
                    Generic
                </span>
            </li>
            <li>
                <span class="tabtext">
                    Generic
                </span>
            </li>
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
        border: 1px solid rgba(255, 255, 255, 0.178);
        background-color: black;
    }

    .managment {
        display: flex;
        flex-direction: column;
        height: inherit;
        width: inherit;
        gap: 5px;
        padding: 0;
    }
    
    h4 {
        display: flex;
        margin-left:20px;
    }

    /**
      * How content should look when clicked on
    **/
    li {
        list-style: none;
        background-color:rgba(139, 139, 139, 0.349);
        height: 40px;
        margin-left: 10px;
        margin-right: 10px;
        border-radius: 3px;
        justify-self: center;
        cursor: pointer;
        transition: 0.5s;
    }


    .tabtext {
        display: flex;
        justify-content: flex-start;
        padding-top: 10px;
        margin-left: 10px;
    }

    li:hover{
        background-color:rgb(61, 61, 61)
   }


</style>
  