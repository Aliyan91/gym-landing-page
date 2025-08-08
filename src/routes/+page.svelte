<script>
  import Conversion from "../components/Conversion.svelte";
  import Faq from "../components/FAQ.svelte";
  import Footer from "../components/Footer.svelte";
  import Hero from "../components/Hero.svelte";
  import Product from "../components/Product.svelte";
  import Review from "../components/Review.svelte";
</script>

<main class="flex flex-col">
  <Hero></Hero>
  <Product />
  <Review />
  <Faq></Faq>
  <Conversion></Conversion>
  <Footer />
</main>

<style lang="postcss">
  @reference "tailwindcss";
  :global(html) {
    background-color: theme(--color-gray-100);
  }
</style>
