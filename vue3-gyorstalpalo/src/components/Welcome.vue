<script setup>

</script>

<template>
    <h1>taskR</h1>
    <div class="df">
      <h2>A leg<strong>cool</strong>abb task kezelő evör</h2>
      <img
      alt="Vue logo"
      src="../assets/logo.png"
      />
    </div>
    <form class="df">
      <input type="email" placeholder="e-mail">
      <input type="password" placeholder="jelszó">
      <button>Login</button>
    </form>
</template>

<style scoped>
h1 {
  font-size: 7rem;
  text-align: center;
  font-weight: 600;
}
h2 {
  font-size: 1.7rem;
  text-align: right;
  font-weight: normal;
}
img {
  width: 100px;
  height: 100px;
}
form{
  background-color: var(--blue);
  flex-direction: column;
  border-radius: 0.5rem;
  align-items: center;
  justify-content: center;
  padding: 2rem;
  margin-top: 2rem;
}

input {
  font-size: 1.5rem;
  border: none;
  border-radius: 0.5rem;
  background-color: var(--inputBg);
  padding: 0.5rem;
}
button {
  background-color: var(--blue);
  color: #fff;
  border:none;
  font-size: 1.5rem;
}
</style>

34:20