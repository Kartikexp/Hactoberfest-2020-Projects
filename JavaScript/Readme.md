# Add in your JavaScript code here
<script>
   function displayTime(){
    let time = new Date();
    console.log(time);
    document.getElementById('time').innerHTML=time;
    }
    setInterval(displayTime , 1000)
</script>
