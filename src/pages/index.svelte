<style>
  section {
    position: relative;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    width: 100vw;
    background-image: url("img/slm.jpg");
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
  }
  section .text {
    position: relative;
    width: 50rem;
    padding: 50px;
    box-shadow: 0 5px 15px rgba(0, 0, 0, 9);
    overflow: hidden;
    color: white;
  }
  section h1 {
    font-size: 4rem;
  }
  .text-change:after {
    content: "";
    animation: animate 2s infinite;
    font-size: 4rem;
  }
  @keyframes animate {
    0% {
      content: "Blockboard";
    }
    50% {
      content: "Plywood";
    }
    100% {
      content: "Laminboard";
    }
  }
</style>

<section>
  <div class="text">
    <h1>
      We sell
      <span class="text-change" />
    </h1>
    <button
      class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4
      rounded-full">
      Products
    </button>
  </div>
  <div />
</section>
