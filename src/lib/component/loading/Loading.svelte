<script>
    export let lsize = "lg";
    export let color = "primary";
    export let type = "spinner";
    
</script>
<div class="text-center my-2">
<span class="loading {`loading-${type}`} {`loading-${lsize}`}  {`text-${color}`}"></span>
</div>