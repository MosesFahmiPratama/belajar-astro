<script>
    function specialFunction() {
        alert('you click me!')
    }
</script>

<button on:click={specialFunction}>
    <slot/>
</button>