<template>
  <form @submit.prevent="submitForm">
    <div>
      <label for="name">Nama:</label>
      <input v-model="formData.name" type="text" id="name" required />
    </div>

    <div>
      <label for="email">Email:</label>
      <input v-model="formData.email" type="email" id="email" required />
    </div>

    <div>
      <label for="school">Asal Sekolah:</label>
      <input v-model="formData.school" type="text" id="school" required />
    </div>

    <button type="submit">Daftar</button>
  </form>
</template>

<script>
export default {
  data() {
    return {
      formData: {
        name: '',
        email: '',
        school: '',
      },
    };
  },
  methods: {
    submitForm() {
      // Kirim data formulir ke backend atau lakukan operasi lain sesuai kebutuhan
      console.log('Data yang dikirim:', this.formData);
    },
  },
};
</script>

<style scoped>
/* Gaya formulir Anda di sini */
</style>
