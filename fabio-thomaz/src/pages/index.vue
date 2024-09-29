<template>
  <div class="bg-index">
    <header>
      <v-container class="pl-0">
        <nav class="pl-0">
          <ul>
            <li><a href="/"><v-btn color="blue" variant="text" prepend-icon="mdi-home" class="pl-2">Home</v-btn></a></li>
            <li><a href="/blog"><v-btn color="orange" variant="text" prepend-icon="mdi-book">Blog</v-btn></a></li>
            <li><a href="/logon"><v-btn color="green" variant="text" prepend-icon="mdi-login">Entrar</v-btn></a></li>
          </ul>
        </nav>
      </v-container>
    </header>
    <main>
      <v-container class="container-home mt-0">
        <v-row>
          <v-col>
            <h1>Fabio Thomaz</h1>
            <p>nada por aqui apenas subi o servidor para esta pagina, em breve o site estara top</p>
          </v-col>
        </v-row>
      </v-container>
    </main>
    <v-footer class="bg-foolter">
      <v-container>
        <v-row>
          <v-col>
              <v-btn icon>
                <v-icon>mdi-facebook</v-icon>
              </v-btn>
              <v-btn icon>
                <v-icon>mdi-instagram</v-icon>
              </v-btn>
              <v-btn icon>
                <v-icon>mdi-linkedin</v-icon>
              </v-btn>
              <v-btn icon>
                <v-icon>mdi-github</v-icon>
              </v-btn>
          </v-col>
        </v-row>
      </v-container>
    </v-footer>
  </div>
</template>

<script setup>
//
</script>

<style scoped>
nav {
  position: relative;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1rem;
  color: white;
}

ul {
  display: flex;
  list-style: none;
}

.container-home {
  background-color: rgba(0, 0, 0, 0.5);
  padding: 1rem;
  border-radius: 5px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
  color: white;
  text-align: center;
  margin-top: 2rem;
  margin-bottom: 2rem;
  height: 60vh;
}

.bg-index {
  background-image: url('/images/background01.png');
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  height: 100vh;
  justify-content: center;
  align-items: center;
  color: white;
}

.bg-foolter {
  background-color: transparent;
}
</style>
