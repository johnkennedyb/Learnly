<template>
  <v-container fluid fill-height>
    <v-row no-gutters class="fill-height">
      <v-col cols="12" md="6" class="d-none d-md-flex align-center justify-center">
        <v-img src="your-image-url.jpg" class="h-100 w-100" cover></v-img>
      </v-col>
      <v-col cols="12" md="6" class="d-flex align-center justify-center">
        <v-card class="pa-8" outlined max-width="500px">
          <v-card-title class="d-md-none justify-center">Sign Up</v-card-title>
          <v-card-title class="d-none d-md-flex justify-center">Create an Account</v-card-title>
          <v-card-text>
            <v-form>
              <v-text-field
                label="Username"
                prepend-icon="mdi-account"
                outlined
                dense
                class="mb-4"
              ></v-text-field>
              <v-text-field
                label="Email"
                prepend-icon="mdi-email"
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
              <v-text-field
                label="Confirm Password"
                prepend-icon="mdi-lock"
                type="password"
                outlined
                dense
                class="mb-6"
              ></v-text-field>
              <v-row align="center" justify="space-between">
                <v-btn color="primary" class="mr-4">Sign Up</v-btn>
                <v-btn text color="primary" to="/login">Login</v-btn>
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
  name: 'SignUp',
};
</script>

<style scoped>
.v-application--is-ltr .v-input--prepend-inner {
  margin-right: 8px;
}
</style>
