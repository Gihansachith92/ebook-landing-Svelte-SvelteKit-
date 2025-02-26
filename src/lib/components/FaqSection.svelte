<script>

	import {FaqItem,Button} from "$components";
  import twitterIcon from "$assets/icons/twitter.webp";

</script>

<section class="faq-section">
  <h2 class="mb-l">Frequently asked questions</h2>
  <div class="faq-container">
    <FaqItem/>
  </div>
  <div class="additional-info">
    <Button class="mt-s">BUY NOW</Button>
    <p class="mt-m">Any other questions?</p>
    <a href="https://x.com/gihan_sachith">
      <p>Hit me up on twitter <img src={twitterIcon} class="twitter-icon" alt=""> </p>
    </a>
  </div>
</section>

<style>
  .faq-section{
    padding: 80px 0;
    margin-left: 12vw;
    margin-right: 20vw;
    max-width: 1150px;
  }

  .additional-info{
    display: flex;
    flex-direction: column;
    align-items: center;
    color: gray;
  }

  .twitter-icon{
    width: 16px;
    height: 16px;
  }

  a{
    text-decoration: underline;
  }
</style>