<template>
    <b-navbar toggleable="md" variant="light">

        <b-navbar-toggle target="nav_collapse"></b-navbar-toggle>

        <b-navbar-brand to="/">Criar ERC20 Token</b-navbar-brand>

        <b-collapse is-nav id="nav_collapse">
            <b-navbar-nav>
                <b-nav-item to="/docs.html">Docs</b-nav-item>
                <b-nav-item target="_blank"
                            href="https://lucaskleiner.github.io/ecr20-generator">
                    About
                </b-nav-item>
            </b-navbar-nav>

        
        
        </b-collapse>
    </b-navbar>
</template>

<script>
  export default {
    name: 'Header',
  };
</script>
