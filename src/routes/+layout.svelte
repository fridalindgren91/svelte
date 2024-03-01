<header class="header"><a href="/about">Om mig</a></header>
<div id="slot-container">
    <slot/>
</div>
<div class="container"><footer class="footer">footer</footer></div>

<style>

#slot-container :global() {
    margin: 20px;
}

.header {
    background-color: grey;
    display: flex;
    flex-direction: row-reverse;
    padding: 20px;
}

.container {
    position: fixed;
    bottom: 0;
    width: 100%;
}

.footer {
    background-color: grey;
    width: 100%;
}

</style>