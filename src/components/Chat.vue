<template>
  <div class="container">
    <div class="box left"></div>
    <section>
      <div class="phone">
        <div class="phone-background">
          <header>
            <div class="header-top"></div>
            <div class="contact">
              <span>&lsaquo;</span>
              <img src="../assets/avatar.jpg" alt="profil picture">
              <div class="name">
                <h3>Samuel Green</h3>
                <p>Available to Walk</p>
              </div>  
              <div class="dots">
                <p>...</p>
              </div>
            </div>
          </header>
          <div class="phone-chat">
            <div class="message message-left">
              <p>That sounds great. I’d be happy with that.</p>
            </div>
            <div class="message message-left">
              <p>Could you send over some pictures of your dog, please?</p>
            </div>
            <div class="img-group">
              <img src="../assets/dog-image-1.jpg" alt="">
              <img src="../assets/dog-image-2.jpg" alt="">
              <img src="../assets/dog-image-3.jpg" alt="">
            </div>
            <div class="message message-right">
              <p>Here are a few pictures. She’s a happy girl!</p>
            </div>
            <div class="message message-right">
              <p>Can you make it?</p>
            </div>
            <div class="message message-left">
              <p>She looks so happy! The time we discussed works. How long shall I take her out for?</p>
            </div>
            <div class="pay-button">
              <div class="circle"></div>
              <p>30 minute walk</p>
              <h1>$29</h1>
            </div>
            <div class="pay-button">
              <div class="circle"></div>
              <p>1 hour walk</p>
              <h1>$49</h1>
            </div>
          </div>
          <div class="input">
            <input type="text" placeholder="Type a message…">
            <button>
              <p>&rsaquo;</p>
              </button>
          </div>
        </div>
      </div>
      <div class="content">
        <h1>Simple booking</h1>
        <p>Stay in touch with our dog walkers through the chat interface. This makes it easy to 
  discuss arrangements and make bookings. Once the walk has been completed you can rate 
  your walker and book again all through the chat.</p>
      </div>
    </section>
    <div class="box right"></div>
  </div>
</template>

<script>
export default {
  name: 'Chat'
}
</script>

<style src='../style.css'>

</style>