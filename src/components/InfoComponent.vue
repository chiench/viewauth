<template>
  <v-container class="mt-5">
    <v-row class="">
      <v-col cols="6" class="my-2">
         <h2 >
          HỆ THỐNG
        </h2>
        <h1 class="display-2 font-weight-bold mb-3">
            Quản lý người dùng tập trung sử dụng tiêu chuẩn xác thực Oauth2.0
        </h1>

        <p class="subheading font-weight-regular">
         Đơn giản cho nhà phát triển ứng dụng trong việc xây dựng, triển khai các luồng uỷ quyền cụ thể cho ứng dụng web và mobile...
        </p>
        <v-btn color="primary" class="pa-2 rounded-pill "> Tìm hiểu thêm <span></span> </v-btn>
      </v-col>

      <v-col cols="6" class="my-4">
       
        <v-img
          :src="require('../assets/landing-page-1.png')"
          class="my-3"
          contain
          height="200"
        />
      </v-col>

    </v-row>
  </v-container>
</template>

<script>
  export default {
    name: 'HelloWorld',

    data: () => ({
    }),
  }
</script>
