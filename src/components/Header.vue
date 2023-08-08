<script setup lang="ts"></script>

<template>
  <nav class="bg-gray-500">
    <div class="mx-auto px-2 sm:px-6 lg:px-8">
      <div class="flex items-center justify-between h-16">
        <!-- 左侧logo -->
        <div class="flex-shrink-0 flex items-center hover:cursor-pointer">
          <!-- LOGO 图片位置 -->
          <img class="h-8 w-8" src="@/assets/logo.jpg" alt="Logo" />
          <span class="text-white font-bold ml-2">Laf AI</span>
        </div>
      </div>
    </div>
  </nav>
</template>

<style>
.modal {
  width: 600px;
}
.btn {
  margin: 20px 20px 0 0px;
}
.WxImg {
  width: 300px;
  display: flex;
  justify-content: center;
  align-items: center;
  margin: auto;
}
.cardbox {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
}
.box-card {
  cursor: pointer;
  margin: 20px;
  width: 160px;
  height: 140px;
  border: 2px solid #e6a23c;
  border-radius: 5px;
}

.boxCard {
  width: auto;
  margin: 20px;
  width: 160px;
  height: 140px;
  border: 2px solid #f6f6f6;
  border-radius: 5px;
}

.useNumber {
  width: 50%;
  height: 30px;
  margin: 10px auto;
  text-align: center;
  font-size: 18px;
}
.money {
  width: 70%;
  height: 100px;
  text-align: center;
  margin: auto;
  line-height: 80px;
  margin: auto;
}
.sign {
  font-size: 16px;
  color: #e6a23c;
}
.number {
  width: 100%;
  text-align: center;
  font-size: 28px;
  font-weight: 700;
  color: #e6a23c;
}
.accountbox {
  margin: auto;
  margin-top: 10px;
  display: flex;
}
.cheerbox {
  margin-top: 20px;
  width: 100%;
  display: flex;
  justify-content: right;
}
.payCode {
  display: flex;
  justify-content: center;
  align-items: center;
  margin: auto;
}
</style>
