<template>
  <v-container fluid fill-height>
    <v-row no-gutters class="fill-height align-stretch">
      <v-col cols="12" md="6" class="d-none d-md-flex">
        <v-img src="https://www.betterteam.com/images/secretary-job-description-5760x3840-2020123.jpeg?crop=4:3,smart&width=1200&dpr=2&format=pjpg&auto=webp&quality=85" class="h-100 w-100" cover></v-img>
      </v-col>
      <v-col cols="12" md="6" class="d-flex align-center justify-center fill-height">
        <v-card class="pa-8" outlined max-width="900px" :class="['fill-height', 'd-flex', 'flex-column', 'justify-center']">
          <v-card-title class="d-md-none justify-center">Invicon</v-card-title>
          <v-card-title class="d-none d-md-flex justify-center">Welcome Back</v-card-title>
          <v-card-text class="fill-height d-flex flex-column justify-center">
            <v-form class="fill-height d-flex flex-column justify-center">
              <v-text-field
                label="Username"
                prepend-icon="mdi-account"
                outlined
                dense
                class="mb-4"
              ></v-text-field>
              <v-text-field
                label="Password"
                prepend-icon="mdi-lock"
                type="password"
                outlined
                dense
                class="mb-6"
              ></v-text-field>
              <v-row align="center" justify="space-between">
                <v-btn color="primary" class="mr-4">Login</v-btn>
                <v-btn text color="primary" to="/signup">Sign up</v-btn>
              </v-row>
            </v-form>
          </v-card-text>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: 'Login',
};
</script>

<style scoped>
.v-application--is-ltr .v-input--prepend-inner {
  margin-right: 8px;
}
</style>
