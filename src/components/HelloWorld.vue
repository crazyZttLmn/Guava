<template>
    <el-form ref="form" :model="form" label-width="80px">
      <el-form-item label="假装有">
        <el-input v-model="form.name"></el-input>
      </el-form-item>
    </el-form>
</template>

<script>
  export default {
    data() {
      return {
        form: {
          name: '',
          region: '',
          date1: '',
          date2: '',
          delivery: false,
          type: [],
          resource: '',
          desc: ''
        }
      }
    },
    methods: {
      onSubmit() {
        console.log('submit!');
      }
    }
  }
</script>
