<template class="bg-gray">
 
<v-card
  elevation="6"
  outlined
class="h-5/7 mx-auto my-28 w-98 text-3xl rounded-3xl">
  <h2 class="text-center font-semibold my-20">SignUp</h2>
  <v-form class="w-4/5 mx-14 h-5/6 my-10 mb-14 mx-auto"
    ref="form"
    v-model="valid"
    lazy-validation
  >


        

           <v-text-field
            v-model="name"
            :counter="10"
            :rules="nameRules"
            required
            density="compact"
            color="gray"
            label="Full Name"
            single-line
            placeholder="Full Name"
            variant="outlined"
            class="mx-5 my-3 "
          ></v-text-field>

           <v-text-field
            v-model="email"
            :rules="emailRules"
            required
            density="compact"
            color="gray"
            label="E-mail"
            single-line
            placeholder="example@gmail.com"
            variant="outlined"
            class="mx-5 my-3"
          ></v-text-field>

          
          <v-text-field
            v-model="password"
            :rules="[rules.required, rules.min]"
            :type="show1 ? 'text' : 'password'"
            density="compact"
            color="gray"
            label="Password"
            single-line
            placeholder="password"
            variant="outlined"
            class="mx-5 mb-5"
          ></v-text-field>

     <v-row class="flex mx-auto">

     <v-btn
      :disabled="!valid"
      size="small"
      flat
      @click="validate"
      color="primary"
      class="text-lg mx-5 mb-20"
    >
      Sign Up
    </v-btn>
     </v-row>

    <v-row class="flex flex-row justify-between">
    

    <a class="text-lg mx-5">Forgot Password?</a>

     <a class="mt-3 text-lg pl-5 font-semibold text-primary">SIGN IN</a>
    </v-row>




   
  </v-form>
</v-card>

</template>
<script>
  export default {
    data: () => ({
      valid: true,
      name: '',
      password: 'Password',
      nameRules: [
        v => !!v || 'Name is required',
        v => (v && v.length <= 10) || 'Name must be less than 10 characters',
      ],
      email: '',
      emailRules: [
        v => !!v || 'E-mail is required',
        v => /.+@.+\..+/.test(v) || 'E-mail must be valid',
      ],

      rules: {
          required: value => !!value || 'Required.',
          min: v => v.length >= 8 || 'Min 8 characters',
          emailMatch: () => (`The email and password you entered don't match`),
        },
      select: null,
      items: [
        'Item 1',
        'Item 2',
        'Item 3',
        'Item 4',
      ],
      checkbox: false,
    }),

    methods: {
      validate () {
        this.$refs.form.validate()
      },
      reset () {
        this.$refs.form.reset()
      },
      resetValidation () {
        this.$refs.form.resetValidation()
      },
    },
  }
</script>