
<template>
    <div>
        <header>
            <p>
                Product Layout Page
            </p>
        </header>

        <main>
            <slot />
        </main>

        <footer>
            <p>
                some footer content
            </p>
        </footer>
    </div>
</template>
  
<script>
export default {
    name: 'ProductLayout',
}
</script>
  
<style>
/* Add your custom styles for the layout here */
</style>
  