<template>
  <div class="footer-container">
    <div class="content">
      <h1>Contact Us</h1>
      <div class="text">
        We accept personalized/customized and bulk orders. <br />
        Contact us or send us a message for further details.
      </div>
      <div class="social-media-container">
        <div class="btn">Facebook</div>
        <div class="btn">Instagram</div>
      </div>
      <div class="text email">contact@test.com</div>
      <div class="text email">Bussiness Address</div>
      <div class="text">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Pariatur ex,
        <br />
        soluta minus eligendi fugiat dolorum quia voluptate ad quas.
        <br />
        Voluptate debitis alias quia natus hic quibusdam architecto
      </div>
    </div>
    <div class="credit-container">
      © 2024, <span>Test Corporation.</span> All Rights Reserved.
    </div>
  </div>
</template>

<script setup></script>

<style lang="scss" scoped>
.footer-container {
  width: 100%;
  background: #000;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  padding: 40px 0;

  .content {
    width: var(--max-width);
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;

    h1 {
      font-size: 48px;
    }

    .text {
      color: #ccc;
      font-size: 20px;
      text-align: center;
      line-height: 30px;

      &.email {
        font-weight: bold;
        margin-bottom: 20px;
      }
    }

    .social-media-container {
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 8px;
      margin: 20px 0;

      .btn {
        padding: 8px 24px;
        border: 1px solid #fff;
        border-radius: 4px;
        font-size: 20px;
        cursor: pointer;

        &:hover {
          background: #fff;
          color: #111;
        }
      }
    }
  }

  .credit-container {
    margin-top: 20px;

    span {
      font-weight: bold;
    }
  }
}
</style>
