<template>
  <div class="container">
    <div>
      <Logo />
      <h1 class="title">
        Manami
      </h1>
      <h4 class="subtitle">
        It shouldn't work, but it does.
      </h4>
      <div class="links">
        <a
          href="https://discord.com/oauth2/authorize?client_id=817653964161548289&permissions=8&scope=bot"
          target="_blank"
          rel="noopener noreferrer"
          class="button--black"
        >
          Invite
        </a>
        <a
          href="https://discord.gg/FqtMgjEqqj"
          target="_blank"
          rel="noopener noreferrer"
          class="button--black"
        >
          Support Server
        </a>
        <a
          href="/commands"
          rel="noopener noreferrer"
          class="button--black"
        >
          Commmands
        </a>
        <a
          href="https://github.com/SensionUltra/Manami"
          target="_blank"
          rel="noopener noreferrer"
          class="button--black"
        >
          GitHub
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Roboto Mono', monospace;
  display: block;
  font-weight: 300;
  font-size: 84px;
  color: #ffffff;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #ffffff;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
